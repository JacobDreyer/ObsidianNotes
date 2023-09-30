---
date-created: 2022-09-14
---
## Generic Type
#### Generic Class
- A generic class can be used to generate a family of classes
```java
public class MyClass <T>{
	private T fir, sec;
	public MyClass(T first, T second){
		fir = first;
		sec = second;
	}
	public void setFirst(T first){
		fir = first
	}
	public T getFirst(){
		return fir;
	}
}

main{
	Integer x = 5, y = 3;
	MyClass <String>cls = new MyClass<String>("Stuff", "More Stuff")
	MyClass <Integer>cls2 = new MyClass<Integer>(x,y);

	cls.setFirst("stuff");
}

// ??  The generic Class is now expecting an String for first and second // because
// <String> was declared ^^^
// same for where ever else T would be used for that class

// For constructors <T> is declared in the Class and <String>
// is declared when creating the class. <T> doesnt go at the start of  // the constructor method ??

//Can be done with others
```

- MyClass is a generic class and the identifier T is a class-reference place-holder which will be filled out by any existing class reference
	- T cannot be replaced by primitive data types (int, char, float) but can be replaced by [[Wrapper Class Reference Types]] (Integer, Double).

#### Generic Method
```java
main{
	MyProj.<Integer>myMethod(myInt, 5); //MyProj is the class name
}


public <T> void myMethod(T o1, int x);
public <T> T myMethod(T o1, int x);
```
- Introduce their own type parameters
	- Similar to declaring a generic type, but the type parameter's scope is limited to the method it was declared

#### Notes
- The main benefit is being able to identify errors at compile time rather than runtime.
- Generics can avoid cumbersome castings
- Generics make programs easier to read
- Note: A generic class is shared by all its instances regardless of its actual generic type

#### Bounded Generic Type
- A generic type that can be specified as a subtype of another type
- Ex
	- \<T Extends Circle> Specifies that T is a generic subtype of Circle class
	- \<? extends T> a bounded (upperbounded) wildcard which specifies T or any subtype of T
	- \<? super T> a lower bounded wild card which specifies T or any super-type of T

#### Restrictions
- Cannot Create an instance of a generic type (new T();)
- Generic array creation is not allowed (new T[100])
- A generic type parameter of a class is not allowed in a static context
- [[Exception Classes]] Cannot be generic

#### Application
##### [[ArrayList]]
- is a generic class with a header: Class ArrayList\<E>
- Similar to an Array
- Automatically expands and shrinks
```java
import java.util.ArrayList;

ArrayList<String> anyNameList = new ArrayList<String>(100);
ArrayList<String> anyNameList = new ArrayList<String>(100);

anyNameList.add("Stuff"); //adds data-item at the end of the array-list
anyNameList.add(1, "Stuff")//adds data at index specified
anyNameList.size(); //returns size of array
anyNameList.get(1); //gets item at location
anyNameList.remove(2); //removes item at location
anyNameList.set(1, "Stuff"); //item at 1 gets overwritten with data
anyNameList.contains("Stuff") //returns true/false if array contains 
							  //data

```
- can't be made for primitive data types
- Must use Integer, Byte, etc
- default length is 10

#### [[Interfaces]]
```java
public interface Pairable <S>{
	public void setPair(S firstItem, S secondItem);
}

public class OrderedPair <T> implements Pairable <T>
```

#### Examples:
- [[SE2205-LabExercise2-Generics]]