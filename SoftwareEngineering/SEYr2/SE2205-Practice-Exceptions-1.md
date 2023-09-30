## SE2205-Practice-Exceptions-1
Includes info from:
- [[Exception]]
- [[Exception Handling]]
- [[Throwing Exceptions]]
- [[Finally Clause]]
- [[Try-Catch Block]]

```java
package Practice1;  
  
import java.util.Scanner;  
  
public class Practice1 {  
  
    public static void main(String[] args){  
  
        double result = 0;  
  
        while(result == 0) {  
            double num = acceptNumber();  
  
            try {  
                result = throwExceptionTest(num);  
  
            } catch (IllegalArgumentException ex) {  
                System.out.println(ex.getMessage());  
            } finally {  
                System.out.println("This is a finally statement");  
            }  
        }  
        System.out.println(result);  
    }  
  
    public static double throwExceptionTest(double num) throws 
     IllegalArgumentException{  
        if(num == 0){  
            throw new IllegalArgumentException("Can't divide by 0");  
        } else if(num%2 != 0){  
            throw new IllegalArgumentException("Number must be even. 
             Enter a number divisible by 2");  
        } else {  
           num = 1.0/num;  
           return num;  
        }  
    }  
  
    public static double acceptNumber(){  
        Scanner inputScan = new Scanner(System.in);  
        double num;  
        System.out.println("Enter a number");  
        num = inputScan.nextInt();  
  
        return num;  
    }  
}
```