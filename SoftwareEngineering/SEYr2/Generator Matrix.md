let C be a linear code and $\vec b_1, \cdots, \vec b_r$ a [[Basis]] of C

Set:
$$ G = 
\begin{pmatrix}
- & \vec b_1 & - \\
\vdots & \vdots & \vdots \\
- & b_r & -
\end{pmatrix}
$$
G is a matrix whose rows are the basis elements

We call G a generator matrix for C

If $\vec c \in C$ and G is a generator matrix for C then there is a unique $\vec x \in \mathbb F_2^n$ such that 
$$ \vec c = \vec x G $$
The Generator Matrix transforms a random vector (not neccessarily in C) into a vector in C

#### Getting Codes from the G Matrix
Step 1. Count the Rows
Step 2. Find all binary row vectors with ^ length = rows$^2$ 