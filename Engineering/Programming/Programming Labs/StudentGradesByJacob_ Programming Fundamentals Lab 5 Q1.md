```java
/**********************************  
 * Jacob Dreyer * 251241714 * 2022-02-07 * In this task the program will print student info **********************************/  
package Q1;  
  
public class StudentGradesByJacob {  
    public static void main(String[] args){  
        //initialize 2 new students  
		Student student1 = new Student();  
		Student student2 = new Student("Jacob Dreyer", 251241714, 42);  
  
		//print my header  
		myHeader("Jacob Dreyer", 5, 1);  
  
		//print the students info (student number, score, and letter grade)  
		System.out.println("Name          Student Number  Score  (Letter
		  Grade)");  
		System.out.println("---------------------------------------------");  
		student1.printInfo();  
		student2.printInfo();  
		System.out.println("----------------------------------------------");  
  
		//determine how the students compare and print it  
		if (student1.getScore() > student2.getScore()){  
            System.out.printf("Note: %s scored higher than %s.\n",
              student1.getName(), student2.getName());  
		} else if (student2.getScore() > student1.getScore()){  
            System.out.printf("Note: %s scored higher than %s.\n",
              student2.getName(), student1.getName());  
		} else  {  
	        System.out.println("Note: Their scores are equal!");  
		}  
  
        //print the footer  
		myFooter();  
	}  
  
	public static void myHeader(String fullName, int labNum, int questionNum)
	{  
        //print the header using given name, lab number and question number  
		System.out.println("*******************************************");  
		System.out.println(fullName);  
		System.out.println("Lab " + labNum + ", Question " + questionNum);  
		System.out.println("*******************************************");  
 }  
  
    public static void myFooter() {  
        //print the statement  
		System.out.println("\n *** Signing off - Jacob Dreyer ***");  
	}  
}
```