##### Note Info
Created to describe how the original mathmaticians were able to derive a way to complete the cube
Based off: [[Video; How Imaginary Numbers Were Invented]] by [[Veritasium]]
Date: 2022-03-30
## Completing the Cube
#### Original Derivation Based on Shapes
Consider: $x^3 + 9x = 26$

$x^3$ can be represented by a cube with sides of length x. 
Add a volume of 9x and you get 26.

extend the $x^3$ cube by y and you get a cube of side length z where z = x + y

The original cube has been padded out and can be broken into 7 shapes

3 rectangles of size $x^2y$ 
3 rectangles of size $xy^2$
1 cube of volume $y^3$

The prisms can be rearranged into 1 block of size 3yzx (keep in mind z = x+y)

if the base of the cube equals 9 then this can represent 9x. So 3yz = 9

However we are still missing the cube of $y^3$ so we add it to both sides of the equation which becomes
$$ x^3+9x+y^3=26+y^3 $$
$$ (x^3 + 9x + y^3) = z^3 $$
$$ 3yz = 9 \rightarrow z=\frac{3}{y}  $$
$$ y^3 + 26 = \frac{27}{y^3} $$
$$ y^6 + 26y^3 = 27 = (y^3)^2 + 26(y^3) $$
This is now a quadratic which can be solved using [[Completing the Square]]
using this and the other equations we found y = 1, z = 3, ==x = 2==

