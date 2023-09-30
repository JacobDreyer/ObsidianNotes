##### Note Info
Date: [[2022-04-22]]
Course: Engineering
Class: [[Linear Algebra]]
## Linear Independence
- Any set of [[Vector]]s that contains the zero vector is linearly dependent
- Non unique solution $\Rightarrow$ set is linearly dependent
- two vectors are ==linearly dependent== when:
$$ c_1\cdot\vec v_1 + c_2\cdot\vec v_2 = 0 $$
- and at least one $c \neq 0$
- they are linearly dependent when the vectors are parallel

- A [[Vector Space]] is a ==linear independent== set of vectors if
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



