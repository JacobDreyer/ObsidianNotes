```ad-note
title: Definition

Attributes are properties or characteristics of entities and relationships. For an [[Entity Type]], an attribute provides descriptive details about each instance of that entity.
```

### Representation:
Attributes of an entity are listed in the second compartment of the rectangle (first compartment is the [[Entity Type]] name)
![[Drawing 2023-09-18 20.08.49.excalidraw]]

### Types of Attributes
[[Simple Attribute]]s:
- Definition: These are indivisible attributes that cannot be divided any further (studentId)
- Example: A "studentId" attribute that holds a string value
- Representation: write the attribute name inside the attribute compartment

[[Composite Attribute]]:PM
- Definition: These are attributes that can be divided into smaller sub-parts representing more basic attributes with independent meanings
- Example: A "name" attribute might be divided into "firstName" and "lastName"
- Representation: list the name of the composite attribute followed below and indented to the right by the names of its simple component attributes

[[Derived Attribute]]:
- Definition: These are attributes whose values can be derived from other attributes in the database
- Example: an "age" attribute can be derived from a "dateOfBirth" attribute
- Representation: prefix the attribute name with a "/"

[[Single-Valued Attribute]]:
- Definition: Attributes that hold a single value
- Example: "dateOfBirth" attribute
- Representation: write the attribute name with no range

[[Multi-Valued Attribute]]:
- Definition: attributes that can hold multiple values
- Example: A "telephone" attribute for an entity "Student" where a student can have more than one phone number
- Representation: mark the attribute with the range (\[0..\*]) after the attribute name. We can define the maximum and minimum allowed number of values

[[Candidate Key]]:
- Definition: a candidate key is an attribute or a set of attributes that can uniquely identify a [[tuple]] (record) in a [[relation]] (table)
- Example: in a table "studentId" and "studentNo" attributes can be a candidate key
- Representation: write the attribute name

[[Primary Key]]: 
- Definition: Among the [[Candidate Key]]s, one is chosen to be the main key for the relation, known as the primary key. This key is used to uniquely identify each record in the table
- Example: "studentNo" is selected to be a primary key
- Representation: write the attribute name followed by "{PK}"

### Attributes on Relationships
```ad-note
title: Definition

Attributes of a [[Relationship Type]] refer to the properties or characteristics that provide additional information about the association between [[Entity Type]]s in an [[Entity Relationship Diagrams]]. These attributes are not directly linked to the participating entities but rather to the relationship itself
```
##### Representation
- Attributes associated with a [[Relationship Type]] uses the same symbol as an [[Entity Type]]
- To distinguish between a relationship with an attribute and an entity, the rectangle representing the attribute(s) is associated with the relationship using a dashed line
- The rectangle first compartment is empty (no title)
![[Pasted image 20230919140101.png|500]]



