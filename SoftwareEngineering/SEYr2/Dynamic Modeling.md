```ad-tldr
title: Definition

Describes the components of the system that have interesting dynamic behaviour
```

- The dynamic model is described with:
	- [[State Diagrams]]: One state diagram for each class with interesting dynamic behaviour
		- Classes without interesting dynamic behaviour are not modeled with state diagrams
	- [[Sequence Diagram]]: For interaction between classes
- Purpose:
	- Detect and supply operations for the [[Object Model]]
		- How? - from the flow of events we proceed to the [[Sequence Diagram]] to find the operations for the object model

### What is an Event?
- Something that happens at a point in time
- An event sends information from one object to another
- Events can have associations with each other:
	- Casually Related:
		- An event happens always before another event
		- An event always happens after another event
	- Casually unrelated:
		- Events that happen concurrently

### Heuristic for finding Participating Objects in [[Sequence Diagram]]s
- An event always has a sender and receiver
- This representation of the event is sometimes called a message
- Find them for each event => these are the object participating in the sequence diagram

