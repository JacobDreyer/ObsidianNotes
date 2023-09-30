## Higher Order DEs
#### nth Order, Linear, ODE
$$ a_n(x)y^{(n)}(x) + a_{n-1}(x)y^{(n-1)}(x) + \cdots + a_1(x)y^{(1)}(x) + a_0(x)y^{(0)}(x) = F(x) $$
where $a_i$ and $F(x)$ are known functions and y(x) is the unknown function

#### Homogenous
If F(x) = 0 for all x, then the DE is called homogenous

If $F(x) \neq 0$ for all x then this DE is called non-homogenous

![[nth Order Initial Value Problem]]

![[Reduceable Differential Equations]]

## A Look at 2nd Order Homogenous DE
$$ Ay'' + By' + Cy = 0 $$
$A, B, C$ are constants

Lets make a guess: $y(x) = e^{rx}$
$r$ is constant
$$ y(x) = e^{rx}, y'(x)=re^{rx},y''(x)=r^2e^{rx} $$
$$ Ar^2e^{rx}+Bre^{rx}+Ce^{rx} = 0 $$
$$ e^{rx}(Ar^2+Br+C) = 0 $$
$$ e^{rx} \neq 0 $$
$$ (Ar^2+Br+C) = 0 $$
^ is the characteristic Equation for the DE
##### 3 Cases for the roots $r_1$ and $r_2$
1. ==Two distinct real roots==
$$ y_1(x) = e^{r_1x}\quad y_2(x) = e^{r_2x} $$
$y_1(x)$ is linearly independent to $y_2(x)$
2 Solutions
General Solution:
$$ y(x) = C_1y_1(x)+C_2y_2(x) $$
$$ y(x) = C_1e^{r_1x}+C_2e^{r_2x} $$
We are done. This is the solution

2. ==Real Roots but they are the same==
$$ r_1=r_2 $$
Solutions are not linearly independent

For a Second Linearly independent solution:
$$ y_2(x) = xe^{r_2x} = xe^{r_1x} $$
General Solution:
$$ y(x) = C_1e^{r_1x} + C_2xe^{r_1x} $$
Done

3. ==A Pair of Complex Roots==
$$ r_1 = a+ib $$
$$ r_2 = a-ib $$
They are complex conjugates
For a Real Number Solution:
$$ y_1(x) = e^{ax}\cos(bx) $$
$$ y_2(x) = e^{ax}\sin(bx) $$
### Expanding Out to nth Order
##### New Characteristic Equation:
$$ a_nr^n+a_{n-1}r^{n-1}+\cdots+a_1r+a_0=0 $$
n roots

##### 3 Cases for the Roots
1. ==Real Root and Distinct==
$$ r = r_k $$
$$ y_k = e^{r_kx} $$
One of these for each case
2. ==Real Root and Repeated==
$$ r = r_1=r_2=r_k $$
One root repeated k times
So we need k linearly indpendent solutions
$$ y_1(x) = e^{r_1x} $$
$$ y_2(x)=xe^{r_1x} $$
$$ y_3(x) = x^2e^{r_1x} $$
$$ \vdots $$
$$ y_k(x) = x^{k-1}e^{r_1x} $$
3. ==Complex Pairs of Roots==
	- <mark style="background: #ABF7F7A6;">Pair of Distinct Complex Roots</mark>
$$ r = a+ib $$
$$ y_1(x) = e^{ax}\cos(bx) $$
$$ y_2(x) = e^{ax}\sin(bx) $$
		- <mark style="background: #ABF7F7A6;">A Pair of Complex Roots Repeated</mark>
$$ r_1 = a\pm ib - 2\;roots $$
$$ r_2 = a\pm ib - 2\;roots $$
$$ \vdots $$
$$ r_k = a\pm ib - 2\;roots $$
2k roots in total
So we need 2k linearly independent solutions to the DE
$$ = x^pe^{ax}\cos(bx),\quad = x^pe^{ax}\sin(bx) $$
for p=0 to k-1

## Higher Order Non-Homogenous DE
$$ L\;y(x) = f(x) $$
We need Solution to homogenous DE ($y_c$) and Any paticular solution to the non-homogenous DE($y_p$)

#### General Solution
$$ y(x) = y_c(x)+y_p(x) $$
Find $y_c$ then $y_p$

##### Two Methods
1. [[Method of Undetermined Coefficients]]
2. [[Variation of Parameter]]

![[Method of Undetermined Coefficients]]

![[Variation of Parameter]]
