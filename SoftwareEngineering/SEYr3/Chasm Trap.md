```ad-note
title: Definition

Where a model suggests the existence of a [[Relationships]] between [[Entity Type]]s, but the pathway does not exist between certain entity occurences
```
##### Cause:
A chasm trap may occur where there are one or more relationships with a minimum [[Multiplicity]] of zero forming part of the pathway between related entites
##### Example:
- A single branch has one or more staff who oversee zero or more properties for rent
- A property can belong to 0 or 1 staff
- A problem arises when we want to know which properties are available at each branch
- (There may be a property with no staff to oversee it and therefore cannot be related back to the branch)
##### Fixing the Problem
- Identify the missing relationship, which in this case is the offers relationship between the branch and PropertyForRent entities
- This connects the property to the branch even though there is no staff to oversee the property