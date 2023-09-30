## [[NMM2270.2.2]]
#### [[Seperable Differential Equations]]
1. $\frac{dy}{dx} = \sin(5x)$
$$ \int 1dy = \int\sin(5x)dx $$
$$ y = -\frac15\cos(5x) + c $$
3. $dx + e^{3x}dy = 0$
$$ \int dy = -\int e^{-3x}dx $$
$$ y = \frac13e^{-3x} $$
5. $x\frac{dy}{dx} = 4y$
$$ \int\frac{dy}{4y} = \int \frac{dx}x $$
$$ \frac14\ln y = \ln x $$
$$ y = cx^4 $$

## [[NMM2270.2.3]]
#### [[Linear 1st Order ODE]]
1. $\frac{dy}{dx} = 5y$
$$ \frac{dy}{dx} - 5y = 0 $$
$$ y(x) = e^{5x}\cdot\int e^{-5x}\cdot 0 + C\cdot e^{5x} $$
$$ y(x) = Ce^{5x} $$
3. $\frac{dy}{dx} + y = e^{3x}$
$$ y(x) = e^{-x}\cdot\int e^x\cdot e^{3x} + C\cdot e^{-x} $$
$$ y(x) = \frac14e^{3x} + Ce^{-x} $$
5. $y' + 3x^2y = x^2$
$$ y(x) = e^{-x^3}\cdot\int e^{x^3}\cdot x^2 + C\cdot e^{-x^3} $$
$$ y(x) = \frac13 + C\cdot e^{-x^3} $$

## [[NMM2270.2.4]]
#### [[Exact Differential Equation]]
1. $(2x-1)dx + (3y +7)dy = 0$

$M = (2x-1)$
$N = (3y+7)$

$$ 0 = 0 $$
$$ \int\frac{\partial f}{\partial x}dx = \int(2x-1)dx $$
$$ f = x^2-x + g(y) $$
$$ \frac{\partial}{\partial y}(x^2-x+g(y)) = 3y + 7 $$
$$ \int g'(y) = \int(3y + 7) $$
$$ g(y) = \frac32y^2 + 7y $$
$$ f = x^2 - x + \frac32y^2 + 7y = c $$

3. $(5x + 4y)dx + (4x-8y^3)dy = 0$
$M = (5x+4y)dx$
$N = (4x-8y^3)dy$

$$ 4 = 4 $$
$$ \int\frac{\partial f}{\partial x}dx = \int(5x + 4y)dx $$
$$ f = \frac52x^2 + 4xy + g(y) $$
$$ \frac{\partial}{\partial y}(\frac52x^2 + 4xy + g(y)) = 4x-8y^3 $$
$$ 4x + g'(y) =  $$
$$ \int g'(y) = -\int 8y^3 $$
$$ g(y) = -2y^4 $$
$$ f = \frac52x^2 + 4xy -2y^4 $$
5. $(2xy^2-3)dx + (2x^2y+4)dy = 0$
$M = (2xy^2-3)dx$
$N = (2x^2y+4)dy$
$$ 4xy = 4xy $$
$$ \int\frac{\partial f}{\partial x}dx = \int(2xy^2-3)dx $$
$$ f = x^2y^2-3x + g(y) $$
$$ (2x^2y + g'(y)) = (2x^2y + 4) $$
$$ \int g'(y) = \int 4 $$
$$ g(y) = 4y $$
$$ f = c = x^2y^2-3x+4y $$
7. $(x^2-y^2)dx + (x^2-2xy)dy = 0$
$M = (x^2-y^2)dx$
$N = (x^2-2xy)dy$
$$ -2y = 2x - 2y $$
## [[NMM2270.2.5]]
#### [[Substitution]]

## [[NMM2270.3.4]]
#### [[Higher Order Differential Equations]]
1. $y'' + 3y' + 2y = 6$
$$ r^2 + 3r + 2 = 0 $$
$$ (r+1)(r+2) = 0 $$
$r = -1$
$r = -2$
$$ y_c = C_1e^{-x} + C_2e^{-2x} $$

$y = A_1$
$y' = 0$
$y'' = 0$
$$ 2A_1 = 6 $$
$$ A_1 = 3 $$
$$ y = C_1e^{-x} + C_2e^{-2x} $$

3. $y''-10y'+25y = 30x + 3$
$$ r^2 - 10r + 25 = 0 $$
$r_1 = r_2 = 5$
$$ y_c = C_1e^{5x} + C_2xe^{5x} $$

$y_p = A_1x + A_2$
$y_p' = A_1$
$y_p'' = 0$
$$ -10A_1 + 25A_1x + 25A_2 = 30x + 3 $$
$25A_2 - 10A_1 = 3$
$25A_1 = 30$
$A_1 = \frac65$

$25A_2 = 15$
$ = 15$
$A_2 = \frac35$

$$ C_1e^{5x} + C_2xe^{5x} + \frac65x + \frac35 $$
5. $\frac14y'' + y' + y = x^2-2x$

$$ r^2 + 4r + 4 = 0 $$
$r_1 = r_2 = -2$
$$ y_c = C_1e^{-2x} + C_2 xe^{-2x} $$
$y_p = A_1x^2 + A_2x + A_3$
$y_p' = 2A_1x + A_2$
$y_p'' = 2A_1$

$$ \frac12A_1 + 2A_1x + A_2 + A_1x^2 + A_2x + A_3 = x^2-2x $$
$A_1 = 1$
$(2(1) + A_2) = -2$
$A_2 = -4$

$\frac12 (1) + (-\frac82) + A_3 = 0$
$A_3 = \frac72$
$$ y = C_1e^{-2x} + C_2xe^{-2x} + x^2 -4x + \frac72 $$
## [[NMM2270.3.5]]
#### [[Variation of Parameter]]

## [[NMM2270.3.6]]
#### [[Cauchy-Euler Equations]]
1. $x^2y''-2y = 0$
$y = x^m$
$y' = mx^{m-1}$
$y'' = m(m-1)x^{m-2}$

$$ (m^2 - m - 2) = 0 $$
$m_1 = 2$
$m_2 = -1$

$$ y_c = C_1x^{2} + C_2x^{-1} $$
3. $xy'' + y' = 0$
$y = x^m$
$y' = mx^{m-1}$
$y'' = (m^2 - m)x^{m-2}$
$$ x^{m-1}(m^2 - m + m) = 0 $$
$$ m_1 = m_2 = 0 $$
$$ y_c = C_1 + C_2\ln|x| $$

