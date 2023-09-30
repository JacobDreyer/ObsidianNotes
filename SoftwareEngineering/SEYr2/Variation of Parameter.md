$$ Ly(x) = f(x) $$
We know:
$$ y_c(x) = C_1y_1+C_2y_2+\cdots+C_ny_n $$
Make the assumption that we can use $y_p(x) = u_1(x)y_1(x) + u_2(x)y_2(x)+\cdots+u_n(x)y_n(x)$

So we introduce $u_1(x), u_2(x),\cdots, u_n(x)$ 

There is always a solution $y_p$ of this form

We have n-1 degrees of freedom here
We need to use one to say that $y_p$ solves the DE

#### 2nd Oder 1st
$$ Ly(x) = f(x) $$
$$ y''(x)+P(x)y'(x)+Q(x)y(x) = f(x) $$
Assume we found the solution to the associated homogenous DE
$$ y_c(x) = C_1y_1+C_2y_2 $$
so $y_1(x)$ and $y_2(x)$ are known functions
$$ Ly_1(x) = 0\qquad Ly_2(x)=0 $$
Now Assume we define $y_p(x)$ 
$$ y_p(x) = u_1(x)y_1(x)+u_2(x)y_2(x) $$
$$ y_p'(x) = u_1(x)y_1'(x)+u_1'(x)y_1(x)+u_2(x)y_2'(x)+u_2'(x)y_2(x) $$
We have 2 degrees of freedom. 2 Equations:
1. Demand that $y_p$ solve the DE
2. $u_1'(x)y_1(x) + u_2'(x)y_2(x) = 0$
	1. We will use later

$$ y_p'(x) = u_1(x)y_1'(x) + u_2(x)y_2'(x) $$
$$ y_p''(x) = u_1(x)y''_1(x) + u_1'(x)y_1'(x)+u_2(x)y_2''(x)+u_2'(x)y_w'(x) $$
Third Order: Repeat a Third Time

Recall: $y_1''+Py_1'+Qy_1 = 0$,     and     $y_2''+Py_2'+Qy_2 = 0$
$$ y_1'' = -(Py_1'+Qy_1) $$
$$ y_2'' = -(Py_2'+Qy_2) $$
Sub these into $y_p''$
$$ y_p''(x) = (u_1'y_1'+u_2'y_2')-P(u_1y_1'+u_2y_2')-Q(u_1y_1+u_2y_2) $$
$(u_1y_1'+u_2y_2') = y_p'$
$(u_1y_1+u_2y_2) = y_p$
$$ y_p''(x) = (u_1'y_1'+u_2'y_2')-Py_p'-Qy_p $$
Finally
$$ Ly_p = y''_p+Py_p'+Qy_p = f(x) $$
$$ = ((u_1'y_1'+u_2'y_2')\cancel{-Py_p'}\cancel{-Qy_p})+\cancel{Py_p'}+\cancel{Qy_p} $$
$$ = (u_1'y_1'+u_2'y_2') = f(x) $$
The Two Equations:
$$ (u_1'y_1'+u_2'y_2') = f(x) $$
$$ u_1'y_1 + u_2'y_2 = 0 $$
We can use these two equations to solve for u1 and u2
$$ u_1' = \frac{-y_2f(x)}{W}\qquad u_2' = \frac{y_1f(x)}{W} $$
W is [[Determinate]] of matrix:
$$ 
\begin{pmatrix}
y_1 & y_2 \\
y_1' & y_2'
\end{pmatrix}
$$
$$ W = y_1y_2' - y_2y_1' $$
==Solution:==
$$ y_p(x) = u_1(x)y_1(x)+u_2(x)y_2(x) $$
$$ y_p(x) = (\int u_1'(x))dxy_1(x)+(\int u_2'(x)dx)y_2(x) $$
$$ y_p(x) = \int\frac{-y_2(x)f(x)}{W}dx\cdot y_1(x) + \int\frac{y_1(x)f(x)}{W}dx\cdot y_2(x) $$
