$$ a_nx^ny^{(n)}(x) + a_{n-1}x^{n-1}y^{(n-1)}(x) + \cdots + a_0x^0y(x) = f(x) $$
Coefficient is not a constant.

#### General Solution:
$$ y(x) = y_c(x) + y_p(x) $$
$y_p(x)$ can still be found from [[variation of parameter]]

So we need to figure out how to solve associated homogenous differential  equation

Assume:
$$ y(x) = x^m $$
and sub it into the differential equation to find values of m that yield solutions

So consider the kth term
$$ a_kx^k\frac{d^k}{dx^k}x^m = a_kx^k m(m-1)(m-2)\cdots(m-k+1)x^{m-k} $$
$$ = a_k\cdot m(m-1)\cdots(m-k+1)x^m $$
So every term in DE will have an $x^m$ in it
$x^m$ times a whole bunch of terms that depend on m = 0

The whole bunch of terms must equal zero.
This is our ==characteristic equation==
This will give the values of m that yield solutions

3 cases for roots:
1. Real and distinct
$$ y_1(x) = x^{m_1}\qquad y_2(x) = x^{m_2} $$
$$ y_c(x) = C_1x^{m_1} + C_2x^{m_2} $$
2. Real but repeated:
$$ y_1(x) = x^{m_1} \qquad y_2(x) = \ln|x|x^{m_1} $$
3. Complex Roots
$$ m_1 = a + ib \qquad m_2 = a-ib$$
$$ y_1(x) = x^a\cos(b\ln|x|)\qquad y_2(x) = x^a\sin(b\ln|x|) $$