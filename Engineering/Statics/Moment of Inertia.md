##### Note Info
Date: 2022/04/09

## Moment of Inertia
#### [[Normal Stress]]
- It has been found that internal stresses not only depend on the Internal bending moment ([[Internal Forces]]) but also on the [[Moment of Inertia]]
$$ \sigma_x = -\frac{My}{I} $$
- $\sigma_x$ = normal stress a distance y from neutral axis
- M = Internal bending moment
- I = moment of Inertia

- Therefore we want to pick the most optimal cross-sectional area; and hence moment of inertia
- Note: The neutral axis is where the [[Normal Stress]] equals 0 and is located at the centroid of the cross sectional area

#### Moment of Inertia for Areas
![[Pasted image 20220409115108.png]]
$$ I_x = \int_Ay^2dA \qquad I_y = \int_Ax^2dA $$
- $I_x$ = moment of inertia about x axis
- $I_y$ = moment of inertia about y axis

###### About Point O
$$ J_O = \int_A r^2dA = I_x + I_y $$

#### [[Parrallel Axis Theorem]]
- The moment of Inertia for an area is equal to the moment of inertia about a parallel axis through the centroid plus the area times the distance away squared
![[Pasted image 20220409115702.png]]
$$ I_x = \bar{I_x} + Ad_y^2 $$
- $\bar{I_x}$ = moment of inertia about centroidal axis
