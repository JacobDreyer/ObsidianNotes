- While [[SoftwareEngineering/SEYr2/Activity Diagram]]s are used for modeling buisness processes in which several objects participate
- UML state machines are used for modeling the life cycle history of a single reactive object as a [[Finite State Machine]]
	- a machine that can exist in a finite number of states. The machine makes transitions between these states in response to events
- The three key elements of state machines are, states, events, and transitions:
	- State - a situation of an object during which it satisfies some condition, performs some activity, or waits for some event
	- Event - a specific occurence (in time and space) of a stimulus that can trigger a state transition
	- Transistion - the movement from one state to another in response to an event

##### An Example
- A state machine of a light-bulb
- you can send events to a light-bulb via a switch. The two events you can send are turnOn and turnOff
- A state machine diagram contains exactly one state machine for a single reactive object. In this case, the reactive object is in a system containing the light bulb, the switch, and the electricity supply
![[Pasted image 20230314125103.png]]

### State Syntax
- Each state in a state machine may contain zero or more actions and activities
- Action is an atomic execution, whereas activity takes a finite amount of time and can be interupted
- Each action in a state is associated with an internal transition that is triggered by an event
- An internal transition doesn't cause a transition to a new state
![[Pasted image 20230314125406.png]]
- Two special actions - the entry action and the exit action
- The entry event occurs automatically on entry to the state - it is the first thing that happens when the state is entered, and it causes the associated entry action to execute
- The exit event is the very last thing that happens automatically on exit from the state, and it causes the associated exit action to execute
- Activities on the other hand, take a finite amount of time and may be interuppted by the reciept of an event. The keyword do indicates an activity
- Whereas actions always finish because they are atomic, it is possible to interupt an activity before it has finished processing

### Transitions
- [[UML Transition]] syntax for [[Behavioural State Machine]]s
![[Pasted image 20230331145042.png]]
- Every transition has three optional elements
	- Zero or more events - these specify external or internal occurences that can trigger the transition
	- Zero or 1 guard condition - This is a boolean expression that must evaluate to true before the transition can occur. It is placed after the events
	- Zero or more actions - This is a piece of work associated with the transition and occurs when the transition fires
- Transitions can be connected by junction psuedo-states
- These represent points where transitions merge or branch
- They are represented as filled circles that have one or more input transitions and one or more output transitions 
![[Pasted image 20230331145455.png]]
![[Pasted image 20230331145521.png]]

### [[UML Event]]
![[UML Event]]

### Identify and Define the States
- The states of an object can be found by looking at its [[Class Attributes]] and [[Class Relationship]]s with other classes
- Looking at the operations
- For each state determine what events cause transitions to what states, including guard conditions, when needed
- Transitions describe what happens in response to the receipt of an event
- Some state transitions events can be associated with an operation
- Depending on the object's state, the operation may have a different behaviour
- 