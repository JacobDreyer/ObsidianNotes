- Motivation
	- Extending the object's functionality can be done statically (at [[Compile Time]]) by using [[Inheritance]]
	- For example, if we have an instance (object) of class Window say mWindow
	- To extend the functionality of the graphical window and adding a frame to the window, we extend the window class to create a FramedWindow
	- To extend the functionality of the FrameWindow once more and adding a scroll bar, we extend the FrameWindow class to create a SBFramedWindow
	- However it might be necessary to extend an object's functionality dynamically (at [[Runtime]]) as an object is used
	- To create a framed window it is necessary to create an object of the FramedWindow class. It would be impossible to start with a plain window object and to extend its functionality at [[Runtime]] to become a framed window
	- With a decorator pattern we can attach additional responsibilities and behaviours to an object dynamically
	- The Frame and Scrollbars that are added are examples of Decorators
- Intent
	- The intent of this pattern is to add additional responsibilities dynamically to an object
	- Wrapping a gift, putting it in a box, and wrapping the box
- Also known as
	- Wrapper
- Participants
	- Component
		- Defines the interface for objects that can have responsibilities added to them dynamically
	- ConcreteComponent
		- Defines an object to which additional responsibilites can be attached
	- Decorator
		- maintains a reference to a component object and defines an interface that conforms to Component's interface
	- ConcreteDecorators
		- ConcreteDecorators extend the functionality of the component by adding state or adding behaviour
- Solution - Use decorator pattern when
	- there is a need to dynamically add as well as remove responsibilities to a class
	- subclassing would be impossible due to the large number of subclasses that could result

![[Pasted image 20230404014514.png]]
![[Pasted image 20230404014641.png]]