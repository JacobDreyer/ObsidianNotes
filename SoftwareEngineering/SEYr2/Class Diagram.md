- Class Diagrams describe the structure of the system in terms of classes and objects
- [[Class]]es are abstractions that specify the attributes and behaviour of a set of objects. [[Objects]] are entities that encapsulate state behaviour
- Naming Convention: Class names start with an uppercase letter, multiple joined; each word starts with a capital letter
- A class can be represented by 4 different ways using [[UML]] Notation
![[Pasted image 20230301102649.png]]

### Steps to Generate
1. Class Identification
2. Identification of attributes and associations
3. Identification of associations between classes
4. Identification of multiplicites
5. identification of roles
6. identification of inheritance

### Class Visibilty
- The access to attributes, operations, and even entire classes can be controlled by applying visibility characteristics
- There are 4 different types of visibility that can be applied to the class and its elements
	- + [[Public Fields]]
	- \# [[Protected Field]]
	- ~ [[Package]]
	- - [[Private Fields]]

### Class Attributes
- A class's attributes are the pieces of information that represent the state of an object
- These attributes can be represented inside the class box, known as inline attributes or by association with another class
- The only mandatory part of the [[UML]] attribute syntax is attribute name
- Naming convention: attributes start with a small letter; capitalize successive words

![[Pasted image 20230301103555.png]]

### [[Multiplicity]]
- Sometimes an attribute will represent more than one object
- Mulitplicity allows you to specify that an attribute actually represents a collection of objects
- Multiplicity can be applied to both inline and attributes by association
![[Pasted image 20230301103808.png]]
- in the above example; each FieldOfficer has a list of emergency reports, and all EmergencyReports are written by exactly one FieldOfficer.
- Also, any Incident should be related to at least one EmergencyReport

- If multiplicity is not explicityly stated it is undecided
	- There is no "default" multiplicity in UML
- It is common UML modelling error to assume an undecided multiplicity defaults to a multiplicity of 1
![[Pasted image 20230301104242.png]]

### Operations:
- A class's operations decide what a class can do but not necessarily how it will do it.
- Operations in [[UML]] are specified on a class diagram with a signature that is a minimum made up of a visibility property, a name, a pair of parentheses, in which any parameters that are needed for the operation to do its job can be supplied, and a return type
![[Pasted image 20230301104528.png]]

### [[Class Relationship]]
![[Class Relationship]]