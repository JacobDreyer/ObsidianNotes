```java
package Q3;  
  
public class Name {  
    //create variables to store first name and last name  
	private String firstName = " ";  
	private String lastName = " ";  
  
	public Name(){  
  
    }  
  
    public Name(String firstName, String lastName){  
        //assign first name and last name  
		this.firstName = firstName;  
		this.lastName = lastName;  
	}  
  
    public String toString(){  
        //return formatted string with first name and last name  
		String fullName = firstName + " " + lastName;  
		return "Name: " + fullName + "\n";  
	}  
}
```