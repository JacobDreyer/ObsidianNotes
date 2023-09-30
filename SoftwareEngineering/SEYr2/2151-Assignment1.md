## 2151 Assignment 1
Using info from [[Proposition]]s and [[Truth Table]]s

#### Section 2
1. Find 3 resources for discrete math outside the lecture notes and the suggested resources. For example, online notes, a textbook at the library ect. List them here.
	- Textbook
	- Youtube Lessons
	- Classmates
2. List 2 concepts/ideas/problems from the first week that you found confusing or difficult. If you found nothing difficult or confusing, what was most challenging? What are some things you hope we cover in this course?
	- I found distributive properties confusing
	- Proving statements involving numbers are also challenging
3. Write down the truth table of $(p\lor q)\land\neg(p\land q)$
| $p$ | $q$ | $(p\lor q)\land\neg(p\land q)$ |
| --- | --- | ------------------------------ |
| T   | T   | F                              |
| T   | F   | T                              |
| F   | T   | T                              |
| F   | F   | F                              |
4. Determine if (¬p∧q)∨(¬q∧p) logically equivalent to (p∨q)∧¬(p∧q). If they are logically equivalent, explain why. If they are not, give an example of truth values for p, q which make them have different truth values.
| $p$ | $q$ | $(\neg p\land q)\lor(\neg q\land p)$ | $(p\lor q)\land\neg(p\land q)$ |
| --- | --- | ------------------------------------ | ------------------------------ |
| T   | T   | F                                    | F                              |
| T   | F   | T                                    | T                              |
| F   | T   | T                                    | T                              |
| F   | F   | F                                    | F                               |
Therefore The two statements are logically equivalent because they produce the same truth values given the same truth inputs

#### Section 3
1. Recall that an integer is a number like −3, −2, −1, 0, 1, 2, 3 ect. An odd integer is an integer n that can be written n = 2 · k + 1 where k is some other integer. An even integer is m is an integer of the form m = 2 · q where q is some other integer.
	1. Are there integers $x,y$ such that 
$$ 6\cdot x + 4\cdot y = 1 $$
No because 1 is an odd number whereas 6 and four are multiples of 2 meaning that they, times their respective variables will produce an even number. and two even numbers added or subtracted cannot produce an odd number.
	2. Are there integers $x,y$ such that 
$$ 6\cdot x + 4\cdot y = 2022 $$
Divide by 2 and then 1011 (x' = x/1011 and y' = y/1011)
$$ 3\cdot x + 2\cdot y = 1011$$
$$  3\cdot x' + 2\cdot y' = 1 $$
This has integer solutions x' = 1 and y' = -1
Therefore  $6\cdot x + 4\cdot y = 2022$ has integer solutions: $x = x' \cdot 1011 = 1011$ and $y = y'\cdot1011 = -1011$

2. Let f(x) = sin(x) and g(x) = cos(x). Let D be the collection of real numbers and consider the propositional functions with domain of definition D defined by P(x) : f(x) = 0 and Q(x) : g(x) = 0 when x is a real number. In other words for a real number x, P(x) is the proposition f(x) = 0 and Q(x) is defined similarly. Let R be the statement
$$ \exists x, P(x)\land Q(x) $$
$$ \exists x, (\sin(x) = 0\;\land\;\cos(x)=0) $$
```desmos-graph
left = -6.28; right = 6.28;
top = 1.5; bottom = -1.5;
---
y = \sin(x)
y = \cos(x)
```
Therfore $\exists x, P(x)\land Q(x)$ is invalid (R is false) because as shown by the graph. There is no value of x where $\sin(x) = \cos(x) = 0$ and because sin(x) and cos(x) continue on to infinity there is no value of x to satisfy this argument.

3. Read the wikipedia entry of ”the square root of 2”. (search Square root of 2 in wikipedia or google and find the link) You do not need to understand everything, but try and understand the following statement. The square root of 2 is irrational. That is, √ 2 is irrational. You may also google around and find out what this means, whatever you like.
	1. Find the Square root of 25
$$ \sqrt{25} = \pm5 $$
	2.  Explain in a few words (like you would to a family member) what it means for a real number x to be a square root of 2.
		- it means that x * x = 2 or $x^2 = 2$
	3. Explain in a few words (like you would to a family member) what the statement √ 2 is irrational means.
		- It means that the exact value of $\sqrt2$ cannot be represent as a fraction using 2 integers
	4. Let Q be the collection of rational numbers. That is fractions p/q where p, q are integers with q $\neq$ 0. Let P(x) be the propositional function with domain of discourse Q defined by P(x) : $x^2$ = 2. In other words, for a rational number x, P(x) is the statement x 2 = 2. Determine the truth of the statement
		$$ \forall x, \neg P(x) $$
		for $x^2 = 2$ to be true we can solve the equation such that the solution is $x = \pm\sqrt2$ . However the square root of 2 is irrational and Q is restricted to only rational numbers. And because $\pm \sqrt2$ are the only 2 solutions. the statement is valid. for all of x, the negative of P(x) is true.