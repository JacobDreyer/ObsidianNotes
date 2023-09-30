##### Note Info
Date: [[2022-04-22]]
Course: Engineering
Class: [[Linear Algebra]]
## Vector Spaces
- Consider a n-tuple (a vector)
$$ \vec X = 
\begin{pmatrix}
x_1 \\
\vdots \\
x_n
\end{pmatrix}
$$
- All such n-tuples form the vector space
$$ \mathbb{R}^n $$
- Think of $\vec X$ as coordinates of a point. it is located somewhere in $\mathbb{R}^n$ 
	- for $\mathbb{R}^3$ think of vector/point in a 3D graph($\mathbb{R}^3$)
- [[Standard Basis Vectors]] in $\mathbb{R}^n$ (are similar to [[Unit Vector]]s $\hat i$, $\hat j$, and $\hat k$)
$$
\hat e_1 = 
\begin{pmatrix}
1 \\
0 \\
\vdots \\
0
\end{pmatrix}
, \qquad
\hat e_2 = 
\begin{pmatrix}
0 \\
1 \\
\vdots \\
0
\end{pmatrix}
, \qquad
\hat e_n = 
\begin{pmatrix}
0 \\
0 \\
\vdots \\
1
\end{pmatrix}
$$
- $\vec X$ is a [[Vector]]

#### Real Vector Spaces
Consider a set $V$:
- $V$ is a real vector space if it satisfies the following
- Addition:
	- $u$ and $w$ belong to $V$
	- $u + w \in V$
	- for each $u \in V$ there is an element $-u$ such that $u + (-u) = 0$
- Multiplication by a Scalar
$$ v\in V, \quad \lambda \in \mathbb{R}\quad \Rightarrow \quad\lambda\cdot v\in V $$
#### Subspaces
$$ W\in V $$
- $W$ is a vector space with operations inherited from $V$
- Ex:
$$ V\;:\quad M_{n\times n} = [n\times n] $$
- $n\times n$ real matricies
$$ W_{n\times n} = [n\times n] $$
- Symmetric $n\times n$ [[matrices]]

#### Spanning Set
#### [[Linear Independence]]
- Any set of [[Vector]]s that contains the zero vector is linearly dependent
- Non unique solution $\Rightarrow$ set is linearly dependent
- two vectors are linearly dependent when:
$$ c_1\cdot\vec v_1 + c_2\cdot\vec v_2 = 0 $$
- and at least one $c \neq 0$
- they are linearly dependent when the vectors are parallel

- A [[Vector Space]] isa linear independent set of vectors if
$$ \{\vec v_1, \vec v_2, \cdots, \vec v_k\}\in V $$
$$ c_1\cdot\vec v_1 + c_2\cdot\vec v_2 + \cdots + c_n\cdot\vec v_n = 0 $$
- has a unique solution
$$ c_1 = c_2 = \cdots = c_n = 0 $$

- If a set of vectors is not linearly independent it is call linearly dependent
- $A$ (combination of $v_i$) has a [[Matrix Inverse]] $\Rightarrow$ unique solution $\Rightarrow$ vectors are linearly independent

###### Linear Independence for Functions
$$
W(x) = 
\begin{pmatrix}
f_1(x) & \cdots & f_n(x) \\
f'_1(x) & \cdots & f'_n(x) \\
\vdots & \vdots & \vdots \\
f_1^{(n-1)}(x) & \cdots & f_n^{(n-1)}(x) 
\end{pmatrix}
$$
- If $W(x)$ is non-zero everywhere, $\{f_1(x), \cdots, f_n(x)\}$ are linearly independent

- if $W(x) = 0$ for all $x$ then $\{f_1(x), \cdots, f_n(x)\}$ are linearly dependent
- $W(x) = 0$ means [[Determinate]] of $W(x)$ equals 0

