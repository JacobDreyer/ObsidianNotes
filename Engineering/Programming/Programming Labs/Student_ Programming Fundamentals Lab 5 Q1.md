```java
package Q1;  
  
public class Student {  
    //initialize variables  
	private String name = "0";  
	private int studentNumber = 0;  
	private int score = 0;  
  
	public Student(){  
        //set variables  
		name = "Jeff";  
		studentNumber = 123456789;  
		score = 42;  
	}  
  
    public Student(String nm, int sNum, int sc){  
        //set variables given inputed values  
		name = nm;  
		studentNumber = sNum;  
		score = sc;  
	}  
  
    public void printInfo(){  
        //print the students info  
		System.out.printf("%-15s %-15d %-3d (letter grade:%-2s)\n", name,
		  studentNumber, score, getLetterGrade());  
	}  
  
    public String getName(){  
        //return students name  
		return name;  
	}  
  
    public int getScore(){  
        //return students score  
		return score;  
	}  
  
    public String getLetterGrade(){  
        //determine the letter grade associated with the score and return it  
		if(score >= 90){  
            return "A+";  
		} else if (score >= 80){  
            return "A-";  
		} else if (score >= 70){  
            return "B+";  
		} else if (score >= 60){  
            return "B-";  
		} else if (score >= 50){  
            return "C+";  
		} else if (score >= 40){  
            return "C-";  
		} else if (score >= 30){  
            return "D";  
		} else {  
            return "F";  
		}  
    }  
}
```