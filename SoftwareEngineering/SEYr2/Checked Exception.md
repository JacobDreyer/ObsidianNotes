## Checked Exception
- java forces the programmer to deal with checked exceptions
- if a method declares checked exception one must follow one of the following methods:
	- in the calling method declare (throws) the exception to throw
	- invoke the exception in a try-catch block
```java
public static void main(String[] args) throws Exception {
	PrintWriter output = new PrintWriter(file);
}

public static void main(String[] args) {
	try {
		output = new java.io.PrintWriter(file);
	}
	catch (FileNotFoundException e){
		//define it or leave it empty
	}
}
```