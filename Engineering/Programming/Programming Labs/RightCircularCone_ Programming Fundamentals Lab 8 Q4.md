```java
package Q4;  
  
public class RightCircularCone extends Geometric3DObject implements 
  VolumeOf3DObjectsInterface {  
  
  
    public RightCircularCone(){  
  
    }  
  
    public RightCircularCone(double r, double h){  
        super(r, h);  
	}  
  
    public double getArea(){  
        return PI * getR() * (getR()+Math.sqrt( Math.pow(getR(), 2) +
          Math.pow(getH(), 2) ));  
	}  
  
    public double getVolume(){  
        return (PI * Math.pow(getR(),2) * getH())/3;  
	}  
  
    public String toString(){  
        return super.toString() + String.format("\nCone's Volume: %.2f cubic
          cm \nCone's Surface Area: %.2f sq. cm", getVolume(), getArea());  
	}  
}
```