##### Note Info
Date: 2022/04/05
## Parametric Curves
- isnt a typical graph. instead x and y are dependent on another factor:
$$ x = f(t)\qquad y = g(t) $$
- parametric equations imply a direction along the curve

Slopes of Parametric Curves:
$$ = \frac{g'(t)}{f'(t)} $$

Concavity:
$\frac{d^2y}{dx^2} > 0$ : Concave up
$\frac{d^2y}{dx^2} < 0$ : Concave down

Arc Length:
$$ L = \int_a^b \sqrt{(f'(t))^2+(g'(t))^2}dt $$
Surface Area:
about x axis
$$ A = 2\pi\int_a^b|g(t)|\sqrt{(f'(t))^2+(g'(t))^2}dt $$
About y axis
$$ A = 2\pi\int_a^b|f(t)|\sqrt{(f'(t))^2+(g'(t))^2}dt $$

Area bounded by curve is same as finding [[Volumes By Slicing]]. create slices
$$ A = \int_a^b g(t)\cdot f'(t)dt $$