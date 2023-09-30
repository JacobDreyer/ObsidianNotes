```ad-note
title: Definition

A relationship type is a formal descriptor of an association between two or more [[Entity Type]]s, denoting a set of possible connections or interactions among their respective instances. Relationship types have [[Cardinality]], which specifies the numeric constraints of the association
```

### Representation
- Relationship types between two entities are depicted as a line connecting them. When relating 2 or more entities, a diamond is used, with lines connecting the diamond to each involved entity
- Normally, a relationship is named using a verb (ex. Supervises, or Manages) or a short phrase including a verb (for example, LeasedBy)
- Again, the first letter of each word in the relationship name is shown in uppercase
- A relationship is only labeled in one direction, which normally means that the name of the relationship only makes sense in one direction
- An arrow symbol is placed beside the name indicating the correct direction for a reader to interpret the relationship name

### [[Degree of Relationship Type]]
![[Degree of Relationship Type]]

### Role Names
Relationships may be given role names to indicate the purpose that each participating [[Entity Type]] plays in a relationship

Role names may also be used when 2 entities are associated through more than one relationship

### [[Attribute]]
![[Attribute#Attributes on Relationships]]

### Structural Constraints
- Constraints represent restrictions in the real world
- Constraints represent policies (called business rules) established by the user or company
- Main type of constraint on relationships is called [[Multiplicity]]
##### [[Multiplicity]]
![[Multiplicity]]

