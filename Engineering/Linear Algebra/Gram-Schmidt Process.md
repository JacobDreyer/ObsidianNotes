##### Note Info
Date: [[2022-04-25]]
Course: Engineering
Class: [[Linear Algebra]]
## Gram-Schmidt Process
- Consider $V = \mathbb R^3$ with
$$ \vec V_1 = (0,1,0)\qquad \vec V_2 = (1,0,1)\qquad \vec V_3 = (1,0,-1) $$
- Note all are Orthogonal and are linearly independent([[Linear Independence]])
- This is an Orthogonal Basis

- An orthonormal basis is a set of mutually orthogonal basis vectors where each of them has the unit norm. (is a [[Unit Vector]])

- Let $V$ be a [[Vector Space]] and $S$ a [[Basis]] of $V$
- Any vector $\vec u\in V$ can be represented uniquely as:
$$ \vec u = c_1\cdot\vec V_1 + c_2\cdot\vec V_2 + \cdots + c_n\vec V_n $$
- {$c_1,c_2,\cdots,c_n$} are the coordinates of $\vec u$ in the basis $S$
- If $S$ is an Orthogonal Basis:
$$ c_n = \frac{\langle\vec u,\vec V_n\rangle}{|\vec V_n|^2} $$
- If $S$ us an Othonormal Basis:
$$ c_n = \langle\vec u,\vec V_n\rangle $$

- Let $V$ be a [[Vector Space]] and $S_{original} = (u_1,\cdots,u_n)$ a [[Basis]] of $V$. We want to convert it to an Orthogonal Basis $S = (\vec V_1,\cdots,\vec V_n)$
-  ==Process==:
	- $V_1 = u_1$
	- $V_2 = u_2 - \frac{\langle u_2, V_1\rangle}{|V_1|^2} \cdot V_1$
	- $V_3 = u_3 - [\frac{\langle u_3,V_1\rangle}{|V_1|^2}\cdot V_1 + \frac{\langle u_3, V_2\rangle}{|V_2|^2}\cdot V_2]$
	- $V_n = u_n - proj_{\{V_1, V_2, V_3,\cdots,V_{n-1}\}}u_n$

