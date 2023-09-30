### 3 versions
1. Fourier Transform
$$ f\{f(x)\} = \int_{-\infty}^\infty f(x)e^{i\alpha x}dx = F(\alpha) $$
- Inverse Fourier Transform
$$ f^{-1}\{F(\alpha)\} = \frac1{2\pi}\int_{-\infty}^\infty F(\alpha)e^{-i\alpha x}d\alpha = f(x) $$
2. Fourier Cosine transform
$$ f_c\{f(x)\} = \int_0^\infty f(x)\cos\alpha xdx = F(\alpha) $$
- Inverse Cosine transform
$$ f_c^{-1}\{F(\alpha)\} = \frac2\pi\int_0^\infty F(\alpha)\cos\alpha xd\alpha $$
3. Fourier Sine Transform
$$ f_s\{f(x)\} = \int_0^\infty f(x)\sin\alpha xdx = F(\alpha) $$
- Inverse Fourier Sine Transform
$$ f^{-1}_s\{F(\alpha)\} = \frac2\pi\int_0^\infty F(\alpha)\sin\alpha xd\alpha $$
### Requirements and Properties
- $f, f'$ must be piecewise continuous on every interval
- $f$ must be absolutely integrable over interval
- f.t.s are [[Linear Transformation]]s:
$$ f\{c_1\cdot f(x) + c_2\cdot g(x)\} = c_1\cdot f\{f(x)\} + c_2\cdot f\{g(x)\} $$
- f.t. of the derivative of a function:
$$ f(f'(x)) = \int_{-\infty}^\infty f'(x)e^{i\alpha x}dx $$
- If $f(x)\to0$ as $x\to\pm\infty$
$$ f\{f'(x)\} = -i\alpha f\{f(x)\} $$
- More Generally:
$$ f\{f^{(n)}(x)\} = (-i\alpha)^n\cdot f\{f(x)\} = (-i\alpha)^nF(\alpha) $$
- The relationships between f.t. of derivatives of a function and that function make integral transformation a key/important tool for solving many [[PDE]]s

### Cosine and Sine F.T and Derivatives
- The cosine and sine transformations of a first (or any odd) derivatives of f are not useful, because they do not give results in terms of the transformation of the original function
- But they do work in helpful ways for 2nd (and even) derivatives of $f$
$$ f_c\{f''(x)\} = -\alpha^2F(\alpha) - f'(0) $$
$$ f_s\{f''(x)\} = -\alpha^2F(\alpha) + \alpha f(0) $$
- All cases assume that f is absolutely integrable on $[0,\infty]$, and $f,f'$ are continuous, and both $f,f'\to 0$ as $x\to\infty$
- If you have a second order PDE and the domain of one of the spatial variables is $[0,\infty]$, you would choose either the $f_c$ or the $f_s$ transformations, depending on whether the boundary condition at $x=0$ is specified in terms of the function value or the derivative of that function value
	- i.e do you know f(0) or f'(0)

### Rectangular Pulse
- Calculate the Fourier Transform of:
$$ f(x) = 
\begin{cases}
		A, \;\;\;-p\leq x\leq p \\
		0, \;\;\;|x|> p
\end{cases}
$$
- and then represent f(x) as a fourier integral

Why can't we express this as a [[Fourier Series]]?
- It's not periodic

Instead we are led to analyze this as a Fourier Transform

$$ F(\alpha) = f\{f(x)\} $$
$$ = \frac1{2\pi}\int_{-\infty}^\infty f(x)e^{-i\alpha x}dx $$
$$ = \frac A{2\pi}\int_{-p}^pe^{-i\alpha x}dx $$
$$ = \frac A{2\pi}\frac{e^{-i\alpha p} - e^{i\alpha p}}{-i\alpha} $$
$$ = \frac A{\pi\alpha}\cdot\frac{e^{i\alpha p} - e^{-i\alpha p}}{2i} $$
$$ = A\frac{\sin\alpha p}{\pi\alpha} = \frac{A\cdot p}{\pi}(\frac{\sin\alpha p}{\alpha p}) $$
$$ = \frac{A\cdot p}{\pi}\cdot\sin c(\alpha p) $$
Here we define: $\sin c(\alpha p) = \frac{\sin\alpha p}{\alpha p}$
More Generally: $\sin c(x) = \frac{\sin(x)}{x}$
$$ F(\alpha) = \frac{2A\cdot p}{2\pi}\sin c(\alpha p) $$
Okay so what does $F(\alpha)$ look like?
Firstly, $F(0)$
$$ F(0) = \frac{2Ap}{2\pi}\cdot\frac{\sin(0)}0 \to [\frac 00] $$
$$ \lim_{\alpha\to 0}\frac{\sin(\alpha p)}{\alpha p} = \frac{p\cdot\cos(\alpha p)}p=1 $$
$$ \therefore F(0) = \frac{2Ap}{2\pi} $$
$2Ap$ is the integral of f(x) $\to$ the area of f(x)

That's a fundamental feature of the F.t. The value of the transform of f(x) at $\alpha = 0$ is the integral area of f(x) over all space
$\Rightarrow$ the "$2\pi$" is a feature of the definition of the f.t pairs as we've defined them

It works both ways:
$$ f(x) = \int_{-\infty}^\infty F(\alpha)e^{i\alpha x}dx $$
$$ f(0) = \int_{-\infty}^\infty F(\alpha)d\alpha $$
- ^ total integral of $F(\alpha)$

$\therefore$ we know that:
$$ f(0) = A = \int_{-\infty}^\infty \frac{Ap}{\pi}(\frac{\sin(\alpha p)}{\alpha p})d\alpha $$
$$ A = \frac{Ap}{\pi}\int_{-\infty}^\infty \frac{\sin(\alpha p)}{\alpha p} $$
$$ \Rightarrow \int_{-\infty}^\infty\frac{\sin(\alpha p)}{\alpha p}d\alpha  = \frac\pi p$$
- Continuing on what does $F(\alpha)$ look like?
$$ F(\alpha) = \frac{2Ap}{2\pi}\sin c(\alpha p) = \frac{2Ap}{2\pi}(\frac{\sin(\alpha p)}{\alpha p}) $$
- clearly we have zeros where $\sin(\alpha p) = 0$ (no longer considering $\alpha = 0$)
$$ \alpha_n = \pm \frac{n\pi}p\quad (n\neq 0) $$
- Finally we know that
$$ |F(\alpha)|\propto\frac1{\alpha} $$
- So $F(\alpha)$:
	- $F(0) = \frac{2Ap}{2\pi}$
	- $F(\alpha_n) = 0$, $\alpha_n = \frac{n\pi}p$, $n = \pm 1, \pm 2,\pm 3, \cdots$
	- $F(\alpha)$ decreases as $\frac1\alpha$
![[Pasted image 20230417122609.png]]

- So we like to draw this "situation" like this:
![[Pasted image 20230417122706.png]]

- What is "sharp" in one domain is oscillatory in the other 
- let p get smaller (and assume A gets larger, such that Ap is a constant)
![[Pasted image 20230417122826.png]]
- So the sharper and narrower you are in one domain (here, f(x) is getting narrower and higher as we let $p\to 0$), the broader you get in the other domain

### [[Parseval's Theorem for Fourier Integrals]]
![[Parseval's Theorem for Fourier Integrals]]

### F.T of Gaussian
Let $G(x) = e^{\frac{-x^2}{a^2}}$
calculate F.T of G(x)

$$ g(p) = \int_{-\infty}^\infty e^{\frac{-x^2}{a^2}}e^{ipx}dx $$
To do this integral (another trick of sorts), we "[[complete the square]]" in the exponent argument:
$$ g(p) = \int_{-\infty}^\infty e^{(\frac{-x^2}{a^2}+ipx)}dx $$
Consider $\frac{-x^2}{a^2} + ipx$

$$ -(\frac xa - \frac{ipa}2)^2 = -(\frac xa)^2 + ipx + (\frac{pa}2)^2 $$
$$ -\frac{x^2}{a^2}+ipx = -(\frac xa -\frac{ipa}2)^2 - (\frac{pa}2)^2 $$
$$ g(p) = \int_{-\infty}^\infty e^{-(\frac  xa - \frac{ipa}2)^2}e^{-(\frac{pa}2)^2}dx $$
$$ g(p) = e^{-(\frac{pa}2)^2}\int_{-\infty}^\infty e^{-(\frac  xa - \frac{ipa}2)^2}dx $$
Now let $z = \frac xa - \frac{ipa}2$
$\frac{dz}{dx} = \frac1a \;\Rightarrow\; dx = a\cdot dz$
$$ g(p) = a\cdot e^{-(\frac{pa}2)^2}\int_{-\infty}^\infty e^{-z^2}dz $$
$\int_{-\infty}^\infty e^{-z^2}dz\to\sqrt \pi$

So finally
$$ g(p) = a\cdot\sqrt \pi\cdot e^{-(\frac{pa}2)^2} = a\sqrt\pi\; e^{-(\frac{a^2}{2})p^2} $$

So $G(x) = e^{-\frac{x^2}{a^2}}$
Transforms to $g(p) = a\cdot\sqrt\pi\cdot e^{\frac{-p^2}{\frac2{a^2}}}$
(width parameter "$\frac{\sqrt 2}{a}$")
![[Pasted image 20230417125736.png]]
- So the [[Gaussian]] or [[Normal Distribution]] function has a F.T. that is also [[Gaussian]]
	- But widths are essentially reciprocal
	- What is broad in one domain is narrow in the other

