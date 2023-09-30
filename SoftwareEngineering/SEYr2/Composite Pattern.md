- Motivation
	- Graphics applications, like drawing editors, let users build complex diagrams out of simple components
	- A simple implementation could define classes for graphical primitives such as Text and Lines plus other classes that act as containers for these primitives
	- But there is a problem with this approach
		- Code that uses these classes must treat primitive and container objects differently, (but drawing line is similar to drawing square)
	- Having to distinguish these objects makes the application more complex
	- The composite pattern describes how to use recursive composition so that clients don't have to make this distinction
![[Pasted image 20230403155406.png]]
- Intent
	- Compose objects into tree structures to represent whole-part heirachies
	- Composite lets clients treat individual objects and compositions of objects uniformly
- Also known as
	- Recursive Composition

- Participants
	- Component
		- Declares the interface for objects in the composition
		- implements default behaviour for the interface common to all classes
		- declares an interface for accessing and managing its child components
	- Leaf
		- represents leaf objects in the composition. A leaf has no children
		- defines behaviour for primitive objects in the composition
	- Composite
		- defines behaviour for components having children
		- stores child components 
		- implements child-related operations in the component interface
	- Client
		- manipulates objects in the composition through the component interface
![[Pasted image 20230403160039.png]]

- Solution - Use the composite pattern when
	- You want to develop systems in which a component may be either an individual object or a collection of objects
	- You want to represent recursive composition of objects
	- you want clients to be able to ignore the difference between compositions of objects and individual objects
		- Clients will treat all objects in the composite structure uniformly

### Implementation Summary
- Create a Box Interface
	- has a calculate price function
- Create a Composite Box class
	- Implements box
	- Contains an array list of boxes
		- Could be a product
		- Could be a Composite Box
	- The Composite box can contain a product or another composite box
	- for a getPrice method it will reference all of the boxes in the arraylist (both composite boxes and products)
- Create a Product class
	- Implements box
	- is simply the product
	- Is the "leaf node"
	- for a getPrice method it will simply return its price
