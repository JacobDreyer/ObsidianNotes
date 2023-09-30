```java
package Q3;  
  
public class InstructorInfo extends Name{  
    //create a String to store office location  
	private String officeLocation = " ";  
  
	public InstructorInfo(){  
  
    }  
  
    public InstructorInfo(String fN, String lN, String oL){  
        //assign values. Parent constructor can assign first name and last
        //name  
		super(fN, lN);  
		//office location is a new added variable so we have to assign in
		//here  
		officeLocation = oL;  
	}  
  
    public String toString(){  
        //add all data to string. Parent toString can assign name. Here we
        //just have to add officeLocation  
		//could use String.format to format it easier 
		return "Instructor's Info:\n" + super.toString() + "Office 
		  Location: " + officeLocation;  
	}  
}
```