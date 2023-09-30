- Motivation
	- you have GUI classes that raise a stream of requests
	- There is a potentially variable number of "handler" or "processing element" objects, that can handle these events
	- Need to efficiently process the requests without hard-wiring handler relationships and precedence, or request-to-handler mappings
	- The Chain of Responsibility Pattern chains these processing elements (receiving objects) together, and then passes any request messages from object to object until it reaches an object capable of handling the message
	- the chaining mechanism uses recursive composition to allow an unlimited number of handlers to be linked
	- The Chain of Responsibility works like this:
		- The "receiver" objects are added to the chain
		- the "sender" object has a refence to the first receiver object in the chain
		- Objects in the chain are linked, typically as a one-directional linkedlist with a "next" reference from one node to the next
		- At some point in the program's lifecycle, the sender sends a request to the chain
		- The request is passed along the chain, from one object to the next, until an object (a "handler" or "receiver") handles it. When the request is handled, it is not passed on any longer
		- If no objects handle the request, a default object at the end of the chain can be made to handle it, or it may be that no objects handle the request
		- In a variation of the pattern, multiple objects may handle the request
- Intent
	- Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it
	- Launch-and-leave requests with a single processing pipline that contains many handlers
- Participants
	- Handler
		- defines an interface for handling requests
		- implements the successor link
	- ConcreteHandler
		- handles requests it is responsible for
		- can access its successor
		- If the concretehandler can handle the request, it does so; otherwise it forwards the request to its successor
	- Client
		- initiates the request to a ConcreteHandler object on the chain
- Solution
	- Use the Chain of Responsibility when:
		- you want to decouple the senders and receivers of a request
		- you want to allow handlers to be added dynamically in your code
		- The sender of the request needs to think of this as a "launch and leave" operation, where they place their request at the entrance of the chain pipeline, and then forget about it
		- When multiple objects can react to a request, and typically the order in which the request is handled is important. The most specific objects are at the beginning of the chain, and the most general handlers are at the end of the chain

![[Pasted image 20230404012825.png]]
![[Pasted image 20230404012835.png]]
![[Pasted image 20230404013205.png]]