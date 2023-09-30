##### Note Info
Date: 2022/04/04
## Polymorphism in Programming
- [[Polymorphism]] refers to the ability of an entity to appear in many forms
- In java:
	- The ability of a reference variable to change behavior according to what instance it is holding
- Three forms of Polymorphism
	- [[Method Overriding]]
	- Implement [[Abstract Methods]]
	- Implement [[Interfaces]]
- Examples of implementation in [[Programming Fundamentals Lab 8]]

[[Dynamic Binding in Polymorphism]]
- Step 1:
	- anyName inherits/is an instance of C1
- Step 2:
	- anyName invokes a [[JavaScript Methods]]. To find the method the JVM seaches C1, C2, C3, ... Cn.
	- where C1 is an instance of/inherits C2; C2 is an instance of/inherits C3; etc where Cn is the highest order (object)
- Step 3:
	- Once an implementation is found the search stops and it is executed