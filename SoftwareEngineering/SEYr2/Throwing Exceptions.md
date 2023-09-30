## Throwing Exceptions
- When the program detects an error, the program creates an instance of an appropirate exception Class type and throws it. This is known as throwing an exception
```java
throw new Exception();
throw new Exception("appropriate string argument");

// or we can use the following:

Exception ex = new Exception();
Exception ex = new Exception("appropriate string argument");

throw ex;
```

#### The throws clause
- When a method is declared, it is possible to explicitly declare, as part of its signature, the possibility that a paticular exception type may be thrown during a call to that method
- The syntax for declaring possible exceptions in a method signature relies on the keyword throws (not throw)
- To create a checked custom exception it must extend Exception or its child classes
- Note: all exceptions are children of Throwable
```java
public void setRadius (double newRadius) throws IllegalArgumentException {
	if(newRadius >=0){
		radius = newRadius;
	} else {
		throw new IllegalArgumentException("Radius cannot be negative");
	}
}
```

#### Examples:
- [[SE2205-Practice-Exceptions-1]]
- [[SE2205-LabExercise2-Generics]]