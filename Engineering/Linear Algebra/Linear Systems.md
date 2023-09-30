##### Note Info
Date: [[2022-04-20]]
Course: Engineering
Class: [[Linear Algebra]]
## Linear Systems
- Unknowns/Variables enter the equation linearly with constant coefficients
- A system of linear equations is $m$ linear equations with the same variables and different coefficients
- If a System has a solution (can find a consistent value  for the variable(s) across the equations) it is ==Consistent==
- No Solution ==Inconsistent==

- We can use [[Matrices]] to solve the system

- To solve an augmented matrix we can use [[Matrix Operations]] to get to [[Row Echelon Form]]

- In [[Row Echelon Form]]:
- Any variable corresponding to columns with leading 1s are ==Leading Variables==
- Any variable corresponding to columns without leading 1s are ==Free Variables==
- If a consistent system has free variables is has infinite solutions

- Once in REF you can use the new/simplified equations to solve the system
- If all the elements on the right side of the equations are 0. The system is homogenous
- Homogenous systems have at least 1 solution: all variables = 0
- A homogenous system will have ($n-r$) free variables
	- So if $n-r$ > 0 there is infinite solutions
	- If $n-r = 0$ there is only the zero solution

#### Solving a System using [[Matrix Inverse]]s
- Create matrix $A$ of coefficients
- Create matrix $\bar b$ of right hand side (answers)
- $\bar X$ is matrix of solutions
$$ \bar X = A^{-1}\cdot\bar b $$
- NOTE: $A^{-1}\cdot\bar b$ is [[matrix multiplication]]

#### Cramer's Rule
- Matrix $A$ of coefficients
- Replace column $i$ with $\bar b$
- using [[Determinate]]s
$$ x_i = \frac{\det(A_i)}{\det(A)} $$

