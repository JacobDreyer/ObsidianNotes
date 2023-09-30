##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Matrix Multiplication
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