- What do we do for functions we need to represent over an infinite $(-\infty, \infty)$ or semi-infinite $(0,\infty)$ interval
- Let's follow the procedure from the to arrive at an infinite interval
- Express the f.s coefficients explicitly:
$$ f(x) = \frac1{2p}\int_{-p}^pf(t)dt + \frac1p\sum_{n=1}^\infty[(\int_{-p}^pf(t)\cos(\frac{n\pi t}p)dt)\cdot\cos(\frac{n\pi x}p) + (\int_{-p}^pf(t)\cdot\sin(\frac{n\pi t}p)dt)\cdot \sin(\frac{n\pi x}p)]  $$
- define $\alpha_n = \frac{n\pi}p$, $\triangle\alpha = \alpha_{n+1}-\alpha_n = \frac\pi p\;\Rightarrow\; \frac1p = \frac{\triangle\alpha}{\pi}$
$$ f(n) = \frac{\triangle\alpha}{2\pi}(\int_{-p}^pf(t)dt) + \frac1\pi\sum_{n=1}^\infty[(\int_{-p}^pf(t)\cos(\alpha_nt))\cos(\alpha_nx) + (\int_{-p}^pf(t)\sin(\alpha_nt))\sin(\alpha_nt)]\triangle\alpha $$
- Now we let $p\to\infty$, $\triangle\alpha\to 0$
- If $\int_{-\infty}^\infty f(t)dt$ exists, initial term ("$a_0$") goes to zero
- The other terms have the form:
$$ \lim_{\triangle\alpha\to 0}\sum_{n=1}^\infty F(\alpha_n)\triangle\alpha \simeq \int_o^\infty F(\alpha)dx $$
$$ f(x) = \frac1\pi\int_0^\infty[(\int_{-\infty}^\infty f(t)\cos(\alpha t)dt)\cos(\alpha x) + (\int_{-\infty}^\infty f(t)\sin(\alpha t)dt)\sin(\alpha x)]dx $$
- We call this the fourier integral of $f$ on interval ($-\infty, \infty$)
$$ f(x) = \frac1\pi\int_0^\infty[A(\alpha)\cos(\alpha x) + B(\alpha)\sin(\alpha x)]dx $$
$$ A(\alpha) = \int_{-\infty}^\infty f(x)\cos(\alpha x)dx $$
$$ B(\alpha) = \int_{-\infty}^\infty f(x)\sin(\alpha x)dx $$
- Convergence requirements: (Stricter than f.s.)
	- f and $f'$ piecewise on every finite interval
	- $f$ must be absolutely integrable on ($-\infty, \infty$)
	- $\int_{-\infty}^\infty |f(x)|dx$ must converge
- Fourier integral converges to average at point of discontinuity (as usual)
- as we had for the f.s. there are special simplifications we can make for even/off f(x)

Cosine Integral form of even f(x):
$$ f(x) = \frac2\pi\int_0^\infty A(\alpha)\cos(\alpha x)dx $$
$$ A(\alpha) = \int_0^\infty f(x)\cos(\alpha x)dx $$
Sine Integral form of odd f(x):
$$ f(x) = \frac2\pi\int_0^\infty B(\alpha)\sin(\alpha x)dx $$
$$ B(\alpha) = \int_0^\infty f(x)\sin(\alpha x)dx $$
- Also as per the f.s. there is a complex form for the fourier integral
$$ f(x) = \frac1{2\pi}\int_{-\infty}^\infty C(\alpha)e^{-i\alpha x}dx $$
$$ C(\alpha) = \int_{-\infty}^\infty f(x)e^{i\alpha x}dx $$