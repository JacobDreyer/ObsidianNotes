```java
package Q3;  
  
public class CourseAndInstructor extends InstructorInfo{  
    //create a variable to store courseName  
	private String courseName = " ";  
  
	public CourseAndInstructor(){  
  
    }  
  
    public CourseAndInstructor(String cN, String fN, String lN, String oL){  
        //call parent constructor to assign given variables  
		super(fN, lN, oL);  
		//assign course name here because its an added variable  
		courseName = cN;  
	}  
  
    public String toString(){  
        //Create string to store course name + other info(name, course name)
        //that can be formatted by parent toString  
		//return it //could also use String.format() 
		return "Course Name: " + courseName + "\n" + super.toString();  
 }  
}
```