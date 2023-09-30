```java
package Q2;  
  
public class ComplexNumber {  
    //initialize real and imaginary components of the complex number  
	private double real = 0;  
	private double imaginary = 0;  
  
	public ComplexNumber(){  
        //set real and imaginary components of the complex number  
		real = 0;  
		imaginary = 0;  
	}  
  
    public ComplexNumber(double re, double im){  
        //set real and imaginary components of the complex number using
        //inputed values  
		real = re;  
		imaginary = im;  
	}  
  
    public double getMagnitude(){  
        //return magnitude of the complex number  
		return Math.sqrt(Math.pow(real, 2) + Math.pow(imaginary, 2));  
	}  
  
    public double getAngle(){  
        //return angle of the complex number  
		return Math.toDegrees(Math.atan2(imaginary, real));  
	}  
  
    public void displayRecForm(){  
        //display the complex number in its full form  
		if(imaginary < 0){  
            System.out.printf("%.2f - %.2fi", real, imaginary*-1 );  
		} else {  
            System.out.printf("%.2f + %.2fi", real, imaginary );  
		}  
    }  
}
```