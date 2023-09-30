```ad-note
title: Definition

Where a model represents a relationship between [[Entity Type]]s, but the pathway between certain entity occurences is ambiguous
```

##### Cause:
A fan trap may exist where 2 or more 1:\* relationships fan out from the same entity
##### Example:
- Single division operates one or more branches and has one or more staff
- The problem arises when we want to know which members of staff work at a particular branch
##### Fixing the Problem:
- We fix the problem by restructing the original [[Entity Relationship Diagram]] to represent the correct association between these identities
- Ex. Single Division operates one or more branches. 1 branch has 1 or more staff
- 