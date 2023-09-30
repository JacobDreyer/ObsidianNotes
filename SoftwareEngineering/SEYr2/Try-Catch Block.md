## Try-Catch Construct
##### Try-Catch Construct
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

#### Examples:
- [[SE2205-Practice-Exceptions-1]]
- [[SE2205-LabExercise2-Generics]]
