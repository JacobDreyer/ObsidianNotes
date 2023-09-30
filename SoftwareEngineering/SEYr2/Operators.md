## Operators
#### [[Java]]
![[Pasted image 20220908102720.png]]
##### Bitwise Operators
~ : bitwise complement (prefix unary operator) - invert binary #
& : bitwise and - 
|   : bitwise or
^ : bitwise exclusive 
<< : shift bits left, filling in with zeros
. >> : shift bits right, filling in with sign bit
. >>> : shift bits right, filling in with zeros

1 = true
0 = false

##### Example
```java
public class DemoBitwiseOperators { 
	public static void main(String[] args) { 
		int x = 9, y = 10, s = 3; 
		System.out.printf("%d in Binary is: %s\n" , 
         x,Integer.toBinaryString(x)); 
		System.out.printf("%d in Binary is: %s\n" 
         ,y,Integer.toBinaryString(y)); 
		System.out.printf("%d | %d = %d, and in Binary it is: %s\n" 
         ,x,y, x|y,Integer.toBinaryString(x|y)); 
		System.out.printf("%d & %d = %d, and in Binary it is: %s\n" 
         ,x,y, x&y,Integer.toBinaryString(x&y)); 
		System.out.printf("%d ^ %d = %d, and in Binary it is: %s\n" 
         ,x,y, x^y,Integer.toBinaryString(x^y)); 
		System.out.printf("complement of %d in Binary is: %s\n" 
         ,x,Integer.toBinaryString(~x)); 
		System.out.printf("Shifting %d left by %d bits; in Binary is: 
         %s\n" ,x,s,Integer.toBinaryString(x<
```
##### Output
![[Pasted image 20220908103949.png]]

1001
1010

Go to each column:
Or - is one of them true (1)
And - are both true
^ - if the 2 numbers are the same: true ????

if true put a 1 for that column
if false put a 0 for that column