z- we can use the concept of a vector function to write a general line integral in a compact manner
- let $\vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j$ be a vector function defined on (x,y) plane/space
- We are going to consider $\vec F(x,y)$ along a curve C defined by
$$ x = f(t),\quad y = g(t), \quad a\leq t\leq b $$
	and we define
$$ \vec r(t) = f(t)\hat i + g(t)\hat j $$
	to be position vector of points on the curve C

Consider:
$$ \frac{d\vec r}{dt} = f'(t)\hat i + g'(t)\hat j = \frac{dx}{dt}\hat i + \frac{dy}{dt}\hat j $$
$$ d\vec r = dx\;\hat i + dy\;\hat j $$
$$ \vec F(x,y)\cdot d\vec r = P(x,y)dx + Q(x,y)dy $$
$$ \int_C[P(x,y)dx + Q(x,y)dy] = \int_C\vec F\cdot d\vec r $$
Extending the same discussion to 3 space and line integral on a space curve:
$$ \vec F(x,y,z) = P(x,y,z)\hat i + Q(x,y,z)\hat j + R(x,y,z)\hat k $$
$$ \vec r(x,y,z) = x\;\hat i + y\;\hat j + x\;\hat k $$
$$ d\vec r = dx\;\hat i + dy\;\hat j + dz\;\hat k $$
$$ \int_C\vec F\cdot d\vec r = \int_C[P(x,y,z)dx + Q(x,y,z)dy + R(x,y,z)dz] $$
### Practice Problems:
[[NMM2276.9.8]]
