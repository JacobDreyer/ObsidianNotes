##### Note Info
Course: [[Engineering]]
Class: [[Calculus]]
Unit: Series
Date: 2022/04/05


## Series
#### [[Sequence]]
- A sequence of numbers
- Usually following a formula

Characterizing Sequences:
- {$a_n$} is bounded from below by L if L < $a_n$ for all n
- {$a_n$} is bounded from above by M if M > $a_n$ for all n
- {$a_n$} is bounded if its bounded from above and below
- {$a_n$} is positive if the lower bound = 0

Convergence:
let {$a_n$} be a sequence defined by $a_n = f(n)$ 
- If $\lim_{n\to\infty} f(n) = L$ the sequence converges to L
- A series is divergent if the limit DNE or L = $\pm \infty$ 

#### [[Infinite Series]]
- Series that has infinite terms

Convergence of a series:
- A series is convergent to the sum S if the sequence of partial sums is convergent to S
$$ s_n = \sum_{i=1}^{n}a_i $$
$$ \lim_{n\to\infty}s_n = S $$
There are also different kinds of Infinite Series
- [[Geometric Series]]
- [[Telescopic Series]]
- [[Harmonic Series]]

###### [[Geometric Series]]
$$ \sum_{n=1}^{\infty}a\cdot r^{n-1} $$
- Coverges when $|r| <1$
- Diverges when $|r| > 1$
- When $|r| < 1$
	- Sum $= \frac{a}{1-r}$

###### [[Harmonic Series]]
$$ \sum_{n=1}^\infty \frac1n $$
- Divergent


- Notes:
	- If if a sequence is convergent. Any sub piece of that sequence is also convergent
	- If a series $\sum_{n=1}^\infty a_n$ converges then $\lim_{n\to\infty} a_n = 0$
		- so in order for a sequence to be convergent then nth term (when $\infty$ is subbed in) must = 0
		- or else you are adding a number inifity times
		- However if the limit does = 0 that doesn't nessecarily mean the series converges

###### [[Telescopic Series]]
$$ \sum_{i=1}^\infty\frac{1}{i(i+1)} = \sum_{i=1}^\infty(\frac1i-\frac1{i+1}) = 1-\frac1{1+n} $$
- this happens because when written out elements cancel out

#### [[Convergence Test]]
###### for [[Positive Series]]
[[Integral Test]]
- pretend our [[Sequence]] is a function $f(n) = a_n$
- if $f(n)$ is [[Continuous]], Positive, and Decreasing
	- then $\sum_{n=1}^\infty a_n$ and $\int_1^\infty f(x)dx$ will both either converge or diverge
	- does not necessarily give the sum

[[Comparison Test]]
- Let $\sum_{n=1}^\infty a_n$ and $\sum_{n=1}^\infty b_n$ such that there is a constant $k$ for which $0 \leq a_n \leq kb_n$ for all $n \geq N$ ($N$ is some integer) then:
	- $\sum_{n=1}^\infty b_n$ convergent $\Longrightarrow$ $\sum_{n=1}^\infty a_n$ convergent
	- $\sum_{n=1}^\infty a_n$ divergent $\Longrightarrow$ $\sum_{n=1}^\infty b_n$ divergent

[[Limit Comparison Test]]
- Let $\sum_{n=1}^\infty a_n$ and $\sum_{n=1}^\infty b_n$ be positive series
$$ \lim_{n\to\infty}\frac{a_n}{b_n}  = L\geq0$$
- If $L<\infty$ and $\sum_{n=1}^\infty b_n$ is convergent $\Longrightarrow$ $\sum_{n=1}^\infty a_n$ is convergent
- if $L>0$ of $L$ is  $\infty$ and $\sum_{n=1}^\infty b_n$ diverges $\Longrightarrow$ $\sum_{n=1}^\infty a_n$ diverges
- if $0<L<\infty$ $\Longrightarrow$ $\sum_{n=1}^\infty a_n$ and $\sum_{n=1}^\infty b_n$ both diverge or both converge

[[Ratio Test]]
- Let $\sum_{n=1}^\infty a_n$ be a positive series
$$ \lim_{n\to\infty} \frac{a_{n+1}}{a_n} = \rho\geq0 $$
- if $0\leq\rho<1$ then $\sum_{n=1}^\infty a_n$ is convergent
- if $\rho>1$ then $\sum_{n=1}^\infty a_n$ diverges
- if $\rho = 1$ test is useless

[[Root Test]]
- Let $\sum_{n=1}^\infty a_n$ be a positive series
$$ \lim_{n\to\infty} a_n^{1/n} = \sigma\geq0 $$
- if $0\leq\sigma<1$ then $\sum_{n=1}^\infty a_n$ is convergent
- if $\sigma > 1$ then $\sum_{n=1}^\infty a_n$ diverges
- if $\sigma = 1$ test is useless

###### Absolute and Conditional Convergence
[[Absolute Convergence]]
- We call a series $\sum_{n=1}^\infty a_n$ absolutely convergent if the series $\sum_{n=1}^\infty |a_n|$  converges
- if the series $\sum_{n=1}^\infty a_n$ coverges absoloutley then $\sum_{n=1}^\infty a_n$ coverges as well

[[Conditional Convergence]]
- We call a series $\sum_{n=1}^\infty a_n$ conditionally convergent if it is convergent but not [[Absolute Convergence]]
- a series $\sum_{n=1}^\infty a_n$ is conditionally covergent if
	- $a_n\cdot a_{n+1} < 0$ for all $n\geq N$ ($N$ is some integer) ($a_n$ is alternating)
	- $|a_{n+1}| \leq |a_n|$ for all $n\geq N$
	- $\lim_{n\to\infty} a_n = 0$

#### [[Power Series]]
$$ \sum_{n=0}^\infty a_n(x-c)^n $$
- $c$ = center of convergence
	- The power series may or may not converge depending on value of x
	- it always converges for ($x = c$)
- $a_n$ = coefficients of power series

One of the following is true:
- Series converges only at x = c
- Series converges for all x
- There is a positive non-zero number $R$ such that ther series is convergent when $|x-c| < R$ and diverges for all x such that $|x-c| > R$


- $R$ = Radius of convergence of power series
- 