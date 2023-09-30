Some Sudden force
![[Drawing 2022-12-09 17.57.57.excalidraw]]
$$ P = \int_0^{\infty}f(t)dt $$
We only worry about P. The form of f(t) isn't actually important

So we model f(t) but make sure we get the proper impulse (P):
![[Drawing 2022-12-09 18.01.32.excalidraw]]
To do this we define:
$$ \delta_{\epsilon}(t-t_0) = \begin{cases}
\frac1\epsilon\; if\; t_0\leq t\leq t_0+\epsilon \\
0 \quad otherwise
\end{cases} $$
 
![[Drawing 2022-12-09 18.08.52.excalidraw]]
f(t) has an impulse of P so i model f(t) as 
$$ f(t) = P\delta_\epsilon(t-t_0) $$

### The Delta Function:
$$ \delta_\epsilon(t-t_0) $$

### The Dirac Delta Function
$$ \delta(t-t_0) = \lim_{\epsilon\to 0}\delta_\epsilon(t-t_0) $$
$$ \int_0^\infty g(t)\delta(t-t_0)dt = g(t_0)\quad t_0\geq 0 $$
$$ \mathcal L[\delta(t-t_0)] = e^{-st_0} $$
$$ \mathcal L[\delta(t)] = 1 $$