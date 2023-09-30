## ECE2277-Quiz-2
### Part 1
Trace the given logic circuit to find the equivalent Boolean function. Please write the function exactly as implemented.
#### Q1
Express the circuit below as Boolean function
![[Pasted image 20221002212849.png]]
$$ f(x,y,z) = (\bar x\cdot\bar y) + z $$
#### Q2
Express the circuit below as a Boolean function
![[Pasted image 20221002213216.png]]
$$ f(x,y,z) = (\bar y + z)\cdot(x+\bar z) $$
### Part 2 Canonical Forms
Express the following Boolean functions in the canonical sum-of-minterms (SOM) or the canonical product-ofmaxterms (POM) form, as indicated.
#### Q1
Express $f (x, y, z) = z + x\bar y$ as a canonical SOM. 
$$  = (\bar x + x)(\bar y + y)z + x\bar y(\bar z + z) $$
$$ = \bar x\bar yz + \bar xyz + x\bar yz + xyz + x\bar y\bar z + x\bar y z$$
$$ =\bar x\bar yz + \bar xyz + x\bar yz + xyz + x\bar y\bar z $$
$$ = (001)+(011)+(101)+(111)+(100) $$
$$ = m_1+m_3+m_5+m_7+m_4 $$
	$$ \sum(1,3,4,5,7) $$
#### Q2
Express $f (x, y, z) = ( x + \bar y + z) (\bar x + \bar z )$ as a canonical POM.
$$ = (x+\bar y+z)(\bar x + \bar z + \bar yy) $$
$$ = (x+\bar y+z)(\bar x+\bar y+\bar z)(\bar x+y+\bar z) $$
$$ = (010)(111)(101) $$
$$ = M_2\cdot M_7\cdot M_5 $$
$$ = \Pi(2,7,5) $$
#### Q3
Express $f (x, y, z) = x \bar y + x \bar z$ as a canonical SOM.
$$ = x\bar y(z+\bar z) + x(y+\bar y)\bar z $$
$$ = (x\bar yz) + (x\bar y\bar z) + (xy\bar z) + (x\bar y\bar z) $$
$$ =   (x\bar yz) + (x\bar y\bar z) + (xy\bar z)  $$
$$ = (101)+(100)+(110) $$
$$ = m_5+m_4+m_6 $$
$$ = \sum(4,5,6) $$
## Part 3 Minimized Standard Form
Use Boolean Algebra to simplify the following canonical forms as much as possible into the standard POS or SOP form as indicated.




### Q1 
Find the lowest cost standard POS equivalent of $f (x, y, z) = M_0 · M_3 · M_7$
Max Terms:
$$ M_0\cdot M_3\cdot M_7 $$
$$ = (0+0+0)(0+1+1)(1+1+1) $$
Min Terms:
$$ m_1+m_2+m_4+m_5+m_6 $$
$$ = (001)+(010)+(100)+(101)+(110) $$
![[Drawing 2022-10-04 14.39.38.excalidraw]]
$$ F = (y\bar z)+(x\bar z)+(\bar yz) $$
or
$$ F = (x+y+z)(\bar x+\bar y) $$
![[Drawing 2022-10-04 15.09.23.excalidraw]]
Cost:
$$ = (6)+(4)+(3) = 13 $$
or
$$ = (5)+(3)+(2)=10 $$
$\therefore$ the answer is $F = (x+y+z)(\bar x+\bar y)$




### Q2
Find the lowest cost standard SOP equivalent of $f (x, y, z) = m_0 + m_1 + m_5 + m_7$
Minterms:
$$ = (000)+(001)+(101)+(111) $$
Maxterms:
$$ = M_2\cdot M_3\cdot M_4\cdot M_6 $$
$$ = (0+1+0)(0+1+1)(1+0+0)(1+1+0) $$
![[Drawing 2022-10-04 15.28.13.excalidraw]]
$$ F = (\bar x\bar y)+(xz) $$
or 
$$ F = (x+\bar y)(\bar x + z) $$
Cost:
$$ = (4)+(3)+(2) = 9 $$
or
$$ = (4)+(3)+(2) = 9 $$
$\therefore$ The answer is $F=(\bar x\bar y)+(xz)$



#### Q3 
Find the lowest cost standard POS equivalent of $f (x, y, z) = M_1 · M_5 · M_6 · M_7$ 
Maxterms:
$$ = (0+0+1)(1+0+1)(1+1+0)(1+1+1) $$
Minterms:
$$ = m_0+m_2+m_3+m_4 $$
$$ = (000)+(010)+(011)+(100) $$
![[Drawing 2022-10-04 15.52.54.excalidraw]]
$$ F = (\bar z\bar y)+(\bar xy) $$
of
$$ F = (\bar x + \bar y)(y+\bar z) $$
Cost:
$$ = (4)+(3)+(2) $$
$$ = (4)+(3)+(2) $$
$\therefore$ the answer is $F = (\bar x+\bar y)(y+\bar z)$
