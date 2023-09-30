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