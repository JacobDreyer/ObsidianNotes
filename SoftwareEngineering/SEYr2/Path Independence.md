- We're using the term "path" simply to refer to the curve along which we are integrating
- We have:
$$ \int_C \vec F\cdot d\vec r = \int_C[Pdx + Qdy] $$
	for:
$$ \vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j $$
$$ \vec r(t) = f(t)\hat i + g(t)\hat j, \quad a\leq t\leq b $$
- And we have seen and understand that $\int_C \vec F\cdot d\vec r$ depends on the specific path of integration:
$$ \int_{C_1}\vec F\cdot d\vec r\neq\int_{C_2}\vec F\cdot d\vec r $$
	in general
- But we are now going to see that for some very specific (and important/practical) vector fields $\vec F$, $\int_C\vec F\cdot d\vec r$ will not depend on C but rather only the endpoints of the path $A(f(a), g(a)),\; B=(f(b), g(b))$
- Recall form of fundamental theorem of calculus:
$$ \int_a^bf'(x)dx = f(b) - f(a) $$
- If we are integrating a derivative of a function over an interval, the definite integral is simply the difference of that function at the end points of that interval

- Let C be a path on some region R of xy plane and determined by $\vec r(t) = x(t)\hat i + y(t)\hat j, \quad a\leq t\leq b$
- if $\vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j$ can be written as the gradient of a scalar function $Q(x,y)$ in R (Q is called a potential function for $\vec F$), then:
$$ \int_C\vec F\cdot d\vec r = \int_C\nabla \phi\cdot d\vec r = \phi(B) - \phi(A) $$
	Where $A(x(a), y(a))$ and $B = (x(b), y(b))$

- A vector function $\vec F$ is said to be conservative if $\vec F$ can be written as $\nabla \phi$ with $\phi$ being a potential function for $\vec F$

### Equivalent Statements/Concepts:
- $\vec F$ is a conservative vector field defined over an open connected region, and C is a closed path lying entirely within region. Then:
	- $\vec F = \nabla\phi$ for some $\phi$ ($\vec F$ is conservative) \<If and only if:>
	- $\int_C \vec F\cdot d\vec r$ is independent of path \<if and only if:>
	- $\int_C\vec F\cdot d\vec r = 0$ for every closed path

- Test for Conservative field:
$$ \vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j $$
is conservative in an open region R, then
$$ \frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x} $$
for all (x,y) in R

### [[Conservative Fields in 3-Space]]
![[Conservative Fields in 3-Space]]

### Practice Problems
[[NMM2276.9.9]]
