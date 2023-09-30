$$ ay'' + by' + cy = g(x) $$
$$ aL[y'']+bL[y']+cL[y] = L[g(x)] $$

$$ L[f'(t)] = sL[f(t)]-f(0) $$
$$ L[f''(t)] = s^2L[f(t)]-sf(0)-f'(0) $$

$$ L[y](as^2+bs+c)+(-asf(0)-af'(0)-bf(0)) = L[g(x)] $$

$L[y]$ is the laplace transformation of the solution to the ODE
so
$$ y(t) = L^{-1}[\frac{G(s) + ((as+b)f(0)+af'(0))}{as^2+bs+c}] $$
is the solution

### More Generally
$$ L[f^{(n)}(t)] = s^nL[f(t)]-s^{n-1}f(0)-s^{n-2}f'(0)-\cdots-sf^{n-2}(0)-f^{n-1}(0) $$

ODE $\to$ L $\to$ Algebraic Eqn $\to$ soln to DE in terms of s $\to$ $L^{-1}$ $\to$ Soln in terms of t

