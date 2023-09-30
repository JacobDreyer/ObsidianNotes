#### What is It?
Simplified analysis of an algorithms efficiency
- It gives us the complexity in terms of input size N
- examine basic computer steps
- examines time and space
- We can examine worst-case, best-case, and average-case

#### General Rules
1. Ignores Constants
2. Certain terms dominate others
$$ O(1) < O(\log n) < O(n) < O(n\log n)<O(n^2)<O(2^n)<O(n!) $$

#### Worst Case
Big O notation

Upper bound of order of growth of a function

Pick the most Dominating Term (The Largest)

ex. 
```
print(stuff); //O(1)       
for(0 to n)       //O(N)         //O(N) * O(1) = O(N)
	print(stuff); //O(1)
for(0 to n)           //O(N)     //O(N) * O(N) * O(1) = O(N^2)
	for(0 to n)       //O(N)     //O(N) * O(1)
		print(stuff); //O(1)
```

Total becomes:
$$ O(N^2) + O(N) + O(1) \to O(N^2) $$

##### Math Solution:

if $\exists$ constants a,b > 0
$f(n) \leq a\cdot g(n)\quad\forall n\geq b$ 

Then $f(n) = O(g(n))$

#### Best Case
Big $\Omega$ Notation


In these cases we are given f(n) and we need to find the O/$\Omega$/$\Theta$


if $\exists$ constants a,b > 0
$f(n) \geq a\cdot g(n)\quad \forall n\geq b$

then
$f(n) = \Omega(g(n))$

##### Different Cases
- f(n) is a polynomial
	- $\Omega(n^k)$
		- k is the largest power of n in polynomial

#### Average Case
Theta

We write $f(n) = \Theta(g(n))$ 

if $f(n) = O(g(n))$ and $f(n) = \Omega(g(n))$

==Suppose that f (n) = Θ(g(n)) and g(n) = Θ(h(n)) then f (n) = Θ(h(n))==


NOTE:
For an algorithm we basically want to figure out how many times it is running (n) and that will be the complexity

