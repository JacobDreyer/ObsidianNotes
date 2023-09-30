 let f(t) be defined for t>0 then the [[Integral]]
$$ \int^{\infty}_0 e^{-st}f(t)dt = \lim_{b\to\infty}\int^b_0e^{-st}f(t)dt \equiv L[f(t)] $$
is called the laplace transofrm of f(t)
$$ L[f(t)] = F(s) $$
becomes a function of s
typically t is time
s has no physical meaning

### Basic Properties of Laplace Transforms
1. The laplace transform is a linear operation
2. Not every f(t) has a L\[f(t)]
3. It is possible to determine if f(t) has a laplace transformation
	- Its difficult
Sufficient Conditions:
- f(t) is piecewise smooth for t >0
- f(t) is of exponential order for t > T where T is some finite value
	- This means that as t -> $\infty$ there must exist non negative constants M,C,T such that 
$$ |f(t)| \leq Me^{Ct} for\; t\geq T $$
	   - we need $e^{-st}f(t)$ to go to zero as t goes to infinity

### Inverse Laplace Transform
$$ L[f(t)] = F(s) $$
$$ L^{-1}[F(s)] = f(t) $$
### Some Examples
##### Constant
$$ f(t) = C $$
$$ L[f(t)] = \frac Cs $$
##### Exponential
$$ f(t) = e^{at} $$
$$ L[f(t)] = L[e^{at}]=\int^\infty_0e^{at}e^{-st}dt $$
$$ = \frac1{s-a}\qquad s>a $$
##### Polynomial
$$ L[t^a] = \int^\infty_0t^ae^{-st}dt = \frac{\Gamma(a+1)}{s^{a+1}} = \frac{a!}{s^{a+1}} $$
[[Gamma Function]]:
$$ \Gamma(n+1)=n! $$
##### cos and sin
$$ L(\cos(kt)) = \int^\infty_0\cos(kt)e^{-st}dt = \frac s{s^2+k^2} $$
$$ L[\sin(kt)] = \frac k{s^2+k^2} $$
### [[Laplace Transform of DE]]
![[Laplace Transform of DE]]

### Translations
$$ s\to s-a $$
$$ L[f(t)] = F(s) $$
$$ L[e^{at}f(t)] = F(s-a) $$
basically solve for F(s) and sub (s-a) in for s

### Finding New Laplace Transforms

### Properties
1. $\lim_{s\to\infty}F(s)=0$ for all F(s) defined by $F(s)=L[f(t)]$ 
2. If $F(s) = L[f(t)]$ and $G(s) = L[g(t)]$ and if $F(s) = G(s)$ for s > c then f(t) = g(t) on \[0,$\infty$) whenever g(t) and f(t) are continuous

#### [[Unit Step Function]]
![[Unit Step Function]]

### More Rules
$$ \frac{d}{ds}F(s) = L[-tf(t)] $$
$$ L[tf(t)] = -\frac{d}{ds}L[f(t)] = -\frac{d}{ds}F(s) = -F'(s) $$In General
$$ L[t^nf(t)] = (-1)^nF^{(n)}(s) $$
#2
$$ f(t) = -\frac1tL^{-1}[\frac{d}{ds}F(s)] $$
#3 Example
$$ L[t\cos(kt)] = -\frac{d}{ds}L[\cos(kt)] $$
#4
The [[Convolution]] of two functions f(t) and g(t) is
$$ (f*g)(t) = \int^t_0f(\tau)g(t-\tau)d\tau $$
$$ L[(f*g)(t)] = L[f(t)]L[g(t)] $$
#5 Integration and Laplace Trasforms
Assume f(t) is continuous and of exponential order for t $\geq$ 0
Assume that $\lim_{t\to 0^+} \frac{f(t)}{t}$ exists

$$ L[\frac{f(t)}{t}] = \int_s^\infty F(\sigma)d\sigma  $$
where $F(s) = L[f(t)]$
$$ f(t) = L^{-1}[F(s)] = tL^{-1}[\int_s^\infty F(\sigma)d\sigma] $$
#6 convolution but g(t) = 1
$$ \frac{F(s)}{s} = L[\int_0^tf(\tau)d\tau] $$

### Laplace Transforms and Periodic Functions
let f(t) be a periodic function with period p and let it be piecewise continuous for t $\geq$ 0 

$$ F(s) = \mathcal L[f(t)]\quad exists\; for\; s>0 $$
$$ F(s) = \frac1{1-e^{-ps}}\int ^p_0e^{-st}f(t)dt $$
