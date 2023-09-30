```java
package Q3;  
  
public class Student {  
    //initialize variables  
	private int studentNumber = 0;  
	private int yearOfBirth = 0;  
	private String firstName = "0";  
	private String lastName = "0";  
	private String emailAddress = "0";  
  
	public Student(){  
        //set default variables if no values are given  
		studentNumber = 251241714;  
		yearOfBirth = 1998;  
		firstName = "Jacob";  
		lastName = "Dreyer";  
		emailAddress = "jdreyer4@uwo.ca";  
	}  
  
    public Student(int sn, String fName, String lName){  
        //set variables with received values  
		studentNumber = sn;  
		firstName = fName;  
		lastName = lName;  
		yearOfBirth = 0;  
		emailAddress = "";  
	}  
  
    public int getStudentNumber(){  
        //return student number  
		return studentNumber;  
	}  
  
    public String getName(){  
        //return full name by adding the 2 strings for first name and last 
        //name  
		return firstName + " " + lastName;  
	}  
  
    public String getEmailAddress(){  
        //return email address  
		return emailAddress;  
	}  
  
    public int getAge(){  
        //return age given current year and year of birth  
		return 2022 - yearOfBirth;  
	}  
}
```
