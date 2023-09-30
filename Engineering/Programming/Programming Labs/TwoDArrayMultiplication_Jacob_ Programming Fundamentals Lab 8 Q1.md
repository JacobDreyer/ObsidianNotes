package Q1;  
  
import java.util.Scanner;  
  
public class TwoDArrayMultiplication_Jacob {  
    public static void main(String[] args){  
        //initialize variables to store row and column size of the arrays/matrices  
		 int row1 = 0;  
		 int col1 = 0;  
		 int row2 = 0;  
		 int col2 = 0;  
		 Scanner inputScan = new Scanner(System.in);  
  
		 MyMethod.myHeader("Jacob Dreyer", 8, 1);  
  
		 //request row and column size of the first matrix  
		 System.out.println("Multiplying two Arrays:");  
		 System.out.println("Enter Array 1 Info:");  
		 System.out.println("Enter row-size:");  
		 row1 = inputScan.nextInt();  
		 System.out.println("Enter column-size");  
		 col1 = inputScan.nextInt();  
		 System.out.println("Enter Array 2 Info:");  
  
		 //request row and column size of second matrix  
		//row size must be equal to column size of matrix 1 so r
		while(true){  
            System.out.println("Enter row-size");  
			 row2 = inputScan.nextInt();  
			 if(row2 == col1){  
                break;  
			 } else {  
	            System.out.println("Row size of the 2nd matrix has to be equal 
                to the column size of first matrix!");  
			 }  
        }  
  
         System.out.println("Enter column size:");  
		 col2 = inputScan.nextInt();  
  
		 //initialize the matrices  
		 int[][] array1 = new int[row1][col1];  
		 int[][] array2 = new int[row2][col2];  
  
		 //randomly populate arrays  
		 populate2DArrays(array1);  
		 populate2DArrays(array2);  
  
		 //display the matrices  
         System.out.printf("Elements of Array 1, Size[%d x %d]:\n", row1, 
         col1);  
		 display2DArrays(array1);  
		 System.out.printf("Elements of Array 2, Size[%d x %d]:\n", row2,    
         col2);  
		 display2DArrays(array2);  
  
		 //display the result of multiplying the two matrices  
		 System.out.println("Multiplying two Arrays [Array 1 x Array 2]");  
		 System.out.printf("The resulting size is: [%d x %d]\n", row1, col2);  
		 System.out.println("The resulting elements are:");  
		 display2DArrays(multiplyArrays(array1, array2));  
  
		 MyMethod.myFooter();  
	 }  
  
    public static void populate2DArrays(int[][] ma){  
		//go through each spot in array and populate it with a 
		//random number between 2 and 5  
		 for(int j=0; j<ma.length;j++){  
            for(int i=0; i<ma[j].length;i++){  
                ma[j][i] = (int)(Math.round(Math.random()*3 + 2));  
			 }  
        }  
    }  
  
    public static void display2DArrays(int[][] ma){  
        //display the entire array as a matrix  
		 for(int j=0; j<ma.length;j++){  
            //print row  
			 for(int i=0; i<ma[j].length; i++){  
	                System.out.printf("%3d ", ma[j][i]);  
				}  
            //go to next row  
			 System.out.print("\n");  
		 }  
    }  
  
    public static int[][] multiplyArrays(int[][] a, int[][] b){  
        //create product array to store product  
		 int[][] product = new int[a.length][b[0].length];  
		 int sum = 0;  
		 for(int j=0; j<a.length; j++) {  
            for(int i=0; i<b[0].length; i++){  
                //formula to calculate value for each location  
				//sum of all row[k] times column[k] 
				for(int k=0; k<a[0].length; k++){  
                    sum += (a[j][k] * b[k][i]);  
				 }  
                product[j][i] = sum;  
				 //reset sum to zero  
				 sum = 0;  
			 }  
        }  
        //return product  
		 return product;  
	 }  
}