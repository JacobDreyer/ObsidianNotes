Remember [[Green's Theorem]] in the Plane and we emntioned how this could be expressed in terms of [[Vector Fields]]

Then we can relate Green's Theorem as:
$$ \oint_{C^+} \vec F\cdot d\vec r = \oint_{C^+} \vec F\cdot \vec Tds = \iint_R (\nabla \times \vec F)\cdot \hat n dA  $$
- The [[Line Integral]] of the tangential component of $\vec F$ around a closed contour is equal to the [[Double Integral]] ([[Area Integral]]) of the normal component of the [[Curl]] of $\vec F$ over the area enclosed by the contour
- so now we extend into [[Green's Theorem]] in [[3-Space]]
- Going to relate a [[Line Integral]] around a [[Piecewise Smooth]] [[Simple Closed Curve]] C forming the boundary of a surface S, with a [[Surface Integral]] over S

#### Stoke's Theorem Statement:
- Let S be a [[Piecewise Smooth]] orientable surface bounded by a piecewise smooth [[Simple Closed Curve]] C. let $\vec F = P\hat i + Q\hat j + R\hat k$ be a [[Vector Fields]] for which P, Q, R are continuous and have continuous first [[Partial Derivative]]s in region of [[3-Space]] containing S. If C is traversed in the positive direction:
$$ \oint_{C^+}\vec F\cdot d\vec r = \oint_{C^+}(\vec F \cdot  \vec T)ds = \iint_S (\nabla \times \vec F)\cdot \hat n\;dS $$
	where $\hat n$ is a unit normal to S in direction of orientation of S