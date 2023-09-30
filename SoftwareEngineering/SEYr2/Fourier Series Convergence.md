- We've been given the means of expressing any f(x) as sum of [[Fourier Series]] terms over some interval
- But what are the required properties of f(x) such that the expansion will work?
	- i.e. will the series converge to f(x) at any x

### Requirements on $f$:
- $f$ and $f'$ must be [[Piecewise Continuous]] on interval $[-p,p]$
	- $f$ and $f'$ can only have finite discontinuities at a finite number of points within $[-p,p]$

If that is true:
- Fourier series converge to $f$ at all points of continuity
- Fourier series converge to the average of $f$ at a point of discontinuity
$$ f_{avg} = \frac{f(x^+) + f(x^-)}{2} $$
