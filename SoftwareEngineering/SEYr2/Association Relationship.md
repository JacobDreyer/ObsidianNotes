Although dependency simply allows one class to use objects from another, association means that a class will actually contain a reference to an object, or Objects, of the other class in the form of an attribute

### [[Association Class]]es
- Sometimes association can have attributes and operations. Such Association is called [[Association class]]
- A common problem in [[Object Oriented]] Modeling is that when you have a many-to-many relationship between classes
- In this situation you can have a property that could belong to one class or another. So where does it belong?
- The answer is that the property is actually a ==property of the association itself==
- [[UML]] allows you to model this situation using an association class as shown:
![[Pasted image 20230303204359.png]]
- Any association can be transformed into a class and simple associations as follows:
![[Pasted image 20230303204616.png]]
