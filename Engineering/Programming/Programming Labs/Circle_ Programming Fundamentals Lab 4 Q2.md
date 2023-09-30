```java
package Q2;  
  
public class Circle {  
    //initialize variables  
	public double radius;  
  
	public void setRadius(double rad){  
        //set radius to declared radius  
		radius = rad;  
	}  
  
    public double getRadius(){  
        //returns radius  
		return radius;  
	}  
  
    public double getArea(){  
        //calculate and return area using circle's radius  
		double area = 0;  
		area = Math.PI * radius * radius;  
		return area;  
	}  
  
    public double getDiameter(){  
        //calculate and return diameter  
		return radius * 2;  
	}  
  
    public double getCircumference(){  
        //calculate and return circumference  
		return 2 * Math.PI * radius;  
	}  
}
```