```java
package Q3;  
  
public class GradeActivity {  
    //create variables  
	//array to store multiple score, score to store a single score. Score
	//will end up storing the final average grade 
	//int to store what it is graded out of 
	//percent score to get percentage private double[] grade;  
	private double score;  
	private int outOf;  
	private double percentScore;  
  
	public GradeActivity(){}  
  
    public GradeActivity(double score, int outOf){  
        //if given a single score assign it to score and assign Outof value  
		this.outOf = outOf;  
		this.score = score;  
	}  
  
    public GradeActivity(double[] grade, int outOf){  
        //if given multiple scores (in array) assign it to grade array  
		//assign out of value this.outOf = outOf;  
		this.grade = grade;  
		//calculate average of these grades  
		//store it in score double sum = 0;  
		for(int i = 0; i< grade.length; i++){  
            sum+= grade[i];  
		}  
        if(outOf == 100)  
            score = sum;  
		else 
			score = sum/ grade.length;  
	}  
  
    public double getScore() {  
        return score;  
	}  
  
    public String getLetterGrade(){  
        //calculate percent  
		percentScore = score/outOf*100;  
		//based on percent determine Letter grade  
		if(percentScore >=90) return "A+";  
		else if(percentScore >=80) return "A";  
		else if(percentScore >=70) return "B";  
		else if(percentScore >=60) return "C";  
		else if(percentScore >=50) return "D";  
		else return "F";  
	}  
  
    @Override  
	public String toString() {  
        //The arguments of String.format() is written in the same way as the
        //arguments of printf()  
		return String.format("%.2f (out of %d), Letter Grade: %s [%.2f%%]",
		  score,outOf, getLetterGrade(),percentScore);  
	}  
}
```