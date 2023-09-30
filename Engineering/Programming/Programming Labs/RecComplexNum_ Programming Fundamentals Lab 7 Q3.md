```java
package Q3;  
  
public class RecComplexNum {  
    //intialize real and imaginary components of real number  
	private double real = 0;  
	private double imaginary = 0;  
  
	public RecComplexNum(){  
        //if no values are received; real and imaginary = 0  
		real = 0;  
		imaginary = 0;  
	}  
  
    public RecComplexNum(double re, double im){  
        //if values are received; real and imaginary are set with the values  
		real = re;  
		imaginary = im;  
	}  
  
    public double getReal(){  
        return real;  
	}  
  
    public double getImaginary(){  
        return imaginary;  
	}  
  
    public double getMagnitude(){  
        //calculate and return magnitude  
		return Math.sqrt(MyMethod.myPow(real,2) + MyMethod.myPow(imaginary,
		  2));  
	}  
  
    public double getAngle(){  
        //calculate and return angle  
		return Math.toDegrees(Math.atan2(imaginary, real));  
	}  
  
    public void displayRec(){  
        //print rec form of Complex number  
		if(imaginary > 0){  
            System.out.printf("%.2f + %.2fi", real, imaginary);  
		} else{  
            System.out.printf("%.2f - %.2fi", real, imaginary*-1);  
		}  
	}  
}
```
