## The Finally Clause
- the finally clause executes some code regardless of whether an exception occurs or is caught. 
- If a system wants to exit from the catch block using System.exit(0), the finally block will not be executed
```java
try {
	//statements;
}
catch (TheException ex){
	//handling ex;
}
finally {
	//final statements
}
```
