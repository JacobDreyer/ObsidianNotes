## Declaring Exceptions
- every [[Method]] must state the types of checked (it is optional for [[Unchecked Exception]]s) exceptions it might throw. This is known as declaring exceptions
- if a method does not declare an exception in the superclass we cannot override it to declare exception in the subclass

```java
method(){
	try{
		invoke myMethod;
	} catch (Exception ex){
		//process exception
	}
}
```
```java
public void myMethod() throws IOException, Exception1{
	if (an error occurs){
		throw new Exception();
	}
}
```
