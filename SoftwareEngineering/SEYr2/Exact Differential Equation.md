## Exact Differential Equation
start with a solution f then find a problem for that solution

Solution: $$ f(x,y) = c $$
Problem:
$$ (\frac{\partial f}{\partial x})dx + (\frac{\partial f}{\partial y})dy = 0 $$
DE and it has a solution $f(x,y) = c$

If I have a DE of this form , called an exact differential equation, then i know the solution.

--------------------------------------------------------

U usually get an equation that looks like:
$$ M(x,y)dx + N(x,y)dy = 0 $$
So i ask "Is this DE equation exact?" because if it is exact the solution is:
$$ f(x,y) = c $$
and 
$$ M(x,y) = \frac{\partial f}{\partial x} \qquad N(x, y) = \frac{\partial f}{\partial y} $$
--------------------------------------------------------------------------------------

If both $M(x,y)$ and $N(x,y)$ are continuous and have continuous 1st partial derivatives then the DE is exact if and only if:
$$ \frac{\partial M}{\partial y} = \frac{\partial N}{\partial x} $$
The proof is book and its basically the same steps we use to find $f(x,y)$ anyway

## Making Exact DEs out of Non-Exact DEs
$$ M(x,y)dx + N(x,y)dy = 0 $$
except:
$$ \frac{\partial M}{\partial y} \neq\frac{\partial N}{\partial x} $$
non exact DE

But does some function exist such that 
$$\mu(x,y)M(x,y)dx + \mu(x,y)N(x,y)dy = 0$$
$$ \frac{\partial}{\partial y} (\mu(x,y)M(x,y)) = \frac{\partial}{\partial x}(\mu(x,y)N(x,y)) $$
##### Two cases where $\mu(x)$ is relatively easy

###### Case 1
if $(\frac{\frac{\partial M}{\partial y}-\frac{\partial N}{\partial x}}{N})$ is only a function of x then we can use:
$$ \mu(x) = e^{\int(\frac{\frac{\partial M}{\partial y}-\frac{\partial N}{\partial x}}{N}dx)} $$
##### Case 2
if $(\frac{\frac{\partial N}{\partial x} - \frac{\partial M}{\partial y}}{M})$ is only a function of y then we can use
$$ \mu(y) = e^{\int(\frac{\frac{\partial N}{\partial x} - \frac{\partial M}{\partial y}}{M})dy} $$

#### Examples:
- [[NMM2270.2.4]]