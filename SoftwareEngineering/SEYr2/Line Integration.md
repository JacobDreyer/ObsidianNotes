- Integration of a function defined along a curve
- we are dealing with 2 different things/functions now
	- Function/relationship defining the curve itself
	- function that varies with position/location along that curve
	- important to keep these clear and seperate when setting these problems up

###### Definitions:
C is a curve parameterized by $x = f(t)$, $y = g(t)$, $a\leq t\leq b$, A is a point (f(a), g(a)), B is (f(b), g(b))
1. C is a [[smooth curve]] if f' and g' are continuous on the closed interval [a,b] and not simultaneaously zero on (a,b)
2. C is a piecewise [[smooth curve]] if it consists of a finite number of smooth curves $c_1, C_2, \cdots, C_n$ joined end to end
3. C is a closed curve if A=B
4. C is a simple closed curve if A=B and the curve does not cross itself
5. If C is not a closed curve, then the positive direction on C is the direction corresponding to increasing value of t

#### 3 Forms/Types of Line Integrals in the Plane
$G = G(x,y)$ is defined on a region of the plane which contains a smooth curve C
1. Line Integral of G along C from A to B with respect to x is:
$$ \int_C G(x,y)dx $$
2. Line Integral of G along C from A to B with respect to y:
$$ \int_C G(x,y)dy $$
3. Line integral of G along C from A to B with respect to the [[arc length]] is:
$$ \int_C G(x,y)ds $$

We evaluate these line integrals in different ways depending on how the curve C is defined.

But the basic idea is always to convert the line integral into into a definite integral over a single variable

#### Evaluation of Line Integrals
- Say that C is parameterized by x = f(t), y = g(t), $a\leq t\leq b$
- replace x, y with corresponding functions of t, replace dx or dy with f'(t)dt or g'(t)dt or ds with $\sqrt{[f'(t)]^2 + [g'(t)]^2}dt$, then integrate as a simple definite integral over t

- Now consider where C is not defined as a parameterized group of functions
- now it's provided as an explicit function y = f(x)     $a\leq x\leq b$
	- now we will use either x or y as the parameter
	- lets assume we are using x for now
- replace y with x, replace dy with f'(x)dx
$$ ds = \sqrt{1 + [f'(x)]^2}dx $$
Now:
$$ \int_C G(x,y)dx = \int_a^bG(x, f(x))dx $$
$$ \int_CG(x,y)dy = \int_a^bG(x,f(x))f'(x)dx $$
$$ \int_CG(x,y)ds = \int_a^bG(x,f(x))\cdot\sqrt{1+[f'(x)]^2}dx $$

### [[Line Integration for Vector Functions]]
![[Line Integration for Vector Functions]]

### Practice Problems
[[NMM2276.9.8]]
