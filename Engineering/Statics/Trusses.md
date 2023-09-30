##### Note Info
Course: [[Engineering]]
Class: [[Statics]]
Unit: Trusses
Date: 2022/03/31

## Trusses
A truss is a structure composed of straight slender members connected/joined (pinned, nailed, riveted, bolted or welded) together at their end points.

The loads are transmitted to the truss as point loads at the locations of the joints. Because the forces are only located at the joints; the members of the truss behave as [[Two-Force Members]].

Tension member:
- The member acts in tension
![[Pasted image 20220331082407.png]]

Compression member:
- The member is being compressed
![[Pasted image 20220331082440.png]]

#### [[Method of Joints]]
- each joint is in equilibrium so we can use the [[equilibrium equations]] to determine the forces acting on the joints
- $\sum M = 0$ is automatically satisfied. We only need to use $\sum F_x = 0$ and $\sum F_y = 0$

 ###### Procedure
 - Draw [[Free Body Diagrams]] for the joints (and entire system if you want)
 - Pick a FBD having at least 1 known force and at most 2 unknowns
 - Apply equilibrium equations
 - Remember a tension member pulls on a joint and a compression member pushes on a joint
 - Move to the next joint

#### [[Zero Force Members]]
- Zero force members are members which support no load
- Can be found:
	- if 2 members form a joint where there is no external load or support reactions then both are zero force members
	- If 3 members form a joint and 2 of the members are collinear and there is no external load or support reactions then the third member is a zero force member

#### [[Method of Sections]]
- Used to find internal forces of a system similarly to [[Method of Joints]]
- "Slice" the system along the members you want to find (max of 3)
- draw a [[Free Body Diagrams]] for a piece.
- Apply the Equilibrium equations to solve for the unknown forces
$$ \sum F_x = 0 \qquad \sum F_y = 0 \qquad \sum M = 0 $$
![[Pasted image 20220331084854.png]]

- When solving the [[Equilibrium Equations]], remember to start with moments about a point that lies at the intersection of the lines of action of two of the unknown truss member forces which will yield a direct result for the third unknown force

