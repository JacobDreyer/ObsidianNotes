```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will print the sums of ints chars and strings **********************************/  
package Q1;  
  
import java.util.Scanner;  
  
public class SumCity {  
    public static void main(String[] args) {  
        //initialize variables  
		Scanner inputScan = new Scanner(System.in);  
		double num1 = 0;  
		double num2 = 0;  
		char char1 = '0';  
		char char2 = '0';  
		String name = "0";  
  
		//call header function to print header  
		myHeader("Jacob Dreyer" ,4, 1);  
  
		//prompt user and recieve 2 integers.  
		System.out.println("Enter a Real Number:");  
		num1 = inputScan.nextFloat();  
  
		System.out.println("Enter a Second Real Number:");  
		num2 = inputScan.nextFloat();  
  
		//print the sum of the integers by calling the sumValues method which
		//returns the sum  
		System.out.printf("The sum of %.2f and %.2f is: %.2f \n", num1, 
		  num2, sumValues(num1, num2));  
  
		//prompt user and recieve 2 characters  
		System.out.println("Enter a Character:");  
		char1 = inputScan.next().charAt(0);  
  
		System.out.println("Enter a Second Character:");  
		char2 = inputScan.next().charAt(0);  
  
		//print the unicode sum of the characters by receiving the returned
		//sumValues casted as int and its resulting character 
		//(original returned value of sum values)  
		System.out.printf("the sum of characters %c and %c is: %c. the
		  integer equivalent is %d \n", char1, char2, sumValues(char1,
		  char2), (int)sumValues(char1, char2));  
  
		//scan next line so the next scans work properly  
		inputScan.nextLine();  
  
		//prompt user and recieve name  
		System.out.println("Enter your Full Name:");  
		name = inputScan.nextLine();  
  
		//print the sum of 2 strings by calling sum values which returns the
		//combined string  
		System.out.printf(sumValues("I am ", name));  
  
		//call footer to print footer  
		myFooter();  
	}  
  
    public static void myHeader(String fullName, int labNum, int questionNum)
    {  
        //print the header using given name, lab number and question number  
		System.out.println("*********************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*********************************************");  
	}  
  
    public static String sumValues(String str1, String str2) {  
        //return sum of strings  
		return str1 + str2;  
	}  
  
    public static double sumValues(double num1, double num2) {  
        //return sum of integers  
		return num1 + num2;  
	}  
  
    public static char sumValues(char char1, char char2) {  
        //cast the received chars as integers, add the resulting unicode
        //values. Store in variable  
		int newCharIndex = ((int) char1 + (int) char2);  
		//return the character corresponding to the resultant unicode value  
		return (char)newCharIndex;  
	}  
  
    public static void myFooter() {  
        //print the statement given the message  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
  
	}  
}
```