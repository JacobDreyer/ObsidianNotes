##### Note Info
Date: [[2022-04-25]]
Course: Engineering
Class: [[Linear Algebra]]
## Common Spaces
- Consider $m\times n$ matrix ($A$)
$$
\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\cdots & \cdots & \cdots & \cdots \\
a_{m1} & a_{m2} & \cdots & a_{mn}
\end{pmatrix}
$$
##### [[Row Space]]
- The rowspace of $A$ is the subspace of $\mathbb{R}^n$ spanned by the rows of $A$
$$ \vec r_1 = (a_{11}, a_{12}, \cdots, a_{2n}) $$
$$ \vec r_2 = (a_{21}, a_{22}, \cdots, a_{1n}) $$
$$ \cdots $$
$$ \vec r_m = (a_{m1}, a_{m2}, \cdots, a_{mn}) $$
- The row space is not changed by [[Elementary Row Operations]]
##### [[Column Space]]
- The column-space of $A$ is the subspace of $\mathbb{R}^n$ spanned by the columns of $A$
$$ 
\vec c_1 = 
\begin{pmatrix}
a_{11} \\
a_{21} \\
\vdots \\
a_{m1}
\end{pmatrix}, \qquad
\vec c_2 = 
\begin{pmatrix}
a_{12} \\
a_{22} \\
\vdots \\
a_{m2}
\end{pmatrix}, \qquad \cdots, \qquad
\vec c_n = 
\begin{pmatrix}
a_{1n} \\
a_{2n} \\
\vdots \\
a_{mn}
\end{pmatrix}
$$
- NOTE: $\vec c_n$ is not linearly independent. This means the dimension of the column space is 1 smaller

##### [[Null Space]]
- space of solutions to a homogenous system
$$ A\cdot\vec X = \vec 0 $$
- is a subspace of $\mathbb R^n$
- null space is not changed by [[Elementary Row Operations]]

- Find $3\times 3$ [[Matrices]] who null space is:
	- A point
	- a line: 
		- 1 free variable
	- a plane:
		- 2 free variables



