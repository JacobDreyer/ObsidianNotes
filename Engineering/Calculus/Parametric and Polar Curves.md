##### Note Info
Course: [[Engineering]]
Class: [[Calculus]]
Unit: Parametric and Polar Curves
Date: 2022/04/05

## Parametric and Polar Curves
#### [[Parametric Curves]]
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

Area bounded by curve is same as any other. create slices
$$ A = \int_a^b g(t)\cdot f'(t)dt $$


#### [[Polar Curves]]
- [[polar coordinates]] consist of an angle and a length/magnitude r

$x = r\cos\theta$
$y = r\sin\theta$

$r^2 = x^2 + y^2$
$\tan\theta = \frac{y}{x}$

- A curve in polar coordinates can be written as $r = f(\theta)$

Slopes:
$$ \tan\psi = \frac{f(\theta)}{f'(\theta)} $$
- $\psi$ = angle between slope and r
- A slope is vertical if $\tan\psi = \cot\theta$
- A slope is horizontal if $\tan\psi = -\tan\theta$
- if $f'(\theta)$ = 0 and $f(\theta)$ = 0 then the slope DNE. It has a cusp

Areas:
$$ A = \frac12\int_{\theta_1}^{\theta_2}f(\theta)^2d\theta $$

Arc Length:
$$ L = \int_{\theta_1}^{\theta_2}\sqrt{(f(\theta))^2+(f'(\theta))^2} d\theta $$


