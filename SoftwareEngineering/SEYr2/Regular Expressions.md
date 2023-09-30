- a String that describes a pattern for matching a set of Strings
- Powerful for string manipulations
- Can be used for matching, replacing, and splitting strings
```java
System.out.println("Java".matches("java")); //prints false
System.out.println("java".equals("java")); //prints true
System.out.println("Java is fun".matches("Java.*")); //prints true
```
![[Pasted image 20221018110924.png]]

### Replacing and Splitting Strings
```java
String s1 = "Java Java Java".replaceAll("v\\w", "wi") ; System.out.println(s1); //prints Jawi Jawi Jawi 
System.out.println("Java Java Java".replaceFirst("v\\w", "wi")); 
//prints Jawi Java Java
```
