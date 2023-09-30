##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Matrix Operations
- Operations performed on [[Matrices]]
###### Multiplication by a Scalar
- Multiply each element in the Matrix by scalar

##### Addition of Matrices
- Add each element of Matrix with the corresponding element of the other array (add the elements at the same location)
- The two matrices must be the same size

###### [[Matrix Multiplication]]
- Multiply array A and B
$$
\begin{pmatrix}
\cdots & \cdots & \cdots \\
a_{i1} & \cdots & a_{ir} \\
\cdots & \cdots & \cdots
\end{pmatrix} 
\qquad \qquad
\begin{pmatrix}
\cdots & b_{1j} & \cdots \\
\cdots & \cdots & \cdots \\
\cdots & b_{rj} & \cdots
\end{pmatrix} 
$$
$$ (A\cdot B)_{ij} = (a_{i1}\times b_1j) + (a_{i2}\times b_{2j}) + (a_{ir}\times b_{rj}) $$
- Order:
	- Row 1 A     &     Column 1 B     at     (1,1)
	- Row 1 A     &     Column 2 B     at     (1,2)
	- $\cdots$
	- Row 2 A     &     Column 1 B     at     (2,1)
	- Row 2 A     &     Column 2 B     at     (2,2)
	- $\cdots$

- Size of array for $(a\times b)\cdot(c\times d)$ is $(a\times d)$
- $b$ and $c$ must be the same number for matrix multiplication

##### [[Transpose Matrix]]
$$ A^T $$
- Rows -> Columns
- Columns -> Rows
- Ex:
$$
\begin{pmatrix}
1 & 2 & -1 \\
3 & -5 & 6 
\end{pmatrix}
\to
\begin{pmatrix}
1 & 3 \\
2 & -5 \\
-1 & 6
\end{pmatrix}
$$
- Order:
	- Row 1 -> Column 1
	- Row 2 -> Column 2
	- $\cdots$



#### [[Elementary Row Operations]]
- Useful to bring [[Matrices]] to [[Row Echelon Form]]
###### Switch
- Swap two rows
- $r_1 \leftrightarrow r_2$ 

###### Multiply
- Multiply a row by a non-zero constant
- apply multiplication to each element in the row
- $r_1 \rightarrow (-3)\cdot r_1$

###### Add a Row
- add a constant multiple of another row to a row
- $r_1 \rightarrow r_1 + (-3)\cdot r_2$



