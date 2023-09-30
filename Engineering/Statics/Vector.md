##### Note Info
Course: [[Engineering]]
Subject: [[Statics]]
Unit: Vectors
Date: 2022-03-30
## Vectors
- A vector is a quantity that has both a magnitude and a direction
- A [[Unit Vector]] is a vector with any direction and a magnitude of 1
	- Represented by a hat on top of the variable
	- $\hat{i}$  is the unit vector along the x axis, $\hat{j}$ is along the y axis, and $\hat{k}$ is along the z axis
- 2 Vectors are ==equivalent== if they have the same direction and magnitude (initial points don't have to be the same)
- 

#### [[Vector Addition]]
- Done by adding the [[Vector Components]] of the two vectors.
	- Ex. x component of vector 1 plus x component of vector 2
	- Do that for all components

#### Cartesian Vectors in 3D
###### Version 1:
![[Pasted image 20220329231508.png]]
$$ \cos\alpha = \frac{A_x}{A}\qquad \cos\beta = \frac{A_y}{A}\qquad \cos\gamma = \frac{A_z}{A} $$
- $\alpha$ (alpha) is the angle between the vector and the x axis
- $\beta$ (beta) is the angle between the vector and the y axis
- $\gamma$ (gamma) is the angle between the vector and the z axis

###### Version 2:
![[Pasted image 20220330140627.png]]
$$ A_z = A\cos\phi \qquad A' = A\sin\phi $$
$$ A_x = A\sin\phi\cos\theta\qquad A_y = A\sin\phi\sin\theta $$
#### [[Vector Magnitude]]
$$ |F| = \sqrt{F_x^2+F_y^2+F_z^2} $$
The total length/force of the vector

Can also be reffered to as the "norm"

#### [[The Dot Product]]
$$ A\cdot B = |A||B|\cos\theta = A_xB_x + A_yB_y + A_zB_z$$
$\theta$ (theta) = the angle between the two vectors

Can be used to find the component of the vector acting along a specific direction(==The projection==) by doing the dot product of the vector and the unit vector of the direction you want to find.

The magnitude of the component perpindicular the what was found above can be found by:
$$ A_\perp = \sqrt{A^2 - A_{||}^2} $$
The vector form can be found by:
$$ A_\perp = A-A_{||} $$
#### [[The Cross Product]]
$$ C = A\times B = |A||B|\sin\theta $$
The direction of C is perpindicular to the plane that A and B are on. It creates a vector that is perpindicular to both A and B.

The direction can be found using the [[Right Hand Rule]].

Can also be calculated like this:
![[Pasted image 20220330145005.png]]
x component:
![[Pasted image 20220330145109.png]]
$$ = (A_yB_z - B_yA_z)\hat{i} $$
y component:
![[Pasted image 20220330145248.png]]
$$ = (A_zB_x - B_zA_x)\hat{j} $$
$$ = (A_yB_z - B_yA_z)\hat{i} + (A_zB_x - B_zA_x)\hat{j} $$
z component:
![[Pasted image 20220330145443.png]]
$$ = (A_xB_y-B_xA_y)\hat{k} $$
$$ A\times B = (A_yB_z - B_yA_z)\hat{i} + (A_zB_x - B_zA_x)\hat{j} + (A_xB_y-B_xA_y)\hat{k} $$
