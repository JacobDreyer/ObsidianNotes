```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will print student info stored in a student class **********************************/  
package Q3;  
  
public class StudentDemoClassJacob {  
  
    public static void main(String[] args){  
        //initialize students  
		//will be set with default values Student student1 = new Student();  
		//these students receive hardcoded values  
		Student student2 = new Student(250221375, "Addie", "Slowgrave");  
		Student student3 = new Student(250309716, "Talia", "Hanscom");  
		Student student4 = new Student(250136525, "Valeria", "McCloughen");  
  
		//call header to print header  
		myHeader("Jacob Dreyer", 4, 3);  
  
		//print out my information (default information) by calling
		//respective get methods  
		System.out.println("Here is my information:");  
		System.out.println("========================");  
		System.out.printf("I am %s \nStudent Number: %d \nEmail Address: %s
		  \nAge: %d \n", student1.getName(), student1.getStudentNumber(),
		  student1.getEmailAddress(), student1.getAge());  
  
		//print out other student info by calling respective methods for each
		//student  
		System.out.println("Here is the info on the other students:");  
		System.out.println("========================================");  
		System.out.println("Number     Name");  
		System.out.println("========================================");  
		System.out.printf("%-10d %s \n%-10d %s \n%-10d %s \n", 
		  student2.getStudentNumber(), student2.getName(),
		  student3.getStudentNumber(), student3.getName(),
		  student4.getStudentNumber(), student4.getName());  
  
		//call footer to print footer  
		myFooter();  
	}  
  
    public static void myHeader(String fullName, int labNum, int questionNum)
    {  
        //print the header using given name, lab number and question number  
		System.out.println("*********************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*******************************************");  
	}  
  
    public static void myFooter() {  
        //print the statement given the message  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
  
	}  
}
```