```ad-note
title: Definition

The number (or range) of possible occurences of an [[Entity Type]] that may relate to a single occurence of an associated entity type through a particular relationship
```

##### Binary
Binary relationships are generally referred to as being:
- one-to-one (1:1): each entity from both sides are associated with at most one entity from the other side (1 instance of Class1 to 1 instance of Class2)
- one-to-many (1:\*): each entity from ClassA is associated with many entities from ClassB, whereas ClassB can be associated with 1 entity from ClassA
- many-to-many (\*:\*): each entity from both classes can be associated with many entities from the other class

### [[Cardinality]] and [[Participation]] Constraints
Multiplicity consists of 2 separate constraints known as cardinality and participation

```ad-note
title: Cardinality

describes the maximum number of possible relationship occurences for an [[Entity Type]] participating in a given [[Relationship Type]]
```

```ad-note
title Participation

Determines whether all or only some [[Entity Type]] occurences participate in a relationship
```

![[Pasted image 20230919144959.png]]
