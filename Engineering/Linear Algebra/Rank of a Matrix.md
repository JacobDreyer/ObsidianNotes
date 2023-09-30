##### Note Info
Date: [[2022-04-25]]
Course: Engineering
Class: [[Linear Algebra]]
## Rank of a Matrix
- let $A$ be a $m\times n$ matrix
- [[Row Space]] and [[Column Space]] of $A$ always have the same dimension. This dimension is called a rank of $A$
- Nullity is the dimension of null space of $A$
- ==Rank of $A$ plus Nullity of $A$ is # of columns of $A$==

- Let $A$ be $n\times n$ matrix
- if rank(A) = n
	- A is non-singular (invertible)
	- $A\cdot\bar X = \bar b$ always has a solution
	- $A\cdot\bar X = 0$ only has a zero solution
		- Nullity(A) = 0

- If $m > n$ system is called overdetermined; there is always a $\bar b$ such that $A\cdot\bar X = \bar b$ is inconsistent (has no solution)
- If $m < n$ the system is called underdetermined; in this case for any $\bar b$ the system is:
	- inconsistent
	- has infinite solutions
 