```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will calculate and print attributes of a circle given radius. Uses a Circle class **********************************/  
package Q2;  
  
import java.util.Scanner;  
  
public class CircleInfoJacob {  
    public static void main(String[] args){  
        //initialize variables  
		int rad = 0;  
		Circle circle1 = new Circle();  
		Scanner inputScan = new Scanner(System.in);  
  
		//call myHeader to print header  
		myHeader("Jacob Dreyer", 4, 2);  
  
		//prompt user for radius  
		System.out.println("Enter the Circle's Radius:");  
		rad = inputScan.nextInt();  
  
		//set Circle c's radius to entered radius  
		circle1.setRadius(rad);  
  
		//print ___ by calling the corresponding circle method (get___) 
		//ex. getRadius prints the radius  
		System.out.printf("The circle's radius is %.3f \n",
		  circle1.getRadius());  
		System.out.printf("The circle's area is %.3f \n", circle1.getArea());  
		System.out.printf("The circle's diameter is %.3f \n",
		  circle1.getDiameter());  
		System.out.printf("The circle's circumference is %.3f \n",
		  circle1.getCircumference());  
  
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
  
    public static void myFooter() {  
        //print the statement given the message  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
	}  
}
```