##### Note Info
Course: [[Engineering]]
Class: [[Calculus]]
Unit: Physical Applications of Integrals
Date: 2022/04/05

## Physical Applications of Integrals
#### [[Volumes By Slicing]]
- Create a slice of the object
- Do the integral on the formula for that slice

Volume by Cylindrical Shells:
$$ V = 2\pi\int_a^b xf(x)dx $$

#### [[Arc Length using Integrals]]
$$ L = \int_a^b \sqrt{1+(f'(x))^2}dx $$
$$ L = \int_c^d \sqrt{1+(g'(y))^2}dy $$
#### [[Surface Area using Integrals]]
surface of f(x) rotated about x axis:
$$ A = 2\pi\int_a^b |f(x)|\sqrt{1+(f'(x))^2}dx $$

surface of f(x) rotated about y axis:
$$ A = 2\pi\int_a^b |x|\sqrt{1+(f'(x))^2}dx $$

#### [[Mass Using Integrals]]
$$ m = \int \rho\cdot dV $$

#### [[Centre of Gravity]]
$$ \bar{x} = \frac{\int x\cdot\rho\cdot dV}{\int\rho\cdot dV} $$
- Do this for each COM coordinate needed (x, y, z)

#### [[Centroids]]
- Same as Centre of Gravity but for a object with constant density
- Can calculate the same way just with density removed

#### [[Pappus's Theorem]]
1. Find the Volume of a plane region revolved around an axis
$$ V = 2\pi r\cdot A $$
Where A is area of place or crossectional area
r = distance of [[Centroids]] to axis of rotation

2. Find Surface area of a curve revolved around an axis
$$ A = 2\pi r\cdot s $$
A = surface area

#### [[Linear 1st Order ODE]]
Given:
$$ \frac{dy}{dx} + p(x)y = q(x) $$
Answer:
$$ y(x) = e^{-\mu(x)}\cdot\int e^{\mu(x)}\cdot q(x)dx + C\cdot e^{-\mu(x)} $$
- where $\mu(x)$ = $\int p(x)dx$ 
- [[Professor Leonard]] has a great video([[Linear Differential Equations by Professor Leonard]]) explaining how this works

