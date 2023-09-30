- It's cool to know/show that 2 given functions are orthogonal over some interval
- But the power is going to come from constructing sets of [[Orthogonal Function]]s
	- Sort of families that we will use together in solving groups of problems

- A set of real valued functions $\{\phi_0(x), \phi_1(x), \cdots\}$ is said to be orthogonal on an interval \[a,b\] if:
$$ (\phi_m, \phi_n) = \int_a^b\phi_m(x)\phi_n(x) = 0 $$
- for $m\neq n$
- One additional step/feature to tank onto the orthogonal case
- Recall the [[Norm]] of a Vector:
$||\vec u||$ -> length of $\vec u$
$\vec u\cdot\vec u = ||\vec u||^2$ -> square norm

- Extend concept of Norm to a function
$$ ||\phi_n(x)||^2 = (\phi_n, \phi_n) = \int_a^b\phi_n^2(x)dx $$
- Square Norm

- If {$\phi_n(x)$} is an orthogonal set of functions on the interval \[a,b\] with property that $||\phi_n(x)|| = 1$ for $n = 0,1,2,\cdots$ then {$\phi_n(x)$} is said or defined to be an orthogonal set on the interval
- Any orthogonal set of non-zero functions can be normalized (made into orthogonal set) by dividing each member by its norm

### Expression of any Vector as sum of Orthogonal Vectors
- Assume we have 3 orthogonal vectors in 3-space 
- We say that these 3 can be used as a basis for the 3-space, and we can in general always express or represent any vector in that space as a linear combination of those 3 vectors:
$$ \vec u = c_1\vec v_1 + c_2\vec v_2 + c_3\vec v_3 $$
- $c_i$ - the components of vector $\vec u$ when expressed in terms of the $\vec u$ basis
- Can obtain $c_i$ from knowledge of $\vec u$ and $\vec v_i$

Procedure:
$$ (\vec u, \vec v_1) = (c_1\vec v_1 + c_2 \vec v_2 + c_3\vec v_3, \vec v_1) $$
$$ = c_1(\vec v_1, \vec v_1) + c_2(\vec v_2, \vec v_1) + c_3(\vec v_3, \vec v_1) $$
$$ = c_1||\vec v_1||^2 + c_2\cdot\theta + c_3\cdot\theta $$
$$ = c_1||\vec v_1||^2 $$
$$ c_1 = \frac{(\vec u, \vec v_1)}{||\vec v_1||^2}\qquad c_2 = \frac{(\vec u, \vec v_2)}{||\vec v_2||^2}\qquad c_3 = \frac{(\vec u, \vec v_3)}{||\vec v_3||^2}\qquad $$
$$ \vec u =  \frac{(\vec u, \vec v_1)}{||\vec v_1||^2}\vec v_1+  \frac{(\vec u, \vec v_2)}{||\vec v_2||^2}\vec v_2+  \frac{(\vec u, \vec v_3)}{||\vec v_3||^2}\vec v_3 $$
### Expression of a Function as  Sum of Othogonal Functions
- Say we have {$\phi_n(x)$} as orthogonal, infinite set of functions over \[a,b\]
- If we have $f(x)$ also defined on \[a,b\], can/how we identify coefficients $c_n$ such that:
$$ f(x) = c_0\phi_0(x) + c_1\phi_1(x)+\cdots +c_n\phi_n(x) + \cdots $$
- We are going to follow analogous procedure as did for the vector expansion
$$ (f,\phi_m) = \int_a^bf(x)\phi_m(x)dx $$
$$ = c_0\int_a^b\phi_0(x)\phi_m(x)dx + c_1\int_a^b\phi_1(x)\phi_m(x)dx + \cdots + c_n\int_a^b\phi_n(x)\phi_m(x)dx  $$
$$ = c_0(\phi_0, \phi_m) + c_1(\phi_1, \phi_m) + \cdots + c_n(\phi_n, \phi_m) + \cdots $$
- But we know that $\phi_n(x)$ is orthogonal set. so all inner products are zero except $n=m$
$$ \int_a^bf(x)\phi_n(x)dx = c_n\int_a^b\phi_n(x)^2dx $$
$$ c_n = \frac{\int_a^bf(x)\phi_n(x)dx}{\int_a^b\phi_n^2(x)dx}, n = 0,1,2,\cdots $$
- So we can express some arbitrary $f(x)$ in terms of a series {$\phi_n(x)$} where:
$$ f(x) = \sum_{n=0}^\infty c_n\phi_n(x) $$
Where
$$ c_n = \frac{\int_a^bf(x)\phi_n(x)dx}{\int_a^b\phi_n^2(x)dx} = \frac{\int_a^bf(x)\phi_n(x)dx}{||\phi_n(x)||^2} $$
Expressed using inner product notation:
$$ f(x) = \sum_{n=1}^\infty \frac{(f,\phi_n)}{||\phi_n(x)||^2}\phi_n(x) $$
- We are assuming that our set of orthogonal set of functions is complete. This means that the only continuous function orthogonal to each member of the set is the zero function


