$$ f(x) = \frac{a_0}2 + \sum_{n=1}^{\infty}[a_n\cdot\cos(\frac{n\pi x}{p}) + b_n\cdot \sin(\frac{n\pi x}{p})] $$
- Note that each term has a different minimum period
	- Let T be the period in x (min period)
$$ \frac{n\pi T}p = 2\pi \quad \Rightarrow\quad T = \frac{2p}{n} $$
- But integer multiples of any period of a periodic function are also periods
$\Rightarrow$ all terms in the [[Fourier Series]] over $[-p, p]$ have a common period of $2p$

- 2p is the fundamental period of the sum (the sum will be repetitive over multiple periods)

You can think about or approach/treat the periodic extension property two ways
1. For a general non periodic $f(x)$:
	- We can solve for the f.s. of $f(x)$ over some interval, say $[-2,2]$
	- The resulting f.s. will actually represent a different function that matches f(x) over the period, and then repeats that over and over
![[Pasted image 20230402194541.png]]
![[Pasted image 20230402194557.png]]

2. if you start with a periodic f(x) with a period 2p, then you can automatically represent f(x) over all x simply by solving for the f.s. of f(x) over a single period
![[Pasted image 20230402194954.png]]