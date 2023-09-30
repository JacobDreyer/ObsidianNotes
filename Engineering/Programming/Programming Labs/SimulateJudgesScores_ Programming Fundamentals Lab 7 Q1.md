```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-03-21 * In this task the program will perform operations on arrays of judge's scoring **********************************/  
package Q1;  
  
public class SimulateJudgesScore {  
    public static void main(String[] args){  
        //create array with length of 5  
		double[] anyName = new double[5];  
  
		//print header  
		MyMethod.myHeader("Jacob Dreyer", 7,1);  
  
		//populate and display anyName array  
		populateArray(anyName);  
		displayArray(anyName);  
		//print average of final score  
		//final score is anyName array replacing max and min values with 0
		System.out.printf("     The final score is: %.2f",
		  finalScore(anyName));  
	}  
  
    public static void populateArray(double[] anyName){  
        //go through each element of array  
		for(int i=0; i<anyName.length;i++){  
            //asssign spot with random number between 7 and 10  
			anyName[i] = Math.random()*3 + 7;  
		}  
    }  
  
    public static void displayArray(double[] anyName){  
        //print statement  
		System.out.println("Here are the scores from 5 judges");  
		System.out.print("[");  
		//go through each element of array  
		for(int i=0; i<anyName.length; i++){  
            //print element  
			System.out.printf("%.2f, ", anyName[i]);  
		}  
        //print ending bracket minus space and comma of last value  
		System.out.println("\b\b]");  
	}  
  
    public static double finalScore(double[] anyName){  
        //create array for finalScore  
		double[] finalScore = new double[anyName.length];  
		//create variables to store location of max and min values  
		int maxPos = 0;  
		int minPos = 0;  
  
		//copy array so that finalScore is identical to anyName  
		System.arraycopy(anyName, 0, finalScore, 0, anyName.length);  
  
		//go through each element of array  
		for(int i=0; i<anyName.length; i++){  
            //if the value at the current element is greater than the value
            //at maxPos  
			//set the new maxPos to this position (i) 
			//same but opposite for minPos 
			if(anyName[i]>anyName[maxPos]){  
                maxPos = i;  
			} else if (anyName[i]<anyName[minPos]){  
                minPos = i;  
			}  
        }  
        //set max and min values to 0  
		finalScore[maxPos] = 0;  
		finalScore[minPos] = 0;  
  
		//print out values (before setting max and min to 0)  
		System.out.printf("     Highest Score: %.2f \n", anyName[maxPos]);  
		System.out.printf("     Lowest Score: %.2f \n", anyName[minPos]);  
  
		//print out array with max and min values discarded  
		System.out.print("Here are the scores after discarding highest and
		  lowest scores\n");  
		System.out.print("[");  
		for(int i=0; i<finalScore.length; i++){  
            System.out.printf("%.2f, ", finalScore[i]);  
		}  
        System.out.println("\b\b]");  
  
		//calculate average of finalScore  
		//create variable to store sum int sum = 0;  
		//sum all the values of the array  
		for(int i=0; i<finalScore.length;i++){  
            sum += finalScore[i];  
		}  
        //return the sum divided by total elements (the average)  
		return sum/(finalScore.length-2);  
  
	}  
}
```