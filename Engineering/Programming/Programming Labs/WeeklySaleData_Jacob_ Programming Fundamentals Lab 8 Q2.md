```java
package Q2;  
  
public class WeeklySaleData_Jacob {  
    private double[] sale;  
  
	public WeeklySaleData_Jacob(){  
        sale = new double[7];  
	}  
  
    public WeeklySaleData_Jacob(double[] s){  
        //initialize sale with s  
		sale = s;  
	}  
  
    public double getAverageSale(){  
        //get average  
		//find sum int sum = 0;  
		for(int i=0; i<sale.length; i++){  
            sum += sale[i];  
		}  
  
        //return sum/length (average)  
		return sum/sale.length;  
	}  
  
    public double getHighestSale(){  
        //find location of max value  
		int maxPos = 0;  
		for(int i=0; i<sale.length; i++){  
            if(sale[i] > sale[maxPos]){  
                maxPos = i;  
			}  
        }  
  
        //return max value  
		return sale[maxPos];  
	}  
  
    public double getLowestSale(){  
        //find position of min value  
		int minPos = 0;  
		for(int i=0; i<sale.length; i++){  
            if(sale[i] < sale[minPos]){  
                minPos = i;  
			}  
        }  
  
        //return min value  
		return sale[minPos];  
	}  
	 
    public void displaySaleData(){  
        //display all the sales  
		System.out.print("[");  
		for(int i=0; i<sale.length; i++){  
            System.out.printf("%.2f, ", sale[i]);  
		}  
        System.out.println("\b\b]");  
	}  
  
    public double getStandardDeviation(){  
        //calculate the standard deviation  
		double sum = 0;  
		double avg = getAverageSale();  
		for(int i=0; i<sale.length; i++){  
            sum += Math.pow((sale[i]-avg),2);  
		}  
  
        //return standard deviation  
		return Math.sqrt(sum/sale.length);  
	}  
}
```