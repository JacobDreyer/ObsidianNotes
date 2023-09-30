### Naming:
![[Pasted image 20230308124141.png]]

### Indentifying Control Objects
- Control Objects are responsible for collecting information from the [[Boundary Objects]] and dispatching it to [[Entity Objects]]
- Control Objects typically do not have a concrete counterpart in the real world
- Typically a control object is created at the beginning of a [[Use Case]] and is diminished at the end
- Heuristics for identifying control objects
	- Identify one control object per [[Use Case]]
	- identify one control object per [[Actor]] in the use case
	- The lifespan of a control object should cover the life of all use case events
	- If it is difficult to identify the beginning and end of a control object activation, the corresponding use case probably does not have well-defined entry and exit conditions
