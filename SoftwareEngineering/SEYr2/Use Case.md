- A Use Case is something an [[Actor]] wants the system to do
- It is a "case of use" of the system by a specific actor
- In other word, a use case describes a function provided by the system (the behaviour) that yields a visible result for the actors
- As naming conventions we will use [[Verb Phrases]] for the use case titles
	- Ex "ReportEmergency"

### Identifying the Use Cases
- What functions will a specific [[Actor]] want from the system?
- Does the system store and retreive information? if so, which actors trigger this behaviour
- Are any actors notified when the system changes state
- Are there any external events that affect the system? What notifies the system about those events

### Use Case Descriptions
- To describe a use case, we use a template composed of six fields:
	- The name of the use case (unique across the system)
	- [[Participating actor]]s are [[Actor]]s interacting with the use case
	- [[Entry Condition]]s (or [[Precondition]]s) describe the conditions that need to be satisfied before the use case is initiated
	- The flow of events describes the sequence of actions of the use case
	- [[Exit Condition]]s ([[Postcondition]]s) describe the conditions that are satisfied after the completion of the use case
	- [[Quality Requirement]]s are not related to the functionality of the system 

### The \<\<Include>> Relationship
- Two use cases are related by an [[Include Relationship]] if one of them (the base) includes the second one (the supplier) in its flow of events
- In [[Use Case Diagram]]s, include relationships are depicted by a dashed open arrow originating from the base use case, and are labelled with the string \<\<include>>
- the syntax for include is a bit like a function call

##### Semantics:
- The base use case executes until the point of inclusion is reached then, execution passes over to the supplier use case
- When the supplier finishes, control returns to the base again
- The base use case is not complete without all of its supplier use cases
- The supplier use cases form integral parts of the base use case. However, the supplier use cases may or may not be complete
- If a supplier use case is not complete then it just contains a partial flow of events that will only make sense when it is included into a suitable base
	- in this case we call it " a [[behaviour fragment]]" and it can't be trggered directly by [[Actor]]s
- If the supplier use cases are complete themselves, then they act just like normal [[Use Case]]s

##### Why Use it?
- Factor out behaviour common to two or more use cases
	- avoid describing same behaviour multiple times.
	- Assure common behaviour remains consistent
- Factor out an encapsulate behaviour from a base use casee
	- simplify complex flows of events
	- Factor out behaviour not part of primary purpose

### The \<\<extend>> Relationship
![[Extend Relationship]]