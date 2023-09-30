- Motivation
	- You want to build a user interface where you want to provide 4 list items and one button
	- The initial values of the list item depend on the selected value in the previous list item
![[Pasted image 20230403165238.png]]
- 	
	 - Reusing one of these list items is difficult because it refers to and communicates with other objects
	 - In order to make your code reusable you don't want to hardcode the way these list items are communicating
	 - You can avoid these problems by encapsulating collective behaviour in a seperate mediator object
	 - A mediator is responsible for controlling and coordinating the interactions of a group of objects
	- The mediator serves as a hub that keeps objects in the group from referring to each other explicitly. The objects only know the mediator, thereby reducing the number of interconnections
![[Pasted image 20230403165633.png]]
- Intent 
	- Define an object that encapsulates how a set of objects interact
	- Mediator promotes loose coupling by keeping objects from refering to each other explicitly, and it lets you vary their interaction independently
- Participants
	- Mediator
		- Defines an interface for communicating with colleague objects
	- Concrete Mediator
		- Implements cooperative behaviour by coordinating colleague objects
		- Knows and maintains its colleagues
	- Colleague Classes
		- Each colleague class knows its mediator object
		- each colleague communicates with its mediator whenever it would like to communicate with another colleague
![[Pasted image 20230403170049.png]]
