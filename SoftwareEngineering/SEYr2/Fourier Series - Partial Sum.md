$$  f(x) = \frac {a_0}2 + \sum_{n=1}^\infty(a_n\cos\frac{n\pi x}p + b_n\sin\frac{n\pi x}p) \quad [-p,p]  $$
- If the [[Fourier Series Convergence]] criteria are met for f, this is a "hard equal", if n is allowed to go to $\infty$, for all values of x in the interval

But for finite n upper limit ($n\leq N$):
$$ f(x) \simeq f_{fs} = \frac {a_0}2 + \sum_{n=1}^N(a_n\cos\frac{n\pi x}p + b_n\sin\frac{n\pi x}p)  $$
- clearly $f_{fs}(x)$ is a better and better approximation of f(x) as $N\to\infty$

$f_{fs}(x)$ does not approach $f(x)$ at the same rate for all values of x
- In particular, at a discontinuity in $f(x)$, $f_{fs}(x)$ exhibits a "ringing" phenomenon at both sides of the discontinuity
$\Rightarrow$ "[[Gills Phenomenon]]" or "[[Gills Ringing]]"
- Almost appears as though the f.s becomes a worse approximation of $f(x)$ near the discontinuity as N gets larger (Not the case actually but seems that way)

1. The amplitude of the max overshoot increases with increasing N, to a limit. The overshoot amplitude itself converges as $N\to\infty$ (depending on nature of f to self)
2. The location of the overshoot moves towards the discontinuity as $N\to\infty$. So, for anyx value you want accuracy at, you need to let N get larger until the overshoot "moves past" your point of interest, and you will eventually get convergence of the f.s. to f at that located

