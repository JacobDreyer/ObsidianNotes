##### Note Info
Course: [[Engineering]]
Class: [[Programming]]
Unit: Inheritance and Polymorphism
Date: 2022-03-30
### Inheritance
public class MyFavouriteClass extends MyClass{
	//class definition
}

an "Is a" relationship

Used to create a "derived class" from another class

The derived class inherits all the same methods as the parent class except the constructor allowing you to call it withour having to write the method again.

Typically the derived class is more specific than the parent class by having more defining variables of methods

Can be chained for parent <- child <- grandchild

##### [[Keyword Super]]
super can be used to call methods from the parent class

super() can be called in the derived class' constructor and it calls the parent's constructor. Must be called before anything else is done.

super.myMethod() calls the parents myMethod() rather than the child's

[[Private Fields]] are not availible to the child class (Methods/Variables)

[[Protected Field]] can be accesed by the child class

#### [[Final Modifier]]
final public class Math{
	...
}

final static double PI = 3.14;

something denoted by final cannot be extended or overwritten by subclasses

#### The Derived Class
An object cannot be derived from multiple parent classes

The derived class reference variable ==is also== a parent class reference variable

#### [[Casting]] in the Inheritance Chain 
A parent object can only access its successor's public methods and fields by casting to that specific successor.

MyClass class = new MyFavouriteClass();
((MyFavouriteClass)class).myMethod();

###### [[Instanceof Operator]]
Can be used to check whether an object is an instance of a class

###### [[The equals() Method]]
public boolean equals(Object obj) { 
	return (this == obj); 
}

In the above statement, ==*this*== represents the reference variable of the same class that is calling equals() method, while *obj* represents another reference-variable of the same class

##### [[toString Method]]
- Used in classes to return a formatted string
- Ususally to print relevant info regarding the class
```java
public String toString(){
	return String.format("Here is the relevant class info: %.2f", randomNum);
}
```

#### [[Abstract Classes]]
- A class that may contain one or more [[Abstract Methods]]
- Abstract classes cannot be used to instantiate an object using the "new" operator
- Used to create Derived classes from it
- Constructors cannot be abstract
- In a UML diagram it is shown in *Italics*
- Examples of implementation are located in [[Programming Fundamentals Lab 8]]

```java
public abstract class MyClass {....}
```

[[Abstract Methods]]:
- is a header only with no implementation
- its implementation is provided by derived classes
```java
public abstract return_type myMethod();
```
- In a UML diagram it is shown in *Italics*
- Examples of implementation are located in [[Programming Fundamentals Lab 8]]

#### [[Polymorphism in Programming]]
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

#### [[Interfaces]]
- A program component that contains:
	- public constants
	- public [[Abstract Methods]] headers

```java
public interface AnyValidName{
	public abstract int someMethod();
}
```
- Is NOT a class
- Like an [[Abstract Classes]] you cannot instatiate with it using new
- In most cases a Java interface is used similarily to [[Abstract Classes]]
- any data field should be public, static, and final
- by default an interface is [[Public Fields]] and abstract
- cannot have [[Constructors]]
- cannot have [[JavaScript Methods]] that are a [[Final Modifier]]
- Omitting Modifiers
	- all [[Data Fields]] are [[Public Fields]], [[Final Modifier]]s, and [[Static Fields]]
	- all [[JavaScript Methods]] are [[Public Fields]], and [[Abstract Methods]]
	- For this reason these modifiers can be omitted

- Implementation examples in [[Programming Fundamentals Lab 8]]

[[Implementing an Interface]]
```java
public class MyClass implements SomeInterface

public class MyClass extends Class implements SomeInterface, AnotherInterface
```
- A class can implement more than 1 interface as shown
- Examples of implementation in [[Programming Fundamentals Lab 8]]

[[Extending an Interface]]
- When an interface extends another using [[Inheritance and Polymorphism]]
- Unlinke classes with interfaces you can combine several interfaces into a new Interface
```java
public interface NewInterface extends Interface1, Interface2{
	//description
}
```

##### [[Interfaces]] vs [[Abstract Classes]]
![[Pasted image 20220404144353.png]]
- Use [[Abstract Classes]] when you need a method or [[Private Fields]] that the generated classes will have in common
- A class that extends an Interface is an instance of that [[Interfaces]]

### [[Aggregation]]
- is a "has a" relationship
- Creating an instance of one class as a reference in another class
- In a [[UML Diagram]] it is represented as a line with an open diamond connecting the classes
![[Pasted image 20220404150438.png]]
- Implementation example in [[Programming Fundamentals Lab 8]]

![[Pasted image 20221121190327.png]]
