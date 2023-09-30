##### Note Info
Date: [[2022-04-21]]
Course: Engineering
Class: [[Linear Algebra]]
## Determinates
- A matrix is only invertible if the determinate $\neq$ 0
- $M_{ij}$ = Minor entry of $a_{ij}$ 
	- size of $(n-1)\times(n-1)$
	- found by removing coloumn $j$ and row $i$ from $A$
- $C_{ij} = (-1)^{i+j}\; M_{ij}$

- Pick a column or row (one with most zeros)
- Go through each element of row/column
- Value of that element($a_{ij}$) times $(-1)^{i+j}$ and times determinate of $M_{ij}$

- Can use [[Elementary Row Operations]] to simplify Matrix 

- Determinate of 2x2 [[Matrices]]:
$$
A = 
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$
$$ \det(A) = a\cdot d - b\cdot c  $$
- Determinate of Upper [[Triangular Matrix]]:
	- $(-1)\times$ each element on diagonal

###### Properties of Determinates
$$ \det(A\cdot B) = \det(A)\cdot\det(B) $$
$$ \det(A^T) = \det(A) $$