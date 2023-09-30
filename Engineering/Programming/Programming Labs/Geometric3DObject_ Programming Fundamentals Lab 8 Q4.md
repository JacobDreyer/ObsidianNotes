```java
package Q4;  
  
public abstract class Geometric3DObject {  
    //create variables to store radius, height, PI  
	private double r = 0;  
	private double h = 0;  
	public double PI = Math.PI;  
  
	protected Geometric3DObject(){  
  
    }  
  
    protected Geometric3DObject(double r, double h){  
        //assign radius and height  
		this.r = r;  
		this.h = h;  
	}  
  
    public double getR(){  
        //return radius  
		return r;  
	}  
  
    public double getH(){  
        //return height  
		return h;  
	}  
  
    //create abstract method. Meaning it will just be assigned meaning in
    //derived classes  
	public abstract double getArea();  
  
	public String toString(){  
        //overwrite toString method to write radius and height  
		return String.format("Given: Radius = %.2f cm, Height = %.2f cm", r,
		  h);  
	}  
}
```
