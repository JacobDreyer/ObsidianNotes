##### Note Info
Date: 2022/04/04

## Dynamic Binding in [[Polymorphism]]
- is used in [[Inheritance and Polymorphism]] in [[Programming]]
- Step 1:
	- anyName inherits/is an instance of C1
- Step 2:
	- anyName invokes a [[JavaScript Methods]]. To find the method the JVM seaches C1, C2, C3, ... Cn.
	- where C1 is an instance of/inherits C2; C2 is an instance of/inherits C3; etc where Cn is the highest order (object)
- Step 3:
	- Once an implementation is found the search stops and it is executed
