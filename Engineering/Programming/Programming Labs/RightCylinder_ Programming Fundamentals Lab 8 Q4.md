```java
package Q4;  
  
public class RightCylinder extends Geometric3DObject implements 
  VolumeOf3DObjectsInterface{  
  
  
    public RightCylinder(){  
  
    }  
  
    public RightCylinder(double r, double h){  
	    super(r, h);  
	}  
  
    public double getArea(){  
        return 2 * PI * getR() * (getR() + getH());  
	}  
  
    public double getVolume(){  
        return (PI * Math.pow(getR(),2) * getH());  
	}  
  
    public String toString(){  
        return super.toString() + String.format("\nCylinder's Volume: %.2f
          cubic cm \nCylinder's Surface Area: %.2f sq. cm", getVolume(),
          getArea());  
	}  
}
```