```java
package Q4;  
  
public class DriverForAreaAndVolJacob {  
  
    public static void main(String[] args){  
        //store a random radius between 2 and 3  
		double r = Math.random()+2;  
		//store a random height between 4 and 7  
		double h = Math.random()*3 + 4;  
		//create new Geometric3DObject for cone. This can calculate volume
		//and surface area of a cone with radius r and height h  
		Geometric3DObject cone = new RightCircularCone(r, h);  
		//create new Geometric3DObject for cylinder. This can calculate
		//volume and surface area of a cylinder with radius r and height h  
		Geometric3DObject cylinder = new RightCylinder(r, h);  
  
		//print header  
		MyMethod.myHeader("Jacob Dreyer", 8, 4);  
		//print cone info  
		printResult(cone);  
		//go to next line  
		System.out.println(" ");  
		//print cylinder info  
		printResult(cylinder);  
		//print footer  
		MyMethod.myFooter();  
	}  
  
    public static void printResult(Geometric3DObject anyName){  
        //prints the given object's info. Same as calling .toString() method  
		System.out.println(anyName);  
	}  
}
```