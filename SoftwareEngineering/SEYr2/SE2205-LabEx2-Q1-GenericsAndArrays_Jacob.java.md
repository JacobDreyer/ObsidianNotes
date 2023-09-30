```java
package Q_LE2;  
  
import java.util.ArrayList;  
import java.util.Arrays;  
import java.util.InputMismatchException;  
import java.util.Scanner;  
  
public class GenericsAndArrays_Jacob {  
    public static void main(String[] args){  
        myHeader(2);                //print header. pass through lab 
							        //number  
  
        Integer year = 0;  
        boolean cont = true;  
        Scanner inputScan = new Scanner(System.in);  
  
        ArrayList<Integer> intList = new ArrayList<Integer> 
         (Arrays.asList(2,3,4,3,2,2)); //init arraylist with years  
        ArrayList<String> strList = new ArrayList<String> 
         (Arrays.asList("Harry", "Lavender", "Ron", "Hermoine", "Luna", "Vincent")); //init arraylist with leader names  
        Pair[] pairList = new Pair[intList.size()];  //init array to 
                                           //pair up names and years  
  
  
        for(int i=0; i<intList.size(); i++){ //loop to go through 
         //each element of array and pair up year and name in one 
         //list  
            
            Pair p = new Pair(strList.get(i),intList.get(i)); //temp 
            //var used to pair up name with corresponding year  
            
            pairList[i] = p; //add temp var to the list  
        }  
  
        while(cont){ //loop to keep running the program as long as 
                     //the user wants 
			         //next time can just use continue(); to start at 
                     //top of loop and skip the rest  
                     //(would only need the next while loop. not this 
                     //one)  
            
            ArrayList<String> tempNameList = new ArrayList<String>();   
             //temp list to store names of leaders in inputed year  
             //init here so it resets after each run through            
            
            while (year == 0) {                                       
                 //while valid year has not been chosen  
                
                System.out.println("Enter Academic Year(2,3 or 4):");   
                 //request a year  
                try {                                                   
                    //try's user's input. if valid continue. else 
                    //catch it and request new year(done by while 
                    //loop)  
                    
                    year = inputScan.nextInt();                         
                    //store user input. will automatically throw 
                    //exception if not an Int  
                    
                    if (year > 4 || year <= 1) {                        
                        //If an invalid int throw exception  
                        throw new IndexOutOfBoundsException();  
                    }  
                } catch (InputMismatchException ex) {                   
                    //catch exception. print statement. reset year to 
                    //0. clear buffer  
                    
                    System.out.print("Incorrect Output!");  
                    year = 0;  
                    inputScan.nextLine();  
                    
                } catch (IndexOutOfBoundsException ex) {                
                    //catch exception. print statement. reset year to 
                    //0. clear buffer  
                    
                    System.out.print("Incorrect Output!");  
                    year = 0;  
                    inputScan.nextLine();  
                }  
            }  
  
            for(int i=0;i<pairList.length; i++){                        
                //loop to check if year of leader matches requested 
                //year. do for each element/leader  
                
                if(pairList[i].getValue() == year){  
                    tempNameList.add((String)pairList[i].getKey()); 
                    //if year does match add it to list that stores 
                    //all names that match  
                }  
            }  
            
            System.out.println("Found " + tempNameList.size() + " 
             leader(s) from year " + year);    
            //print # of leaders in that year  
            
	        System.out.println("Here is the List:");                                                
            //print names of leaders in that year  
            
            System.out.println(tempNameList.toString());  
            System.out.println("Do you Wish to Continue? (y to 
             continue or any other key to exit"); 
            //prompt to see if continue  
            
	        if(inputScan.next().charAt(0) != 'y'){                                                  
                //if no cont = false breaking while loop  
                cont = false;  
            } else {  
                year = 0;                                                                           
                //else: they want to continue so reset year in order 
                //to ask again  
            }  
        }  
  
  
        myFooter(2); //print footer. pass through lab number  
    }  
    public static void myHeader(int labNum){  
        System.out.println("Lab Exercise " + labNum);  
        System.out.println("Prepared By: Jacob Dreyer");  
        System.out.println("Student Number: 251241714");  
        System.out.println("Goal of this Exercise: handling 
         exceptions from user inputs");  
    }  
  
    public static void myFooter(int labNum){  
        System.out.println("Completion of Lab Exercise " + labNum + " 
         is Successfull");  
        System.out.println("Signing off - Jacob");  
    }  
}
```