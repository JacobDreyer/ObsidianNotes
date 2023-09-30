- [[Composition]] is a stronger form of [[Aggregation]] and has similar (but more constrained) semantics
- Like Aggregation, it is a [[whole-part relationship]] and is both [[Transitive]] and [[Asymmetric]]
- The Key difference between aggregation and composition is that in composition the parts have no independent life outside of the whole
- Furthermore, in composition each part belongs to one and only one whole
![[Pasted image 20230303205805.png]]

### Semantics:
- The parts belong to exactly one whole at a time
- The whole has sole responsibilty for the creation and destruction of all its parts
- If the whole is destroyed, it must either destroy all its parts, or give responsibilty for them over to some other object
- When the whole is created, all its parts should be created as well

