```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will perform operations on complex numbers **********************************/  
package Q2;  
  
import java.util.Scanner;  
  
public class ComplexNumberDemoJacob {  
    public static void main(String[] args){  
        //initialize scanner and real and imaginary components of complex
        //numbers x and y  
		Scanner inputScan = new Scanner(System.in);  
		double rex = 0;  
		double imx = 0;  
		double rey = 0;  
		double imy = 0;  
  
		//print header  
		MyHeader("Jacob Dreyer", 5, 2);  
  
		//request real and imaginary values for the first complex number  
		System.out.println("Enter x's real value:");  
		rex = inputScan.nextDouble();  
  
		System.out.println("Enter x's imaginary value;");  
		imx = inputScan.nextDouble();  
  
		//initialize complex number x using given values  
		ComplexNumber x = new ComplexNumber(rex, imx);  
  
		//request real and imaginary values for the second complex number  
		System.out.println("Enter y's real value:");  
		rey = inputScan.nextDouble();  
  
		System.out.println("Enter y's imaginary value;");  
		imy = inputScan.nextDouble();  
  
		//initialize complex number y using given values  
		ComplexNumber y = new ComplexNumber(rey, imy);  
  
		//display the complex numbers in their full form  
		System.out.print("x = ");  
		x.displayRecForm();  
		System.out.print("\n");  
		System.out.print("y = ");  
		y.displayRecForm();  
		System.out.print("\n");  
  
		//initialize 2 more complex number; the sum of x and y, and the
		//product of x and y  
		ComplexNumber addRes = new ComplexNumber(rex+rey, imx+imy);  
		ComplexNumber mulRes = new ComplexNumber((rex * rey) - (imx * imy),
		  (imx * rey) + (rex * imy));  
  
		//display the full form, magnitude, and angle of the new complex 
		//numbers  
		System.out.println("Here are the results of the arithmetic
		  operations");  
		System.out.print("x + y = ");  
		addRes.displayRecForm();  
		System.out.printf(", Magnitude: %.2f, Angle: %.2f degrees \n",
		  addRes.getMagnitude(), addRes.getAngle());  
  
		System.out.print("x * y = ");  
		mulRes.displayRecForm();  
		System.out.printf(", Magnitude: %.2f, Angle: %.2f degrees \n", 
		  mulRes.getMagnitude(), mulRes.getAngle());  
  
		//print footer  
		myFooter();  
	}  
  
    public static void myHeader(String fullName, int labNum, int questionNum)
    {  
        //print the header using given name, lab number and question number  
		System.out.println("***************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*******************************************");  
	}  
  
    public static void myFooter() {  
        //print the statement  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
	}  
}
```