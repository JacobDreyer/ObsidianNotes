
# Question 1
1. Determine if the following statements are true or false. If the statement is true, prove it. If it is false give a counter example.
### Part 1 
Let x be a real number and y a rational number.
$\forall x, \exists y$ such that x + y is rational

If x is irrational, then there exists some y such that x + y is rational

if x + y is rational, there exists some irrational x such that x + y is rational

##### Assumption
x + y is rational
##### Definition of Assumption
x + y = $\frac{a}{b}$
y = $\frac{c}{d}$
a,b,c,d are integers in lowest terms
##### Manipulations
$$x + y = \frac{a}{b}$$
$$ x + \frac{c}{d} = \frac{a}{b} $$
$$ x = \frac{a}{b}-\frac{c}{d} $$
$$ x = \frac{ad - cb}{bd} $$
##### Definition of Conclusion
##### Conclusion
x is irrational

since a,b,c,d are all integers x is a rational number
Therefore x + y can only be rational when x is rational. Therefore the statement is false


2. Let y be an irrational real number and x a real number.
$\forall y, \exists x$ such that $x\cdot y$ is rational

$$  x\cdot y =  $$
let $x = \frac1y$
$$ \frac1y\cdot y = 1 $$
for any irrational number you can multiply it by the inverse of the irrational to produce 1. a rational number. Therfore there is a value of x for every irrational y such that $x\cdot y$ is rational
### Part 3 
Let m and n be integers.
$\forall n, \exists m$ such that mn is even
##### Assumptions
n is odd, m is even
##### Definition of Assumption
n = 2$k_1$ + 1, m = $2k_2$
##### Manipulations
$$ mn = (2k_1 + 1)(2k_2) $$
$$ mn = 4k_1k_2 + 2k_2 $$
$$ mn = 2(2k_1k_2 + k_2) $$
$k_3 = 2k_1k_2 + k_2$
##### Definition of Conclusion
mn = 2$k_3$
##### Conclusion
mn is even

#### Case 2
##### Assumptions
n is even, m is even
##### Definition of Assumption
$n = 2k_1, \quad m = 2k_2$
##### Manipulations
$$ mn = (2k_1)(2k_2) $$
$$ mn = 4k_1k_2 $$
$$ mn = 2(2k_1k_2) $$
let $k_3 = 2k_1k_2$
##### Definition of Conclusion
mn = 2$k_3$
##### Conclusion
mn is even

4. Let m and n be integers.
		$\forall n,\exists m$ such that mn is odd
		Case 1
		n is even; let n = 2k
		$$ 2(km) =  $$
		Any integer multiplied by 2 is even. therefore for any even integer n there is no value of m such that $n\cdot m$ will produce an odd number
## Question 2 
The following theorem is called the division algorithm
	Theorem 2.1: (The division algorithm). Let a, b be non-negative integers. Then there are unique non-negative integers q and 0 ≤ r < b such that
	$$ a = bq+r $$
	Prove the theorem in the following manner
#### Part 1 
$\exists!$ q
0 $\leq$ r < b

##### Assumption
a is less than b
##### Definition of Assumption
a < b
##### Manipulations
$a=bq+r$
$$ bq+r < b $$
let q = 0
let r be the largest number possible
$$ b\cdot 0 + (b-1)<b $$
$$ b-1 < b $$
Case 2:
let q = 1
let r be as small as possible (to make the LS as small as possible(to satisfy eqn))
$$ b\cdot1 + 0 < b $$
$$ b \nless b $$it is false
$$ b\cdot n < b $$
$$ b\cdot (n+1) < b $$
$$ bn + b < b $$
Therefore the b is only less than b then q = 0
##### Definition of Conclusion
$\exists!$ q
##### Conclusion
q is unique

		
#### Part 2
##### Assumption
$b\cdot k \leq a$
##### Definition of Assumption
$a = (b\cdot k) + n$
let n $\geq$ 0
##### Manipulations
$$ b\cdot k < a$$
$$ bk < bq + r $$
$$ bk-bq < r $$
$$ b(k-q)<r $$

k is some positive integer, q is some positive integer
r must be less than b.

Therefore so long as k is less than q the statement is true. Also meaning that k is finite.

#### Part 3
Because S is a finite collection of integers it has a largest element. Call this biggest element q and set r = a − bq. Show that 0 ≤ r < b. Hint: Argue by contradiction. If r ≥ b then r = b + k for some integer k. Now use this to contradict the fact that q was chosen to be the largest integer with bq ≤ a. The contradiction should be ”I found an integer q2 with bq2 ≤ a and q2 ≥ q” contradicting that q was chosen to be largest with this property.

##### Assumption
r = a - bq

largest element of S is q

r $\geq$ b
###### Definition of Assumption
$b\cdot q \leq a$ 
r = b + k
k = some positive integer
##### Manipulations
$$ r = b + k $$
$$ a-bq = b+k $$
$$ a=bq + b + k $$
$$ a = b(q+1)+k $$
let $q_2$ = (q + 1)
$$ bq_2 + k = a $$
Therefore $a \geq bq_2$ and $q_2 = q + 1$ so $q_2 > q$. Therefore r must be smaller than b

#### Part 4
By part (1) and (3) we can write a = bq + r with q, r non-negative integers and 0 ≤ r < b. Show that r and q are unique in the following way. Suppose that we have integers 0 ≤ r1, r2 < b and q1, q2 such that
	$$ bq_1 + r_1 = a = bq_2 + r_2 $$
Argue by Cases:
- Suppose that r1 = r2. Show that q1 = q2. Remember not to divide by zero.
- By case (1) we may assume that r2 $\neq$ r1. So either r2 > r1 or r1 > r2. Up to relabeling our integers we may assume that r2 > r1. Rearrange the equation
$$ bq_1+r_1=a=bq_2+r_2 $$
	to obtain b(q1 − q2) = r2 − r1
- Prove that b > r2 − r1.
- Prove that b(q1 − q2) ≥ b.
- Use the last two items to derive a contradiction, showing that r1 = r2 By the first case we win.

###### Part A
##### Assumptions
$r_1$ = $r_2$
##### Definition of Assumptions
##### Manipulations
$$ bq_1 + r_1 = bq_2+r_2 $$
$$ bq_1 + r_2 = bq_2 + r_2 $$
$$ bq_1+r_2-r_2 = bq_2 $$
$$ bq_1 = bq_2 $$
if b = 0:    0 = 0 regardless of $q_1$ and $q_2$ so they are not neccessarily equal
if $b \neq 0$: divide by b
$$ q_1 = q_2 $$
##### Definition of Conclusions
$q_1 = q_2$
##### Conclusions
q 1 equals q2

##### Part B
$$  bq_1 + r_1 = a = bq_2 + r_2  $$
$$ bq_1 - bq_2 = r_2-r_1 $$
$$ b(q_1 − q_2) = r_2 − r_1 $$
##### Part C
if $r_1$ and $r_2$ are less than b then b must be larger than ($r_2$ - $r_1$) because $r_1$ must be positive. Assuming the lowest value of $r_1 = 0$ the maximum number ($r_2 - r_1$) can produce is $r_2$ which is by definition smaller than b
##### Part D


## Question 3
initialize a
initialize b

initialize r to the reminder of a divided by b
initialize q to a minus r divided by b

return r
return q

## Question 4
Using the division algorithm prove the following lemma:

Lemma. Let N be an integer such that $N^2$ = 3m for some integer m. Show that there is an integer q such that 3q = N.
#### Part A
Using the division algorithm we may write N = 3q + r where 0 ≤ r < 3. Explain why that we are done the proof if r = 0.

Because if r = 0 we acheive the formula N = 3q

#### Part B
Now argue by contradiction that r = 0. If r > 0 then r = 1 or r = 2 because 0 ≤ r < 3. First show that r = 1 leads to a contradiction of the division algorithm using the fact that $N^2$ = 3m. You will use the q, r in the division algorithm are unique, that is there is only 1 choice for q, r such that $N^2$ = 3q + r with 0 ≤ r < 3.

##### Assumption
##### Definition of Assumption
r = 1
##### Manipulations
$$ N^2 = 3m $$
$$ N\cdot N = 3m $$
$$ N = \frac{3m}{N} $$
Division Algorithm: $3m = N\cdot k + r$
$$ N = \frac{N\cdot k + r}{N} = k + \frac{r}{N} $$
$$ N^2 = Nk+r $$
$N = 3q$
$$ N^2 = 3qk + r $$
$qk$ = $m_2$
$$ N^2 = 3m_2 + 1 $$
This is a contradiction because $N^2$ is = to 3m but here we are showing it is equal to 3m + 1. Meaning that r must not equal 1

##### Assumption
##### Definition of Assumption
r = 2
##### Manipulations
$$ N^2 = 3m $$
$$ N\cdot N = 3m $$
$$ N = \frac{3m}{N} $$
Division Algorithm: $3m = N\cdot k + r$
$$ N = \frac{N\cdot k + r}{N} = k + \frac{r}{N} $$
$$ N^2 = Nk+r $$
$N = 3q$
$$ N^2 = 3qk + r $$
$qk$ = $m_2$
$$ N^2 = 3m_2 + 2 $$
This is a contradiction because $N^2$ is = to 3m but here we are showing it is equal to 3m + 2. Meaning that r must not equal 2. And if r cannot equal 1 or 2 r must equal zero.

## Question 5
Using the above lemma and the strategy for proving that  √ 2 is irrational prove that $\sqrt3$ is irrational.

##### Assumption
$\sqrt 3$ is a rational number
##### Definition of Assumption
$\sqrt 3 = \frac{a}{b}$
##### Manipulations
$$ 3 = \frac{a^2}{b^2} $$
$$ 3b^2 = a^2 $$
$a^2$ is a multiple of 3. according to the above lemma. a is also a muliple of 3
$$ 3b^2 = (3m)^2 $$
$$ 3b^2 = 9m^2 $$
$$ b^2 = 3q $$
$b^2$ is a multiple of 3. therefore b is a multiple of 3.

##### Conclusion
Therefore there is a contradiction because we stated a and b were in lowest terms meaning that $\sqrt 3$ is irrational



## Question 6
Look up the definition of a prime number.Answer the following short question. You can use the internet, your own resources whatever. Just figure it out.
#### Part 1
Describe in your own words what a prime number is

a prime number is any number that is divisible by only 1 and itself (to produce a whole number)
#### Part 2
Describe why you think prime numbers may or may be important.

prime numbers could be important because they could provide a smaller way to represent larger numbers. ex. 25 can be written as 5\*5 or 100 can be written as 5\*20

#### Part 3
Write down a rigorous mathematical definition of a prime number. It should look like p cannot be written as p = ab with some conditions on a and b.
$$ p \neq ab $$
if p is a prime number and a, b do not equal 1 or p

## Question 7
Let n be a positive integer larger then one. Show that n has a prime factor. That is, there is a prime number p and an integer k with pk = n. Do this in the following steps.
1. Towards a contradiction, suppose not. Then there is an integer n > 1 such that n has no prime factor. Prove that n must not be a prime number itself.
2. From question 7 part 3 you have a definition of what it means to be a prime number. Write down what it means for our n to not be prime.
3. We now have a collection of integers n1, n2, . . . ect such that each ni has no prime factor, and by (1) is not a prime number itself. We may order these integers n1 ≤ n2 ≤ . . . ect. So we may assume that n1 is the smallest integer without a prime factor and that n1 is not prime itself. Show that if 1 < a < n1 then a has a prime factor.

	Hint: Remember that n1 was chosen in a special way. It is smallest subject to some property!
4. Use part (2) and (3) to derive a contradiction. The contradiction is that n1 actually has a prime factor!
#### Part 1

