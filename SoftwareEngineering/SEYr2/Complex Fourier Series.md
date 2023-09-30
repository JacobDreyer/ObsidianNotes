- these are a series of relations between trigonometric functions (real valued functions of a real variable x) and complex exponential functions:
- Recall [[Euler's Formula]]: ($i = \sqrt{-1}$)
$$ e^{ix} = \cos x + i\sin x $$
$$ e^{-ix} = \cos x - i\sin x $$
- (Same Formula)
- Conversely we can express cos and sin in terms of complex exponentials:
$$ \cos(x) = \frac{e^{ix} + e^{-ix}}2 $$
$$ \sin x = \frac{e^{ix} - e^{-ix}}{2i} $$
- We can use the above expressions to convert our expressions for the [[Fourier Series]] of $f$ into a complex fourier series involving a sum of complex valued exponential functions
$$ f(x) = \sum^{+\infty}_{n=-\infty}c_ne^{\frac{inx\pi}p} $$
$$ c_n = \frac1{2p}\int_{-p}^{+p}f(x)e^{\frac{inx\pi}p}dx\qquad n=0, \pm 1\pm 2\cdots $$
