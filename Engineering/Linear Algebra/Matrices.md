##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Matrices
- 2D array/table of numbers
- coordinates of a Matrix is opposite to coordinates on a graph
	- First # is how far down
	- Second # is how far across
- Can be maniuplated using [[Matrix Operations]]
#### [[Identity Matrix]] (Unit Matrix) ($I_n$)
$$
I_3 = 
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
$$
- $n$ = column/row size
- All elements are 0 except those on the diagonal
- Matrix is square
- Note:
$$ A\cdot A^{-1} = I_n $$

#### [[Augmented Matrix]]
- Used to solve [[Linear Systems]]
- Given a system of $m$ equations with $n$ unknowns:
$$ a_{11}\;x_1 + a_{12}\;x_2 + a_{1n}\;x_n = b_1 $$
$$ a_{m1}\;x_1 + a_{m2}\;x_2 + a_{mn}\;x_n = b_m $$
- We then assemble these into the Augmented Matrix
- It will have a size $m \times (n+1)$
$$
\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} & b_1 \\
a_{21} & a_{22} & \cdots & a_{2n} & b_2 \\
\vdots & \vdots & \ddots & \vdots & \vdots \\
a_{m1} & a_{m2} & \cdots & a_{mn} & b_m
\end{pmatrix}
$$
- To solve an augmented matrix we can use Elementary Row Operations([[Matrix Operations]]) to get to [[Row Echelon Form]]

- In [[Row Echelon Form]]:
- Any variable corresponding to columns with leading 1s are ==Leading Variables==
- Any variable corresponding to columns without leading 1s are ==Free Variables==
- If a consistent system has free variables is has infinite solutions

#### Elementary Matrix
- E is an Elementary Matrix if E is obtained from $I_n$ by performing a ==single elementary row operation== ([[Matrix Operations]])
- Every elementary matrix has a [[Matrix Inverse]]

#### Matrix Types:
[[Diagonal Matrix]]
- The only non-zero elements are on the diagonal
- Applying a power to a diagonal matrix:
	- apply power to each element

[[Triangular Matrix]]
- Upper Triangular Matrix
	- all elements below diagonal = 0
- Lower Triangular Matrix
	- all elements above diagonal = 0

[[Symmetrical Matrix]]
$$ A^T = A $$
- if $A$ and $B$ are symmetric:
$$ A+B\qquad,\qquad A-B\qquad,\qquad k\cdot A\qquad, \qquad A^{-1} $$
- Are symmetric