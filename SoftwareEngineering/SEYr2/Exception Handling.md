---
date-created: 2022-09-19
---
## Exception Handling in Java
- involves declaring, throwing, and catching an exception
- Enables a method to throw (generate) an [[Exception Object]] for the caller of the method
- Can be mandatory or optional based on two types of exceptions
	- Checked exception: 
		- compiler makes exception handling mandatory
		- code will not compile if exception is not checked
	- Unchecked Exception:
		- exception-handling is optional
![[Pasted image 20220918220903.png]]
#### Catching Exceptions
##### [[Try-Catch Block]]
```java
try{
	//guardedBody
} catch (exceptionType1 variable1){
	//remedyBody1
} catch (exceptionType2 variable2){
	//remedyBody2
} //etc

try {
	if(num == 0)
		throw new ArithmeticException("Integer Division by zero!");
	result = num1/num;
	break;
} catch (Exception ex){
	System.out.println("Exception: " + ex);
		input.nextLine(); //always cleanup the buffer
}
```
- if guardedBody throws an exception the exception is caught by having the program flow  jump to a predefined catch block that contains code to apply an appropriate resolution
- If no exception occurs all catch blocks are skipped

![[Pasted image 20220922174801.png]]

#### Examples:
- [[SE2205-Practice-Exceptions-1]]
- [[SE2205-LabExercise2-Generics]]

## Python
```python
#file handling
with open('file_path', 'w') as file:
	file.write('Hello World!')
#with handles exceptions in a much cleaner easier way. ordinarilly you would need 
#a try block to handle an exception from file.write and then also close file with #file.close. with handles all of that
```