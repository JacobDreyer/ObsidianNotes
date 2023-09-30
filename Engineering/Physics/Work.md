#### [[Electric Field]] and [[Electric Potential Energy]]
- [[Electric Force]] is a [[conservative force]] meaning all that matters in the start and endpoints and not the path taken
$$ W_{AB} = -(U_B-U_A) $$
- $W_{AB}$ = work to get from A to B
- $U_B$, $U_A$ = [[Electric Potential Energy]] at A and B

voltage of a battery can tell you how much [[Work]] the battery does on each coulomb of charge.
$$ W = q\Delta V $$

#### [[Line Integration]] and Work
- Theres a physical application of the vector line integration concept thats too obvious and important not to examine at this point
- Recall that the work done by a force $\vec F$ along a displacement $\vec d$ is
$$ W = \vec F\cdot\vec d $$
- In general if we consider a general force field 
$$ \vec F(x,y) = P(x,y)\hat i + Q(x,y)\hat j $$
	acting at each location along a smooth curve C : $x = f(t), y = g(t), a\leq t\leq b$
- At each location along C, $\vec F$ varies in magnitude and direction
- We define the work done by $\vec F$ along C as the line integral:
$$ W = \int_C\vec F\cdot d\vec r = \int_C[P(x,y)dx + Q(x,y)dy] $$
- Lets look at this in terms of $\vec F$ tangent to curve C
$$ \frac{d\vec r}{dt} = \frac{d\vec r}{ds}\frac{ds}{dt} $$
	for arclength s and:
$$ \frac{d\vec r}{dt} = \vec T $$
	$\vec T$ = a unit tangent vector to C
	so we could write:
$$ d\vec r = \vec T\;ds $$
	and
$$ W = \int_C\vec F\cdot d\vec r = \int_C\vec F\cdot \vec T\;ds = \int_C<comp_\vec T\vec F>ds $$
- Work done by $\vec F$ along C is due entirely to that tangential component of $\vec F$ at each location along C
- if $\vec F$ is everywhere $\perp$ to $\vec T$ (perpindicular to the curve) the work done must be 0
- 