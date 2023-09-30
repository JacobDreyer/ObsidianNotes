```ad-note
title: Definition

a graphical representation of the logical structure of a [[Database]]. It illustrates the relationships between entities (such as tables or onjects), capturing their attributes and the ways they interact with each other. The primary purpose of an [[ER Diagram]] is to offer a visual tool for designing and understanding database structures, ensuring data integrity, and consistency in complex system
```

```ad-danger
title: Problems

problems may arise when designing a conceptual data model called [[Connection Trap]]s.

Connection traps normally occur due to a misinterpretation of the meaning of certain relationships.

Two Types of Connection traps:
- [[Fan Trap]]
- [[Chasm Trap]]
```
### [[Fan Trap]]
![[Fan Trap]]
### [[Chasm Trap]]
![[Chasm Trap]]
#### [[Entity Type]]
![[Entity Type]]

### [[Relationship Type]]
![[Relationship Type]]

- An entity relationship shows the relationships between tables
![[Pasted image 20230314204209.png]]
- Primary keys are denoted with (PK)
- Lines drawn between tables show how they are related, the ends of each line show either a 1 or an $\infty$, the infinity symbol means many and 1 means 1
- A one to many relationship means that for each row in table A there can be many rows in table B that reference it. A many to one relationship means that many rows in A can reference a single row in B
