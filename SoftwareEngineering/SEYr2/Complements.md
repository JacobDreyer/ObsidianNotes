---
date-created: 2022-09-14
---
## Complements
- Used to simplify the subtraction operation
- 2 types of complements for each base-r system
	- (r-1) complement ([[Diminished Radix Complement]])
	- r complement ([[Radix Complement]])
	- For binary (r=2): The one's complement and 2's complement

#### Diminished Radix Complement
- Given a number $N=(x_{n-1}\cdots x_0)_r$ having n digits: 
	- (r-1)'s complement of N = $(r^n-1) - N$

#### Radix Complement
$$ (N) = (2^n-1) - N = (1\cdots11)_2-(x_{n-1}\cdots x_1x_0)_2
$$
$$ = (x_{n-1}'\cdots x_1'x_0')_2 $$
- $x_i' = 1-x_1$
- Change 1s to 0s and 0s to 1s

#### R's Complement
$$ (N) = r^n - N $$
- n = # of digits
- r = base
- N = number in base r

- also equals (r-1)'s complement + 1

Ex. 7s complement of 4532:
7777 -
4532 =
3245 + 1

#### Subtraction with Complements
If A-B >0


$$ A + \bar B = S + cr^n $$
$\bar B$ = r's complement of B
c = 1

If A-B < 0

$$ A + \bar B = S $$
D = Difference = $-\bar S$
$\bar S$ = r's complement of S

If There is no carry out the answer is wrong