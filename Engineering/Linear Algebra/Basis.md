##### Note Info
Date: [[2022-04-25]]
Course: Engineering
Class: [[Linear Algebra]]
## Basis
- $V$ is a [[Vector Space]]
- A set of elements of $V$ ($\vec v_1, \vec v_2, \cdots, \vec v_n$) is a basis of $V$ if:
	- the elements are linearly independent([[Linear Independence]])
	- the [[Span]] of the elements $= V$
- If the the elements are a basis of $V$ any vector can be written in a unique way as a linear combination of the elements of the basis:
$$ \vec v = c_1\cdot\vec v_1 + c_2\cdot\vec v_2 + \cdots + c_n\cdot\vec v_n $$
- the coefficients are the coordinates of $\vec v$ in the given basis

#### [[Basis Dimension]]
- Any [[Vector Space]] $V$ will have a basis. In fact, $V$ can have many different basis. All such basis of $V$ have the same number of vectors. This # = dimension of $V$
$$ \dim(\mathbb{R}^n) = n $$
$$ P_3 \; : \{1,x,x^2,x^3\} \qquad \dim(P_3) = 4 \qquad \dim(P_n) = n+1 $$
$$ 
M_{2\times 2} = 
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
\qquad \dim(M_{2\times 2}) = 4 \qquad \dim(M_{m\times n}) = m\cdot n
$$
- vector of functions of a single variable: $\dim(\digamma) = \infty$

- If $W \subset V$ is a subspace of $V$ then the dimension of W is less or equal to that of $V$
- If $\dim(W) = \dim(V) \Rightarrow W = V$
- If $W \neq \{\vec 0\} \subset V$ is a subspace of $V$ and $\dim(W) < \dim(V)$ then $W$ is a ==proper subspace== of $V$ 

- Dimension will equal # of free varibles


