- [[Use Case]]s show what your system should do
- Activity Diagrams allow you to specify how your system will accomplish its goals
- Activity diagrams is used for modeling buisness processes, in which several objects participate
- Activity diagrams are "OO Flow Charts"

### Essentials:
- The activity is launched by the initial node, which is drawn as a filled circle
- At the other end of the diagram, the activity final node, drawn as two concentric circles with a filled inner circle, marks the end of the activity
- In between the initial node and the activity final node are actions, which are drawn as rounded rectangles
- The flow of the activity is shown using arrowed lines called edges or paths
- The diamond-shaped node is called a decision, analogous to an if-else statement
![[Pasted image 20230313165209.png]]

### Activites and Actions
- Actions are active steps in the completion of a process.
- The word "activity" is often mistakenly used instead of "action" to describe a step in an activity diagram, but they are not the same
	- An activity is the process being modeled. An action is a step in the over all activity
![[Pasted image 20230313165646.png]]

### Decisions and Merges
- Decisions are when you want to execute a different sequence of actions depending on a condition
- Decisions are drawn as diamond-shaped nodes with one incoming edge and multiple outgoing edges
![[Pasted image 20230313165824.png]]
- Each branched edge contains a guard condition written in brackets. Guard decisions determine which edge is taken after a decision node.

### Doing Multiple Tasks at the Same Time
- We represent parallel actions in activity diagrams by using forks and joins.
![[Pasted image 20230313170733.png]]
- The join means that all incoming actions must finish before the flow can proceed past the join

### Time Events
- Sometimes, Time is a factor in your activity. You may want to model a wait period, such as waiting three days after shipping an order to send a bill. You may also need to model processes that kick off at a regular time interval, such as a system backup that happens every week
- Time events are drawn with an hourglass symbol
![[Pasted image 20230313171024.png]]
- A time event with no incoming flows is a recurring time event, meaning its activated with the frequency in the text next to the hourglass
![[Pasted image 20230313171121.png]]

### Subactivity
- Sub activities hide the complexity of a model
![[Pasted image 20230313171227.png]]

### Objects and Pins
- Object Nodes
	- To represent objects and data as they flow in and out of invoked behaviours
	- An object node is drawn with a rectangle,
![[Pasted image 20230313171339.png]]
- Pin
	- Pin: Abbreviated notation for an Object node. Object and pIn notations define object flow in an activity
![[Pasted image 20230313171448.png]]

### Sending and Receiving Signals
- ACtivities may involve interactions with external people, systems, or processes
- In activity diagrams, signals represent interactions with external participants. Signals are messages that can be sent or received
![[Pasted image 20230314123354.png]]
- When you see a receive signal node with no incoming flows, it means that the node is always waiting for a signal when its containing activity is active

### Starting Activities and Flows
- The simplest and most common way to start an activity is with a single initial node
- There are other ways to represent the start of an activity that have special meaningins:
	- The activity starts by receiving input data (using object node)
![[Pasted image 20230314123701.png]]
		- The activity starts in response to a time event
![[Pasted image 20230314123804.png]]
		- The Activity starts as a result of being woken up by a signal
![[Pasted image 20230314123844.png]]

### Ending Activities and Flows
The Activity final node stops all flows within an activity. An activity diagram may have many activity final nodes, the first one to be activated terminate all other flows and the activity itself

The flow final node simply stops one of the flows within the activity, the other flows continue.

![[Pasted image 20230314124048.png]]

