```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will use methods to print a header footer and the conversion of cm to * inches **********************************/  
package Q3;  
  
import java.util.Scanner;  
  
public class Task {  
    public static void main(String[] args) {  
        //initialize variables  
		double cm = 0;  
		Scanner inputScan = new Scanner(System.in);  
  
		//call header function inserting name, lab number and question number  
		myHeader("Jacob Dreyer", 3, 3);  
  
		//prompt user for the length in cm and store it in cm variable  
		System.out.println("Enter the length in cm:");  
		cm = inputScan.nextDouble();  
  
		// print the result of the conversion by calling cmToInchConverter
		//method. passing in amount of cm  
		System.out.printf("%.2f cm = %.2f inches", cm,
		  cmToInchConverter(cm));  
  
		// print the footer by calling the footer method.  
		String message = "Signing off - ";  
		myFooter(message);  
	}  
  
    public static void myHeader(String fullName, int labNum, int questionNum)
    {  
        //print the header using given name, lab number and question number  
		System.out.println("*****************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*******************************************");  
 }  
  
    public static void myFooter(String message) {  
        //print the statement given the message  
		System.out.println("\n *** " + message + "Jacob Dreyer ***");  
	}  
  
  
    public static double cmToInchConverter(double cm) {  
        //return the conversion of cm to inches  
		return cm / 2.54;  
	}  
}
```