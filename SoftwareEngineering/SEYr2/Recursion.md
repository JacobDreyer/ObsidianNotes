## Recursion
#### [[Java]]
We are used to calling others methods from a method in Java but its also possible for a method to call itself

A method that calls itself is called a [[Recursive Method]]

Ex.
```java
public class EndlessRecursion {
	public static void main(String[] args){
		message();
	}
	public static void message(){
		System.out.println("Do Nothing");
		message();
	}
}
```

Like a loop, a recursive method must have some way to control the number of times it repeats.

#### Solving Problems with Recursion
- Is a powerful tool for solving repetitive problems
- Any problem that can be solved Recursively can also be solved with a loop
- Often recursive algorithms are less efficient
- Recursive Solutions repetitively:
	- allocate memory for parameters and [[Variables]]
	- Store address of where control returns after the method terminates
- These actions are called overhead and take place each method call
- This overhead does not occur with a loop
- Some repetitive problems are easier solved with recursion
	- Iterative algorithms (loops) might execute faster, However:
	- a recursive algorithm might be designed faster


- Base Case
	- Values of the input variables for which we perform no recursive calls are called base cases (there should be at least one base case)(to end the loop??).
	- Every possible chain of recursive calls must eventually reach a base case.
	- There can be more than one base-case for a recursive method.
- Recursive Calls
	- Calls to the current [[Method]]
	- Each recursive call should be defined so it makes progress to a base case
	- the # of times a method calls itself is known as the depth of recursion

##### Iteration
Iteration is a technique used to run a block of code repeatedly until a specific condition no longer exists. Iterations are normally performed with loops.

##### Recursion
Recursion is a technique that repeats itself until a base case, in terms of a simpler version of itself, is satisfied.

### Examples
- [[SE2205-LabExercise1]] (Q1)