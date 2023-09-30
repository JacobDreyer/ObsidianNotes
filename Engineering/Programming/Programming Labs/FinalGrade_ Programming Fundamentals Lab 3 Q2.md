```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * The program will print out the final grade of 3 grades and grade weights **********************************/  
package Q2;  
  
import java.util.Scanner;  
  
public class FinalGrade {  
    public static void main(String[] args){  
  
        //initalize the variables  
		double grade1 = 0;  
		double grade2 = 0;  
		double grade3 = 0;  
		double gradeWeight1 = 0;  
		double gradeWeight2 = 0;  
		double gradeWeight3 = 0;  
		double finalGrade = 0;  
		Scanner inputScan = new Scanner(System.in);  
  
		//print the header  
		System.out.println("**********************************************");  
		System.out.println("Jacob Dreyer");  
		System.out.println("251241714");  
		System.out.println("2022-02-07");  
		System.out.println("This program will receive three grades and 
		  their weight and calculate the final grade");  
		System.out.println("********************************************");  
  
		//prompt the user for each grade and grade weight  
		System.out.println("Input the First Grade:");  
		grade1 = inputScan.nextFloat();  
  
		System.out.println("Input the First-grade Weight:");  
		gradeWeight1 = inputScan.nextFloat();  
  
		System.out.println("Input the Second Grade:");  
		grade2 = inputScan.nextFloat();  
  
		System.out.println("Input the Second-grade Weight:");  
		gradeWeight2 = inputScan.nextFloat();  
  
		System.out.println("Input the Third Grade:");  
		grade3 = inputScan.nextFloat();  
  
		System.out.println("Input the Third-grade Weight:");  
		gradeWeight3 = inputScan.nextFloat();  
  
		//Calculate the final grade  
		finalGrade = grade1 * gradeWeight1 + grade2 * gradeWeight2 + 
		  grade3 * gradeWeight3;  
  
		//print the final grade  
		System.out.printf("The course Grade is: %.2f", finalGrade);  
	}  
}
```