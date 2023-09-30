```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will calculate the volue of a cone given radius and height **********************************/  
package Q1;  
  
import java.util.Scanner;  
  
public class ConeVolume {  
    public static void main(String[] args){  
        // create variables for radius height and volume  
		double radius = 0;  
		double height = 0;  
		double volume = 0;  
		Scanner inputScan = new Scanner(System.in);  
  
		//print the header  
		System.out.println("********************************************");  
		System.out.println("Jacob Dreyer");  
		System.out.println("251241714");  
		System.out.println("2022-02-07");  
		System.out.println("This program will receive the height and radius
		  of a cone and print the volume");  
		System.out.println("******************************************");  
  
		//prompt the user to input values for height and radius  
		System.out.println("Please enter the height of the cone:");  
		height = inputScan.nextDouble();  
  
		System.out.println("Please enter the radius of the cone:");  
		radius = inputScan.nextFloat();  
  
		//Calculate the volume  
		volume = (Math.PI * radius * radius * height)/3;  
  
		//Print the volume radius and height  
		System.out.printf("The volume of a cone with radius %.2f and
		  height %.2f is: %.2f", radius, height, volume);  
	}  
}
```