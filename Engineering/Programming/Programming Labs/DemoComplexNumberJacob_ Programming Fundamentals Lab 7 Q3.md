```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-03-21 * In this task the program will perform operations on complex numbers **********************************/  
package Q3;  
  
import java.util.Scanner;  
  
public class DemoComplexNumberJacob {  
  
    public static void main(String[] args){  
        //initialize variables  
		char choice = '0';  
		RecComplexNum x = new RecComplexNum(1, -2);  
		RecComplexNum y = new RecComplexNum(-3, 4);  
		RecComplexNum rcn = new RecComplexNum();  
		Scanner inputScan = new Scanner(System.in);  
  
		//print header  
		MyMethod.myHeader("Jacob Dreyer", 7, 3);  
  
		System.out.println("You have entered the following two complex
		  numbers x and y:");  
  
		//print the default complex numbers  
		System.out.print("x = ");  
		x.displayRec();  
		System.out.printf(", Magnitude: %.2f, Angle: %.2f degrees\n",
		  x.getMagnitude(), x.getAngle());  
		System.out.print("y = ");  
		y.displayRec();  
		System.out.printf(", Magnitude: %.2f, Angle: %.2f degrees\n",
		  y.getMagnitude(), y.getAngle());  
  
		System.out.println("\nComplex Number Calculator:");  
  
		while(true){  
            //get user to choose a function; store it in choice  
			System.out.println("=========================");  
			System.out.println("a: Addition");  
			System.out.println("b: Subtraction");  
			System.out.println("c: Multiplication");  
			System.out.println("d: Division");  
			System.out.println("e: Exit");  
			System.out.println("=========================");  
  
			System.out.println("Enter your choice:");  
			choice = inputScan.next().charAt(0);  
  
			choice = Character.toLowerCase(choice);  
  
			//depending on choice. perform function  
			//if default is called; print "Invalid choice" and repeat
			switch(choice){  
                case 'a':  
                    //case for addition  
					//print addition of the 2 complex numbers 
					rcn = addComplexNumbers(x,y);  
					System.out.print("x + y = ");  
					rcn.displayRec();  
					System.out.printf(", Magnitude: %.2f, Angle: %.2f
					  degrees\n", rcn.getMagnitude(), rcn.getAngle());  
					break;  
				case 'b':  
                    //case for subtracation  
					//print subtraction of the 2 complex numbers 
					rcn = subtractComplexNumbers(x,y);  
					System.out.print("x - y = ");  
					rcn.displayRec();  
					System.out.printf(", Magnitude: %.2f, Angle: %.2f
					  degrees\n", rcn.getMagnitude(), rcn.getAngle());  
					break;  
				case 'c':  
                    //case for multiplication  
					//print multiplication of the 2 complex numbers 
					rcn = multiplyComplexNumbers(x,y);  
					System.out.print("x * y = ");  
					rcn.displayRec();  
					System.out.printf(", Magnitude: %.2f, Angle: %.2f
					  degrees\n", rcn.getMagnitude(), rcn.getAngle());  
					break;  
				case 'd':  
                    //case for Division  
					//print division of the 2 complex numbers 
					rcn = divideComplexNumbers(x,y);  
					System.out.print("x / y = ");  
					rcn.displayRec();  
					System.out.printf(", Magnitude: %.2f, Angle: %.2f
					  degrees\n", rcn.getMagnitude(), rcn.getAngle());  
					break;  
				case 'e':  
                    //case for exiting  
					break;  
  
				default:  
                    //any other choice print "Invalid Choice"  
					System.out.println("Invalid Choice!");  
			}  
  
            //if choice was 'e'; exit loop and therefore end program  
			if(choice == 'e')  
                break;  
  
		}  
  
        MyMethod.myFooter();  
	}  
  
    public static RecComplexNum addComplexNumbers(RecComplexNum x,
      RecComplexNum y){  
        //store addition of 2 complex numbers in rcnSum and return it  
		RecComplexNum rcnSum = new RecComplexNum(x.getReal() + y.getReal(),
		  x.getImaginary() + y.getImaginary());  
		return rcnSum;  
	}  
  
    public static RecComplexNum subtractComplexNumbers(RecComplexNum x,
      RecComplexNum y){  
        //store subtraction of 2 complex numbers in rcnSum and return it  
		RecComplexNum rcnSum = new RecComplexNum(x.getReal() - y.getReal(),
		  x.getImaginary() - y.getImaginary());  
		return rcnSum;  
	}  
  
    public static RecComplexNum divideComplexNumbers(RecComplexNum x,
      RecComplexNum y){  
        //create a PolarComplexNum pcnProduct to store the division of 2
        //complex numbers (makes calculation easy)  
		//create a RecComplexNum rcnProduct based off of pcnProduct
		PolarComplexNum pcnProduct = new PolarComplexNum(x.getMagnitude()/
		  y.getMagnitude(), x.getAngle() - y.getAngle());  
		RecComplexNum rcnProduct = new RecComplexNum(pcnProduct.
		  getRealValue(), pcnProduct.getImaginaryValue());  
		return rcnProduct;  
	}  
  
    public static RecComplexNum multiplyComplexNumbers(RecComplexNum x,
      RecComplexNum y){  
        //create a PolarComplexNum pcnProduct to store the multiplication of
        //2 complex numbers (makes calculation easy)  
		//create a RecComplexNum rcnProduct based off of pcnProduct 
		PolarComplexNum pcnProduct = new PolarComplexNum(x.getMagnitude()*
		  y.getMagnitude(), x.getAngle() + y.getAngle());  
		RecComplexNum rcnProduct = new RecComplexNum(pcnProduct.
		  getRealValue(), pcnProduct.getImaginaryValue());  
		return rcnProduct;  
	}  
}
```