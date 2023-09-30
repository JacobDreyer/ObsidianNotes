## ECE2277 Lab 1 Pre Lab
1. To obtain a Boolean function from a set of minterms or maxterms, 
2. To use to minimize the complexity of that function, 
3. To construct a logic circuit from a Boolean function, 
4. To use simulation tools to verify the correctness of that logic circuit, and 
5. To implement and test the logic circuit in hardware.

Required: 1,2
Strongly Encouraged: 3-5

#### Lab Preparation 
Each student has been assigned a unique 4-variable Boolean expression presented as a canonical sum of minterms (SOM) with 8 terms. The complete list of minterms by student number is included at the end of this lab manual. To prepare for the in-person lab exercise, please derive the minimized standard SOP and POS forms of your given Boolean expression. 

1. Please bring some evidence of your work to the lab for the TA to check. Most of you will probably use a K-map to solve, but if you love manipulating Boolean algebra by hand you can do that too. You can bring in handwritten work, printed work, show the TA work done on a laptop or tablet, or show a digital copy of your work on the lab computer. 
2. Also calculate the cost of the SOP and POS forms to identify which one you should implement in Quartus. You should show this work to the TA as well. 

You must complete this before coming to the lab. As noted, it is also recommended that you complete the Quartus design before attending the lab.

#### My [[Minterms]]
0,1,2,6,8,9,10,11

$0 = (0,0,0,0)$
$1 = (0,0,0,1)$
$2 = (0,0,1,0)$
$6 = (0,1,1,0)$
$8 = (1,0,0,0)$
$9 = (1,0,0,1)$
$10 = (1,0,1,0)$
$11 = (1,0,1,1)$

###### Maxterms
3,4,5,7,12,13,14,15

$$ F = m_0+m_1+m_2+m_6+m_8+m_9+m_{10}+m_{11} $$
$$ F = (\bar w\bar x\bar y\bar z)+(\bar w\bar x\bar yz)+(\bar w\bar xy\bar z)+(\bar wxy\bar z)+(w\bar x\bar y\bar z)+(w\bar x\bar yz)+(w\bar xy\bar z)+(w\bar xyz) $$
#### Minterms
![[Drawing 2022-10-03 20.31.25.excalidraw]]
$$ F = (\bar w\bar x\bar y)+(\bar wy\bar z)+(w\bar x) $$
or
$$ F = (w+\bar y+\bar z)(\bar x+y)(\bar w+\bar x) $$
![[Drawing 2022-10-06 12.54.45.excalidraw]]
Cost:
$$ = (8)+(3)+(4) $$
or:
$$ =(7)+(3)+(4) $$
$\therefore$ The function is $F = (w+\bar y+\bar z)(\bar x+y)(\bar w+\bar x)$

| w   | x   | y   | z   | f   |
| --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 1   |
| 1   | 0   | 0   | 0   | 1   |
| 1   | 1   | 0   | 0   | 0   |
| 1   | 1   | 1   | 0   | 0   |
| 1   | 1   | 1   | 1   | 0   |
| 0   | 1   | 0   | 0   | 0   |
| 0   | 1   | 1   | 0   | 1   |
| 0   | 1   | 1   | 1   | 0   |
| 0   | 0   | 1   | 0   | 1   |
| 0   | 0   | 1   | 1   | 0   |
| 0   | 0   | 0   | 1   | 1   |
| 0   | 1   | 0   | 1   | 0   |
| 1   | 0   | 1   | 0   | 1   |
| 0   | 1   | 1   | 1   | 0   |
| 1   | 0   | 1   | 1   | 1   |
| 1   | 1   | 0   | 1   | 0   |

