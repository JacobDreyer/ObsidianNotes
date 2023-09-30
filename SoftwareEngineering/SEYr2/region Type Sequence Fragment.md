### Parameters
None

### Why is it Useful?
Interactions within this type of fragment are said to be part of a critical region. A critical region is typically an area where a shared participant is updated. Combined with parallel interactions, specified using the [[par Type Sequence Fragment]], you can model where interactions are not reuired to be thread or process safe and where locks are required to prevent parallel interactions interleaving ([[region Type Sequence Fragment]]). Has similarities to synchronized blocks and object locks in [[Java]]

