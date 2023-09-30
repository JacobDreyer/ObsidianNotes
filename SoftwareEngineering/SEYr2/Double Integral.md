(Two-dimensional definite integral)

- we are now integrating some function of 2 variables
$$ f(x,y) $$
	over some region R in x,y plane

The geometric interpretation of this integral is that it represents the volume between the x,y plane and $f(x,y)$

$$ V = \int\int_R f(x,y)dA $$
$dA$ = area elements within R

as we will see, $dA = dx\cdot dy$ for integration of fuctions $f(x,y)$

### Properties
$$ \int\int_R l\cdot f(x,y)dA = l\cdot\int\int_Rf(x,y)dA $$
$l$ = constant

$$ \int\int_R[f(x,y)\pm g(x,y)]dA = \int\int_Rf(x,y)dA + \int\int_Rg(x,y)dA $$

$$ \int\int_Rf(x,y)dA = \int\int_{R_1}f(x,y)dA + \int\int_{R_2}f(x,y)dA $$
When $R = R_1 \cup R_2$ and $\phi = R_1\cap R_2$

### Regions of Type I and Type II
#### Type I
R:
- x limits are constants
- y limits are functions

#### Type II
R:
- y limits are constants
- x limits are functions

### Iterated Integration
- If we set up our integral as Type I we integrate with respect to y first, then finish by integrating over x -> end result must be a number

$$ \int_a^b\int_{g_1(x)}^{g_2(x)}f(x,y)\;dy\;dx = \int_a^b[\int_{g_1(x)}^{g_2(x)}f(x,y)\;dy\;]\;dx $$
$[\int_{g_1(x)}^{g_2(x)}f(x,y)\;dy\;]$ will be purely a function of x after integrating

If we set up the integral as a type II we simply do the opposite; integrate over x before y

### [[Polar Double Integration]]
![[Polar Double Integration]]

### Practice Problems
[[NMM2276.9.10]]
