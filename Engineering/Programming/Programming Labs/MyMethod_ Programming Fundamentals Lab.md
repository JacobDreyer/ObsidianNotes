```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will allow the user to choose a math function and pass in variables to calculate **********************************/  
package Q4;  
  
//Import Scanner  
  
public class MyMethod {  
  
  
   public static void myHeader(String fullName, int labNum, int questionNum){  
	    //print the header using given name, lab number and question number  
	    System.out.println("*********************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*********************************************");  
	}  
  
    public static void myFooter() {  
        //print the statement  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
	}  
  
    public static double myPow(double x, int y){  
        //x is number, y is the power  
		//initialize result with 1 double result = 1;  
		if(y<0){  
            //if power is negative flip x and make y positive (this is
            //equivalent to a num to a negative power)  
			x = 1/x;  
			y *= -1;  
		}  
        for(int i=0; i<y; i++){  
            //x gets multiplied by itself y times where y is the power  
			result = result*x;  
		}  
  
        //return the result  
		return result;  
	}  
  
    public static double myFactorial(int n){  
        //initialize result with n  
		double result = 1;  
		for(int i=1; i<= n; i++){  
            //start at one and multiply by i to result increasing by 1 up to
            //number of factorial  
			result = result*i;  
		}  
        //return result  
		return result;  
	}  
  
    public static double mySin(double x){  
        double result = 0;  
		for(int n=0; n<=20; n++){  
            //calculation for sin  
			result = result + ( myPow(-1,n) * myPow(x, (2*n)+1) /
			myFactorial((2*n)+1) );  
		}  
        //return result  
		return result;  
	}  
  
    public static double myCos(double x){  
        double result = 0;  
		for(int n=0; n<=20; n++){  
            //calculation for cos  
			result = result + ( myPow(-1,n) * myPow(x, 2*n) /
			myFactorial(2*n));  
		}  
        //return result  
		return result;  
	}  
  
    public static double myDegreeToRadian(double degree){  
        //calculate and return angle(in degrees) given to radians  
		return degree*Math.PI/180;  
	}  
}
```