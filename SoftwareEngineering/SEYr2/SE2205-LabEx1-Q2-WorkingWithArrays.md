```java
package Q2L2;  
  
  
import java.util.Scanner;  
  
public class WorkingWithArrays {  
    public static void main(String[] args){  
        int[] arr;  
  
        Scanner inputScan = new Scanner(System.in);  
        myHeader(1);  
  
        System.out.println("Enter the size of the Array");  
        arr = new int[inputScan.nextInt()];  
  
        for(int i=0;i<arr.length; i++){  
            arr[i] = (int)((Math.random()*51)-25);  
        }  
  
  
        double[] doubArr = mma5MethodJacob(arr);  
  
        System.out.println("Max: " + doubArr[0]);  
        System.out.println("Min: " + doubArr[1]);  
        System.out.println("Avg: " + doubArr[2]);  
        System.out.println("Student Number: " + (int)doubArr[3]);  
  
        myFooter(1);  
    }  
  
    public static double[] mma5MethodJacob(int[] intArr){  
        int counter = 0;  
        int max = 0;  
        int min = 0;  
        double avg = 0;  
        int numDiv5 = 0;  
  
        for(int i=0; i< intArr.length; i++){  
            int temp = intArr[i];  
            if(temp%5 == 0){  
                numDiv5++;  
                avg += temp;  
                if(counter == 0){  
                    counter++;  
                    max = temp;  
                    min = temp;  
                }  
  
                max = Math.max(max, temp);  
                min = Math.min(min, temp);  
            }  
        }  
  
        System.out.println("Jacob found " + numDiv5 + " numbers that 
         are divisible by 5");  
  
        if(numDiv5 == 0)  
            numDiv5 = 1;  
  
        double[] doubArr = new double[4];  
        doubArr[0] = max;  
        doubArr[1] = min;  
        doubArr[2] = (avg/numDiv5);  
        doubArr[3] = 251241714;  
  
        return doubArr;  
    }  
  
    public static void myHeader(int labNum){  
        System.out.println("Lab Exercise " + labNum);  
        System.out.println("Prepared By: Jacob Dreyer");  
        System.out.println("Student Number: 251241714");  
        System.out.println("Goal of this Exercise: test execution 
         times of calculating factorials");  
    }  
  
    public static void myFooter(int labNum){  
        System.out.println("Completion of Lab Exercise " + labNum + 
         " is Successfull");  
        System.out.println("Signing off - Jacob");  
    }  
}
```

##### Uses:
- [[Print Statements]]
- [[Arrays]]
- [[Scanner]]
- [[Loops]]