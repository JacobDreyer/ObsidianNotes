[[Big O Notation V2]]

- O-Notation, known as the order of an algorithm, represents the worst-case time requirment of the Algorithm. In the table below-
	- Algorithm A has a worst-case time requirement proportional to n - O(n). 
		- In, short, we say algoritm-A is O(n); 
			- we call it "Big O of n" or 
			- "order of at most n"
- Algorithm analysis is focused on the growth rate. The multiplicative constants have no impact on growth rates. The growth for n/2 or 100n is the same as n
|                  | Algoritm A | Algorithm B | Alorithm C |
| ---------------- | ---------- | ----------- | ---------- |
| Assignments      | n+1        | 1+n(n+1)/2  | 1          |
| Additions        | n          | n(n+1)/2    | 1          |
| Multiplications  |            |             | 1          |
| Divisions        |            |             | 1          |
| Total Operations | 2n+1       | $n^2+n+1$   | 4          |

The Big O Notation estimates the execution time of an algorithm in relation to the input size. If the time is not related to input size, the algorithm is said to take constant time with the notation O(1)
- For Example: a method that retrieves an element at a given index in an array takes constant time because it does not grow as the size of the array increases

Consider the Algorithm for finding the maximum number in an array of n elements
- if n is 2, it takes one comparison to find the max
- if n is 3, it takes two comparisons to find the max
- In general it takes n-1 comparisons to find the max
- Algorithms Efficiency for large input size:
	- If the input size is small, there is no significance to estimate an algorithms efficieny
	- As n grows larger. the n part in n-1 starts to dominate
	- ==The Big O notation allows us to ignore the non-dominating part== and highlight the dominating part (n in this case). So the complexity is O(n)

### Identities for Big O
$$ O(kf(n)) = O(f(n)) $$
$$ O(f(n))+O(g(n)) = O(f(n)+g(n)) $$
$$ O(f(n))\times O(g(n)) = O(f(n)g(n)) $$

### Rules for Big O
- if f(n) is a polynomial of degree d then f(n) is O($n^d$)
	- drop lower-order terms
	- drop constant factors
- Use the smallest possible class of functions
	- say 2n is O(n) instead of 2n is O($n^2$)
- Use the simplest expression of the class
	- Say 3n+5 is O(n) instead of 3n+5 is O(3n)

### Practical Considerations
- The big O notation provides a good theoretical estimate of an algorithm's efficiency
- However, two algorithms of the same time complexity are not necessarily equally efficient

### Comparing Common Growth Functions
- $O(1)$ - Constant time
- $O(\log n)$ - Logarithmic Time
- $O(n)$ - Linear Time
- $O(n\log n)$ - Log-Linear Time
- $O(n^2)$ - Quadratic Time
- $O(n^3)$ - Cubic Time
- $O(2^n)$ - Exponential Time
$$ O(1) < O(\log n) < O(n) < O(n\log n) < O(n^2) < O(n^3) < O(2^n) $$
