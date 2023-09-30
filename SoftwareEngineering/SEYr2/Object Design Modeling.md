### Three Types of Objects:
- [[Entity Objects]]
	- Represent the persistent information used by the system (also called "[[Buisness Objects]]")
- [[Boundary Objects]]
	- Represent the interaction between the user and the system
- [[Control Objects]]
	- Represent the control tasks performed by the system

- Having three types of objects leads to models that are more resilient to change
	- The interface of a system changes more likely than the control
	- The way the system is controlled changes more likely than entities in the application domain
- The most common software architecture: Model, View, Controller (MVC)

Model <-> [[Entity Objects]]
View <-> [[Boundary Objects]]
Controller <-> [[Control Objects]]

Steps during Object Modeling:
1. Class Identification
2. Find the Attributes
3. Find the Methods
4. Find the Associations between classes

Order of Steps:
- Goal: get the desired model
- Order of steps is secondary, only a heuristic

### Class Identification
Approaches:
- Application Domain Approach
	- Ask Application Domain experts to find relevant models
- Syntactic Approach
	- Start with [[Use Case]]s
	- Analyze the text to identify objects
	- Extract participating objects from flow of events
- Design Patterns Approach
	- Use reusable design patterns

### Finding Participating Objects in [[Use Case]]s
- Pick a use case and look at flow of events
- Do a textual analysis (noun-verb analysis)
	- [[Noun]]s are candidates for objects/classes
	- [[Verb]]s are candidates for operations
	- This is also called [[Abbott's Technique]]
- [[Abbott's Technique]] can be used to:
	- Identify [[Entity Objects]]
	- Identify [[Control Objects]]
	- Identify [[Boundary Objects]]

#### Filtering the Candidate Classes List
- [[Abbott's Technique]] may result in many more [[noun]]s than relevant classes
	- Many [[Noun]]s correspond to attributes or synonyms for other nouns
	- Sorting through all the nouns for a large requirements spcification is a time-consuming activity
- The following heuristics can be used in conjunction with [[Abbott's Technique]] to determine whether the identified noun is a candidate class ot not:
	- Is it a container for data?
	- Does it have seperate attributes that will take on different values?
	- Would it have many instance objects?
	- Is it in scop of the application domain?

### [[Entity Objects]]
![[Entity Objects]]

### [[Boundary Objects]]
![[Boundary Objects]]

### [[Control Objects]]
![[Control Objects]]
