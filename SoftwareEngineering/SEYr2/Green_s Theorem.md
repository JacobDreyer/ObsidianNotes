going to relate a line integral around a piecewise smooth simple closed curve C, to a double integral over the region R bounded by that curve.

#### Green's Theorem in the Plane
C is a piecewise smooth simple closed curve bounded by a simply connnected region R. If $P(x,y)$, $Q(x,y)$, $\frac{\partial P}{\partial y}$, and $\frac{\partial Q}{\partial x}$ are continuous on R,
$$ \oint[P(x,y)dx + Q(x,y)dy] = \iint_R (\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y})dA $$
![[Pasted image 20230211114317.png]]

#### Green's Theorem and a Region with a Hole
This may seem to be pointless and with no application, but there are circumstances where it can really help.

![[Pasted image 20230211114553.png]]

- Earlier we said we traverse C "Positively" when we are moving counterclockwise
- But more correctly/generally, we traverse C as $C^+$ when R is to the left of curve C when following C
- So in the above case, walking around $C_1$, we also have R to the left
- Also walking around $C_2$, we also have R to the left
- So the total curve $C = C_1\cup C_2$ is positive

### Practice Problems
[[NMM2276.9.12]]
