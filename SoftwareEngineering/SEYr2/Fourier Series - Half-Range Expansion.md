- You will have noted that we have always been restricting ourselves to the interval $[-p,+p]$
	- Symetric about the x=0 origin
- We often try to set-up problems to have symmetric domains if/when using f.s
	- Similar to choosing the "right" coord sys. when solving any problem
	- The physics "don't care", but the math after does
- Let's consider something a bit different (though not general) expansion of $f$ over interval $[0,L]$

Example: 3 different options for f.s. expansion of f
![[Pasted image 20230403100619.png]]
- We want a useable expansion of f over (0,L)
- There are options and we will arrive at different but equally valid expansions of f depending on how we treat the problem

1. We'll consider f from (-L, L) such that f is even
![[Pasted image 20230403100842.png]]
So we are calculating the expansion of the even extension of f from (-L, L)

f even $\Rightarrow$ cosine series (all $b_n = 0$)
$$ f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty}a_n\cdot \cos(n\pi\frac xL) $$
$$ a_0 = \frac 1L\int_{-L}^{+L}f(x)dx = \frac2L\int_0^Lf(x)dx = \frac2L\int_0^Lxdx = \frac2L(\frac{x^2}2)|^L_0 = \frac1L(L^2-0) = L $$
Average value of f over (-L, L)

$$ a_n = \frac1L\int_{-L}^{+L}f(x)\cos(n\pi\frac xL)dx = \frac2L\int_0^Lx\cdot \cos(n\pi\frac xL)dx $$
$$ \int udv = uv - \int vdu $$
$u = x\quad \Rightarrow\quad du = dx$
$dv = \cos(n\pi\frac xL)dx\quad \Rightarrow\quad v = (\frac{L}{n\pi})\sin(\frac{n\pi}Lx)$
$$ \int x\cos(\frac{n\pi}Lx)dx = x\cdot (\frac L{n\pi})\sin(\frac{n\pi}Lx) - \frac L{n\pi}\int\sin(\frac{n\pi}Lx)dx $$
$$ = x\cdot (\frac L{n\pi})\sin (\frac{n\pi}Lx) + (\frac L{n\pi})^2\cos(\frac{n\pi}Lx) $$
$$ \Rightarrow \frac2L\int_0^Lx\cos(\frac{n\pi}Lx)dx = \frac2L[\cancel{x\cdot(\frac L{n\pi})\sin(\frac{n\pi}Lx)}  + (\frac L{n\pi})^2\cos(\frac{n\pi}Lx)]|^L_0 $$
$$ = \frac2L(\frac L{n\pi})^2[\cos(n\pi)-1] $$
$$ a_n = \frac{2L}{(n\pi)^2}[(-1)^n-1] $$
Hence:
$$ f(x) = \frac L2 + \frac{2L}{\pi^2}\sum_{n=1}^{\infty}(\frac{(-1)^n-1}{n^2})\cdot\cos(n\pi\frac xL) $$
Check: what are units of $f(x)$? $f(x) = x$. $\Rightarrow$ units of L
- Each term in expansion must have units of L (not $L^2$ not $\frac1L$, etc)

2. Different option, still to represent the same $f$ over (0,L) except here f is odd
![[Pasted image 20230403103103.png]]
- So we are now calculating the f.s. expansion of f, odd extension from (-L, L)
- f odd $\Rightarrow$ sine series (all $a_n = 0$)

$$ f(x) = \sum_{n = 1}^{\infty}b_n\sin(\frac{n\pi x}L) $$
$$ b_n = \frac 1L\int_{-L}^{+L}x\cdot\sin(\frac{n\pi x}L)dx = \frac 2L\int_0^Lx\cdot\sin(\frac{n\pi x}{L})dx $$
$u = x\qquad du=dx$
$dv = \sin(\frac{n\pi x}{L})dx \qquad v = \frac{-L}{n\pi}\cos(\frac{n\pi x}L)$
$$ \int x\cdot \sin (\frac{n\pi x}L)dx = -\frac L{n\pi}\cdot x\cdot\cos(\frac{n\pi x}L) + \frac L{n\pi}\int\cos(\frac{n\pi x}L)dx $$
$$ = -x\frac L{n\pi}\cdot\cos(\frac{n\pi x}L) + (\frac L{n\pi})^2\sin(\frac{n\pi}Lx) $$
$$ \Rightarrow \frac2L\int_0^L x\cdot\sin(\frac{n\pi x}L)dx = \frac2L[-x\frac L{n\pi}\cos(\frac{n\pi}Lx) + \cancel{(\frac L{n\pi})^2\sin(\frac{n\pi x}L)}]|^L_0 $$
$$  = \frac2{n\pi}[-L\cos(n\pi) - 0] $$
$$ b_n = \frac{-2L}{n\pi}\cdot (-1)^n $$
Hence:
$$ f(x) = \frac{-2L}\pi\sum_{n=1}^{\infty}\frac{(-1)^n}n\sin(\frac{n\pi x}L) $$
Check units: all terms linear in L

##### Aside for 3
Originally we defined:
$$  f(x) = \frac {a_0}2 + \sum_{n=1}^\infty(a_n\cos\frac{n\pi x}p + b_n\sin\frac{n\pi x}p)  $$
for any interval other than (-p, p) such as (a, a+2p) we just need to specify a and p

for example from (0,L):
$$ 2p = L \quad p = \frac L2\quad a=0 $$
3. So now we are going to simply consider $f$ over $(0,L)$, and make the change of interval as discussed above 
	- We don't really think of it as expanding the interval by making f odd, even, or otherwise
	- we just transform the integral expressions to allow for a (0,L) calculation
	- Will still get replication with period L for free, as always with a f.s
![[Pasted image 20230403105930.png]]
$$ (a, a+2p)\to (0,L) \quad \Rightarrow\quad a=0, \;\; L = 2p, \;\Rightarrow\; p = \frac L2 $$
$$ f(x) = \frac {a_0}2 + \sum_{n=1}^{\infty}[a_n\cdot\cos(\frac{2\pi nx}L) + b_n\cdot\sin(\frac{2\pi nx}L)] $$
$$ a_0 = \frac1p\int_a^{a+2p}f(x)dx = \frac2L\int_0^L f(x)dx = \frac 2L\int_0^L xdx = L $$
Note: exactly the same as 1
$$ a_n = \frac1p\int _a^{a+2p}f(x)\cos(\frac {n\pi x}p)dx = \frac 2L\int_0^Lx\cdot\cos(\frac{2n\pi x}L)dx $$
Recall:
$$ \int x\cos(\frac{2n\pi x}{L})dx = x\cdot(\frac L{2\pi n})\sin(\frac{2\pi nx}L) + (\frac L{2\pi x})^2\cdot\cos(\frac{2\pi nx}L) $$
$$ a_n = \frac 2L[\cancel{x(\frac L{2\pi n})\sin(\frac{2\pi nx}L)} + (\frac L{2\pi n})^2\cdot\cos(\frac{2\pi nx}L)]|^L_0 $$
$$ a_n = \frac 2L[(\frac{L}{2\pi n})^2\cos(2\pi n) - (\frac L{2\pi n})^2] $$
$$ a_n = 0 $$


$$ b_n = \frac 2L\int_0^Lx\cdot\sin(\frac{2\pi nx}L)dx $$
Recall:
$$ \int x\sin(\frac{2\pi nx}L)dx = -x\frac L{2\pi n}\cos(\frac{2\pi nx}L) + (\frac L{2n\pi})^2\sin(\frac{2n\pi x}) $$
$$ \Rightarrow b_n = \frac2L[-x(\frac L{2\pi n})\cos(\frac {2n\pi x}L) + \cancel{(\frac {L}{2\pi n})^2\cdot\sin(\frac{2\pi nx}L)}] $$
$$ = \frac2L[\frac{-L}{2\pi n}\cos(2\pi n) - 0] $$
$$ = -\frac L{\pi n} $$
Hence:
$$ f(x) = \frac L2 + \sum_{n=1}^{\infty}(-\frac L{\pi n})\sin(\frac{2\pi nx}L), \quad (0,L) $$
