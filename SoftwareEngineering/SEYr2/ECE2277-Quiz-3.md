# ECE 2277 Quiz 3
## Q1: Canonical Functions From Karnaugh Maps
#### Part A 
Express Karnaugh map (a) as a canonical SOM.
![[Drawing 2022-10-12 16.19.19.excalidraw]]
$$ F = (0001)+(0011)+(0010)+(0110)+(1110)+(1001) $$
$$ F = m_1+m_3+m_2+m_6+m_{14}+m_9 $$
#### Part B
Express Karnaugh map (b) as a canonical POM
![[Drawing 2022-10-12 16.33.33.excalidraw]]
$$ F = (0+0+0+0)(0+0+0+1)(0+1+0+0)(0+1+0+1)(1+1+1+0)(1+0+1+1) $$
$$ F = M_0\cdot M_1\cdot M_4\cdot M_5\cdot M_{14}\cdot M_{11} $$
## Q2: Karnaugh Maps from Boolean Functions
Write the Karnaugh map for the given Boolean function.

#### Part A
Write the Karnaugh map for $f(w,x,y,z) = wx+xyz+x\bar y\bar z$
![[Drawing 2022-10-12 16.59.49.excalidraw]]
$$ f= wx+xyz+x\bar y\bar z $$
$$ f= wx(y+\bar y)(z+\bar z) + (w+\bar w)xyz + (w+\bar w)x\bar y\bar z $$
$$ f = wxyz+wx\bar yz+wxy\bar z+wx\bar y\bar z + wxyz+\bar wxyz + wx\bar y\bar z + \bar wx\bar y\bar z $$
$$ f = (1111)+(1101)+(1110)+(1100)+(0111)+(0100) $$
![[Drawing 2022-10-12 17.14.14.excalidraw]]
#### Part B
Write the Karnaugh map for 
$f(w,x,y,z) = (w+x+\bar z)(w+y+z)(\bar x+\bar y+\bar z)$
![[Drawing 2022-10-12 17.20.46.excalidraw]]
## Q3 Simplified Standard Functions from Karnaugh Maps
Use a Karnaugh map to find the lowest-cost standard form for the given canonical function and set of don’t-cares. The lowest-cost standard form may be a sum of products (SOP) or a product of sums (POS) — i.e., of the two options, pick the one that has the lowest cost. If they both have the same cost, please choose the SOP form.

#### Part A
Find the lowest-cost standard form of $f(w,x,y,z) = \sum(0,2,4,10,11,12)$, with don't cares $d(w,x,y,z) = \sum(7,13,14)$
$$ f = (0000)+(0010)+(0100)+(1010)+(1011)+(1100) $$
$$ d = (0111)+(1101)+(1110) $$
![[Drawing 2022-10-12 20.52.41.excalidraw]]
![[Drawing 2022-10-12 21.16.49.excalidraw]]
$$ c = (9)+(4)+(3)\qquad\qquad c = (11)+(5)+(4) $$
$\therefore f = (x\bar y\bar z)+(\bar w\bar x\bar z)+(w\bar xy)$

#### Part B
Find the lowest-cost standard form of $f(w,x,y,z) = \Pi(0,1,9,11,12,14)$ with don't cares $d(w,x,y,z) = \sum(2,7,15)$
$$ f = (0000)(0001)(1001)(1011)(1100)(1110) $$
$$ d = (0010)+(0111)+(1111) $$
![[Drawing 2022-10-12 22.09.39.excalidraw]]
$$ c = (9)+(4)+(3) = 16 $$
#### Part C
Find the lowest-cost standard form of $f(w,x,y,z) = \Pi(0,4,6,12,13,14)$ with don't cares $d(w,x,y,z) = \sum (3,8,11)$
$$ f = (0000)(0100)(0110)(1100)(1101)(1110) $$
$$ d = (0011)+(1000)+(1011) $$
![[Drawing 2022-10-12 23.04.30.excalidraw]]
![[Drawing 2022-10-13 09.39.33.excalidraw]]
$$ c = (8)+(4)+(3)=15\qquad\qquad c = (9)+(5)+(4)= 18 $$
$\therefore f = (\bar w+\bar x+y)(y+z)(\bar x+\bar y+z)$
