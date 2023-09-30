##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Matrix Inverses
$$ A^{-1} $$
- Inverse of [[Matrices]]
- Note
$$ A\cdot A^{-1} = I_n $$
- $I_n$ = [[Identity Matrix]]
- A square non-invertible matrix is called ==singular==
- If a matrix has 2 identical rows or columns it is singular

#### Inverse Properties
$$ (A \cdot B)^{-1} = A^{-1}\cdot B^{-1} $$
$$ (A^T)^{-1} = (A^{-1})^T $$


#### Finding an Inverse Matrix
- Form a $n\times (2n)$ matrix
$$ [\;A\quad |\quad I_n\;] $$
- Bring left side of the matrix ($A$) to Reduced [[Row Echelon Form]]
- Right side becomes $A^{-1}$
$$ [\;I_n\quad|\quad A^{-1}\;] $$
- Inverse of 2x2 matrix:
$$ A^{-1} = \frac{1}{\det(A)}\cdot
\begin{pmatrix}
d & -b \\
-c & a
\end{pmatrix}
$$
- Adjoint Method:
$$ Adj(A) = C_{ij}^T $$
$$ A^{-1} = \frac{1}{\det(A)}\cdot Adj(A) $$


#### [[Determinate]]s
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
	- $(-1)\times$ each element on diagonal multiplied together

- 

###### Properties of Determinates
$$ \det(A\cdot B) = \det(A)\cdot\det(B) $$
$$ \det(A^T) = \det(A) $$
- Given $\det(A) = 7$ Find $\det(3\cdot A)$
$$ \det(3\cdot A) = 
\begin{pmatrix}
r_1\to3\cdot r_1 \\
r_2\to3\cdot r_2 \\
r_3\to3\cdot r_3
\end{pmatrix}
= 3^{1+1+1}\cdot\det(A)
$$
