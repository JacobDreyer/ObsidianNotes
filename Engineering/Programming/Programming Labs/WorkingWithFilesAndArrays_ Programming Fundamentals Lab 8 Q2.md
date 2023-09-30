```java
package Q2;  
  
import java.io.*;  
import java.util.Scanner;  
  
public class WorkingWithFilesAndArrays {  
    public static void main(String[] args) throws IOException{  
        //create array to store sales values  
		//initialize other functions(File to read file, PrintWriter to write 
		//to file) double[] sales = new double[7];  
		FileWriter fw = new FileWriter("C:/School/Year
		  1/ES1056A/jdreyer4_Lab8/src/Q2/sales.txt", true);  
		
		PrintWriter appendFile = new PrintWriter(fw);
		  
		File file = new File("C:/School/Year
		  1/ES1056A/jdreyer4_Lab8/src/Q2/sales.txt"); 
		 
		Scanner inputFile = new Scanner(file);  
  
		MyMethod.myHeader("Jacob Dreyer", 8, 2);  
  
		//populate array with values from sales text file  
		for(int i=0; i<sales.length;i++){  
            sales[i] = inputFile.nextDouble();  
		}  
        inputFile.close();  
  
		//create new variable to do operations on sales array  
		WeeklySaleData_Jacob wsd = new WeeklySaleData_Jacob(sales);  
  
		//print out info about the sales  
		System.out.println("Reading the file...");  
		System.out.println("Here is this week's sale data...");  
		wsd.displaySaleData();  
		System.out.printf("Highest Weekly Sale: %.2f\n",
		  wsd.getHighestSale());  
		System.out.printf("Lowest Weekly Sale: %.2f\n", wsd.getLowestSale());  
		System.out.printf("Average Weekly Sale: %.2f\n",
		  wsd.getAverageSale());  
		System.out.printf("Standard Deviation of Weekly Sale: %.2f\n",
		  wsd.getStandardDeviation());  
  
		//write info found above to file  
		appendFile.printf("Highest Weekly Sale: %.2f\n",
		  wsd.getHighestSale());  
		appendFile.printf("Lowest Weekly Sale: %.2f\n", wsd.getLowestSale());  
		appendFile.printf("Average Weekly Sale: %.2f\n", 
		  wsd.getAverageSale());  
		appendFile.printf("Standard Deviation of Weekly Sale: %.2f\n",
		  wsd.getStandardDeviation());  
  
		//close file  
		System.out.println("...Updating the file with the above info...");  
		appendFile.close();  
		System.out.println("Closed the file...");  
  
		MyMethod.myFooter();  
	}  
}
```
