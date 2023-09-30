##### Note Info
Date: 2022/04/04
## Interfaces
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
