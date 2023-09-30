$$ Ly(x) = f(x) $$
And f(x) is made up of only terms with polynomials in x ($x^2$), exponentials ($e^{rx}$), and $\cos(kx)/\sin(kx)$ plus products of these terms we can guess a $y_p$ but with coefficients that we will need to use the DE to find.

1. If no term in f(x) is also a solution to the associated homogenous DE:

We can take a linear combination of all the linearly independent terms in f(x) and all their possible derivatives as our trial solution.
$$ x^n\to x^n, x^{n-1},\cdots, x^1, x^0 $$
$$ y_p\to A_{n}x^n + A_{n-1}x^{n-1}+\cdots+A_1x^1 + A_0x^0 $$
------------------------- B --------------------------------------
$$ e^{rx}\to e^{rx} $$
$$ y_p\to Be^{rx} $$
------------------------- C ---------------------------------------
$$ \cos(kx)\to\cos(kx), \sin(kx) $$
$$ \sin(kx)\to\cos(kx), \sin(kx) $$
$$ y_p \to D\cos(kx)+E\sin(kx) $$
	For Products of these terms we take products of the above

2. If one of the terms in part 1 is a solution to the associated homogeneous DE then we need to multiply that term by $x^{s}$, where s is the smallest psoitive integer such that we no longer have terms that are solutions to the associated homogenous DE

We then take the trial solution $y_p$, substitute it into the non-homogenous DE
$$ Ly_p(x) = f(x) $$
This will give us a system of algebraic equations to solve to get all the constants/coefficients
