[[Polar Curves]]

Integrating using (r,$\theta$)
$$ dA = r\cdot dr\cdot d\theta $$
## Two Types:
#### Type I
![[Pasted image 20230211112249.png]]

Region bounded by
$$ \alpha\leq \theta\leq \beta $$
$$ g_1(\theta)\leq r\leq g_2(\theta) $$
So we integrate over (think "elimininate") r first, then $\theta$ 
$$ \int\int_R f(r,\theta)dA = \int_\alpha^\beta\int_{g_1(\theta)}^{g_2(\theta)} f(r,\theta) dr\cdot d\theta $$
Integrate r first which yields a function of $\theta$ only. Then integrate over $\theta$

#### Type II
![[Pasted image 20230211112719.png]]
Region bounded by:
$$ a\leq r\leq b $$
$$ h_1(\theta)\leq \theta\leq h_2(\theta) $$
Integrate over (eliminate) $\theta$ first then r
$$ \int\int_R f(r,\theta)dA = \int_a^b\int_{h_1(r)}^{h_2(r)} f(r,\theta)\cdot d\theta\cdot dr $$



$$ \int\int_Rf(r,\theta)dA = \int\int_R dA = Area\; of\; region\; R $$
Not at all different than what we had in cartesian cordinates

And

$$ V = \int\int_R f(r,\theta) dA $$ Would be the volumen below the region below $f(r,\theta)$ and over R

### Practice Problems
[[NMM2276.9.11]]
