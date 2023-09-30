- In some situations we need to represent an exceptional behaviour of the [[Use Case]] flow
- The \<\<extend>> relationship is drawn like the \<\<include>> relationship ([[Include Relationship]]), but:
	- The arrow direction is from the supplier use case to the [[base use case]]
	- Labelled by string \<\<extend>>
- An extend relationship indicates that an instance of the base use case may include (under certain circumstances) the behaviour specified by the supplier use case
- The [[Supplier Use Case]] is executed when the extension point is reached and the extending condition is true
- Supplier Use Case is inserted into base use case at named extension point

### Semantics:
- The base use case provides a set of extension points which are hooks where new behaviour may be added
- The supplier use case provides a set of behaviour fragments that can be inserted into the base use case at these hooks
- The base use case does not know anything about the supplier use cases - it just provides hooks for them. In fact, ==the base case is perfectly complete without its extensions==
- The base use case flow is completely independent of the extension points
- Supplier use Cases are generally not complete use cases and therefore can't usually be instantiated by an actor.

### Why use it?
- Factor out optional or exceptional behaviour
	- Executed under certain conditions
	- Simplifies flow of events in the base use case
- 