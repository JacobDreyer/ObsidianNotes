- earlier we used [[Green's Theorem]] in the plane to relate the integral of the tangential component of a [[Vector Fields]] around a closed curve, to the [[Surface Integral]] of the [[Curl]] of $\vec F$ over region enclosed by C.

[[Green's Theorem]] in the Plane:
$$ \oint_{C^+}[Pdx + Qdy] = \iint_R (\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y})dA  $$
and if $\vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j$
$$ \oint_{C^+}\vec F\cdot d\vec r = \oint_C \vec F\cdot \vec T ds = \iint_R (\nabla \times \vec F) \cdot\hat n dA $$
And More Generally ([[Stoke's Theorem]])
$$ \vec F(x,y,z) = P(x,y,x)\hat i + Q(x,y,z)\hat j + R(x,y,z)\hat k $$
$$ \oint_{C^+}\vec F\cdot d\vec r = \oint_{C^+}(\vec F\cdot \vec T) dS = \iint_R (\nabla \times \vec F)\cdot \hat n\; dS  $$
- integral of tangential component of $\vec F$ around C, equals [[Surface Integral]] of normal component of [[curl]] of $\vec F$

- now consider the "opposite": look at normal component of $\vec F$ integrated around closed plane curve C
$$ \oint_C (\vec F\cdot \hat n)ds $$
Let
$$ \hat n = (\frac{dy}{ds})\hat i - (\frac{dx}{ds})\hat j $$
be unit normal to C

Recall:
$$ \hat T = (\frac{dx}{ds})\hat i + (\frac{dy}{ds})\hat j $$
was unit tangent to C
=> $\hat T\cdot \hat n = 0$

#### Putting it Together
$$ \oint_C (\vec F\cdot \hat n)ds = \oint_C [Pdy - Qdx] = \iint_R [\frac{\partial P}{\partial x} - (\frac{-\partial Q}{\partial y})] = \iint_R (\nabla \cdot \vec F)dA $$
### In 3-Space
D be a closed and bounded region in 3-space bounded by a piecewise-smooth boundary S oriented outward
Let $\vec F(x,y,z) = P(x,y,z)\hat i + Q(x,y,z)\hat j + R(x,y,z)\hat k$
be a [[Vector Fields]] for which P, Q, R are continuous and have continuous first partial derivatives in the region containing D

Then:
$$ \iint_S(\vec F\cdot \hat n)dS = \iiint_D\nabla\cdot \vec F\; dV $$
