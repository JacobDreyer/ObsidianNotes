##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Augmented Matrix
- is a type of [[Matrices]]
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