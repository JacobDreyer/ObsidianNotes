```java
package Q3;  
  
public class PolarComplexNum {  
    //intialize magnitude and angle variables  
	private double magnitude = 0;  
	private double angle = 0;  
  
	public PolarComplexNum(){  
        //if nothing is entered. set amgnitude and angle to 0  
		angle = 0;  
		magnitude = 0;  
	}  
  
    public PolarComplexNum(double mag, double ang){  
        //set angle to received angle (has to be converted to radians)  
		//set magnitude to entered magnitude angle = Math.toRadians(ang);  
		magnitude = mag;  
	}  
  
    public double getRealValue(){  
        return MyMethod.myCos(angle)*magnitude;  
	}  
  
    public double getImaginaryValue(){  
        return MyMethod.mySin(angle)*magnitude;  
	}  
}
```