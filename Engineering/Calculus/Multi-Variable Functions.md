##### Note Info
Date: 2022/04/17
Course: Engineering
Class: [[Calculus]]
Unit: Multi-Variable Functions
## Multi-Variable Functions
#### [[Limits and Continuity of MV Functions]]
$$ \lim_{(x,y)\to(a,b)} f(x,y) = L $$
- There are inifite # of paths to our point
- To prove continuity we must prove that ALL paths approach the same point
	- Very hard to do
- We can use [[Squeeze Theorem]]
- We can prove when a limit doesn't exist

###### Prove a Limit Doesn't Exist
- Show that 2 paths do not approach the same point

- Restrict one of the variables
	- ex for limit at a point (0,0) set x = 0
- You can then sub that # in and find limit just as y approaches point

- Try $x = 0$ and $y = 0$ first
- Then try other paths ($y = f(x)$, $x = f(y)$)
	- make sure point is along the path
	- make sure degree of numerator and denominator are the same

#### [[Partial Derivative]]
For now we restrict derivatives to x-direction or y-direction

to do this we contain the tangent line in a plane parallel to the x-z plane

==differentiate 1 variable at a time. treat the other(s) as constants==

#### [[Tangent Plane]] and Normal Lines
Normal Line is [[The Cross Product]] between the vector of tangent going in the x direction and the vector of the tangent going in the y direction.

Is the same as the normal line to the Tangent Plane

$$ z = f(a,b) + f_1(a,b)\cdot(x-a)+f_2(a,b)\cdot(y-b) $$
- $f_1(a,b)$ = [[Partial Derivative]] of x (y constant)(sub in a and b)
- $f_2(a,b)$ = [[Partial Derivative]] of y (x constant)(sub in a and b)

#### [[Higher Order Derivatives]]
- Same as for single variable fuction there are just more options
- For example you can differentiate with regards to x and then differentiate that with regards to y
$$ f(x,y)\to\frac{\partial f}{\partial x}\to\frac{\partial^2 f}{\partial x^2}\to\frac{\partial^3 f}{\partial y\;\partial x^2} $$
- Note $\partial y$ goes out front. you add each partial to the front 
- Next Form is nicer/more intuitive
$$ f(x,y)\to f_{x}\to f_{xx}\to f_{xxy} $$

#### [[Chain Rule]]
- let $z = f(x(s,t), \;y(s,t))$ 
$$ \frac{\partial z}{\partial s} = \frac{\partial z}{\partial x}\cdot\frac{\partial x}{\partial s}+\frac{\partial z}{\partial y}\cdot\frac{\partial y}{\partial s} $$
- Answer will have x and y still so sub in $x(s,t)$ and $y(s,t)$

- Second Method
	- Sub in formula for x and y and do normal partial derivatives

