```java
package Q3;  
  
public class StudentInfo extends Name{  
    //create variable to store student number and a CourseAndInstructor to
    //store all the course info  
	private int studentNumber = 0;  
	private CourseAndInstructor courseInfo;  
  
	public StudentInfo(){  
  
    }  
  
    public StudentInfo(String fN, String lN, int sN, CourseAndInstructor
      cInfo){  
        //parent constructor can assign first name and last name  
		super(fN, lN);  
		//assign course info and student number here  
		courseInfo = cInfo;  
		studentNumber = sN;  
	}  
  
    public String toString(){  
        //This will return ALL the relevant info except grades  
		//parent to String can write Name 
		//add student number 
		//courseInfo.toString will add all the course info 
		//could use String.format() to format string. 
		return super.toString() + "Student Number: " + studentNumber + "\n"
		  + courseInfo.toString();  
	}  
}
```