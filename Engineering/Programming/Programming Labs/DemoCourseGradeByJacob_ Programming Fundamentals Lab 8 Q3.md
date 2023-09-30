```java
package Q3;  
  
public class DemoCourseGradeByJacob {  
    public static void main(String[] args){  
        //instantiate a variable to store all the course info and student
        //info  
		CourseAndInstructor cai = new CourseAndInstructor("Programming
		  Fundamentals", "Qauzi", "Rahman", "TEB361");  
		StudentInfo si = new StudentInfo("Jacob", "Dreyer", 2512, cai);  
		//create arrays to store multiple grades and Grade Activities to
		//calculate averages  
		double[] labG = new double[]{15,13.65,15,14.5,15,15,15};  
		GradeActivity avgLabG = new GradeActivity(labG, 15);  
		double[] quizG = new double[]{20,19.33,20,20,20};  
		GradeActivity avgQuizG = new GradeActivity(quizG, 20);  
		GradeActivity midtermG = new GradeActivity(20.71,25);  
		GradeActivity finalG = new GradeActivity(40,40);  
		double[] finalScore = new double[]{avgLabG.getScore(),
		  avgQuizG.getScore(), midtermG.getScore(), finalG.getScore()};  
		GradeActivity courseG = new GradeActivity(finalScore, 100);  
		double[] bonusG = new double[]{4.67,4.75,5,4.8,4,4.8,2.25,5,5,5,5};  
		GradeActivity avgBonusG = new GradeActivity(bonusG, 5);  
		GradeActivity reportedFinalG = new GradeActivity(courseG.getScore()
		  + avgBonusG.getScore(), 100);  
  
		//print header  
		MyMethod.myHeader("Jacob Dreyer", 8, 3);  
  
		//print course and student info  
		System.out.print(si.toString() + "\n");  
		System.out.println("==========================");  
		System.out.println("Score Card");  
		System.out.println("==========================");  
  
		//print all the avg grades  
		System.out.println("Lab Grade: " + avgLabG.toString());  
		System.out.println("Quiz Grade: " + avgQuizG.toString());  
		System.out.println("Midterm Grade: " + midtermG.toString());  
		System.out.println("Final Grade: " + finalG.toString());
		System.out.println("=========================================");  
		System.out.println("Course Grade: " + courseG.toString());  
		System.out.println("=======================================");  
		System.out.println("Bonus Quiz Grade: " + avgBonusG.toString());  
		System.out.println("Reported Final Grade (with bonus): " +
		  reportedFinalG.toString());  
		System.out.println("=========================================");  
 }  
}
```
