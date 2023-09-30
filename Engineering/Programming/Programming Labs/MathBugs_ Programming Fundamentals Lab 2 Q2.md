```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-01-31 * In this task the program will print out the RMS of the tens digit and ones digit of an inputed # **********************************/  
package Q2;  
  
import java.util.Scanner;  
  
public class MathBugs {  
    public static void main(String[] args){  
        int num = 0;  
		int tensDigit = 0;  
		int onesDigit = 0;  
		double rms = 0;  
		Scanner inputScan = new Scanner(System.in);  
  
		//requests and then reads the input  
		System.out.println("enter a number between 11 and 99. The number
		  cannot contain zeros");  
		num = inputScan.nextInt();  
  
		//gets tens digit by dividing number by 10 and ignoring the decimals  
		tensDigit = num/10;  
		//gets ones digit by subtracting the tens  
		onesDigit = num-(tensDigit*10);  
  
		//calculates RMS  
		rms = Math.sqrt((tensDigit*tensDigit + onesDigit*onesDigit)/2);  
  
		//prints RMS to 2 decimals  
		System.out.printf("the RMS of the ones digit and tens digit is %.2f"
		  , rms);  
	}  
}
```