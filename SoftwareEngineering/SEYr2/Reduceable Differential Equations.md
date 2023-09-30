## Reduceable Differential Equations
$$ F(y(x),y'(x),y''(x),x) = 0 $$
#### 2 Cases:
1. No dependence on y(x)
$$ F(y'(x),y''(x),x)=0 $$
2. No dependence on x
$$ F(y(x),y'(x),y''(x)) = 0 $$
#### Case 1 (no dependence on y)
let P = y'(x), y''(x) = P'(x)

$$F = (x,P,P') = 0$$
1st Order

#### Case 2 (no explicit x)
$$ F(y,y',y'') = 0 $$
let $p = y'$
let $y'' = \frac{dy'}{dx}-\frac{dP}{dx} = \frac{dP}{dy}\frac{dy}{dx} = \frac{dP}{dy}P$

$$ F(y,P(y), P(y)\frac{dP(y)}{dy})=0 $$
$$ \frac{dy}{dx} = P(y) $$
$$ \int\frac{dy}{P(y)}=\int dx $$
$$ \int\frac{dy}{P(y)} = x $$
becomes $x(y)$

