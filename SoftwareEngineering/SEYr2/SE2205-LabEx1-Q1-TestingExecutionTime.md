```java
package Q1L1;  
import java.util.Scanner;  
  
public class TestingExecutionTime {  
  
    static int j = 1;  
    static int recResult = 1;  
  
    public static void main(String[] args){  
        myHeader(1);  
        Scanner inputScan = new Scanner(System.in);  
        int num = -1;  
        double startTime = 0;  
        double time = 0;  
  
  
        do {  
            System.out.println("Enter an Integer to calculate the 
             Factorial of:");  
            num = inputScan.nextInt();  
        } while(num <= 0);  
  
  
        /**********************************************/  
        startTime = System.nanoTime();  
  
        int result = 1;  
  
        if(num == 0) {  
            result = 0;  
        }  
  
        for(int i=2; i<=num; i++){  
            result *= i;  
        }  
  
        time = System.nanoTime() - startTime;  
        System.out.println("Time: " + time + "       Result: " + 
         result);  
        /*******************************************/  
  
  
        startTime = System.nanoTime();  
        result = iterativeMethod(num);  
        time = System.nanoTime()-startTime;  
        System.out.println("Time: " + time + "       Result: " + 
         result);  
  
        startTime = System.nanoTime();  
        result = recursiveMethod(num);  
        time = System.nanoTime()-startTime;  
        System.out.println("Time: " + time + "       Result: " + 
         result);  
  
        myFooter(1);  
    }  
  
    public static void myHeader(int labNum){  
        System.out.println("Lab Exercise " + labNum);  
        System.out.println("Prepared By: Jacob Dreyer");  
        //System.out.println("Student Number: 251241714");  
        System.out.println("Goal of this Exercise: test execution 
         times of calculating factorials");  
    }  
  
    public static void myFooter(int labNum){  
        System.out.println("Completion of Lab Exercise " + labNum + 
         " is Successfull");  
        System.out.println("Signing off - Jacob");  
    }  
  
    public static int iterativeMethod(int facNum){  
        int result = 1;  
  
        if(facNum == 0) {  
            result = 0;  
            return result;  
        }  
  
        for(int i=2; i<=facNum; i++){  
            result *= i;  
        }  
  
        return result;  
    }  
  
    public static int recursiveMethod(int facNum){  
  
        j++;  
        recResult *= j;  
  
        if(j < facNum){  
            recursiveMethod(facNum);  
        }  
  
        return recResult;  
    }  
}
```

##### Uses:
- [[Recursion]]
- 