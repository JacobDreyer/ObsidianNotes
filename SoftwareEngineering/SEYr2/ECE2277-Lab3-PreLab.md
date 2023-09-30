### Design Logic
##### Accepts:
- Carry-out (Cout)
- Binary Sum (S)
- Operation Control Input (M)

##### Outputs:
- Correction Term(+6 or +0)
	- Type: 4-bit Bus
	- Used to generate correct BCD value
- Control output
	- indicates when a subtraction operation is negative
	- outputs to display "-" or a 1 in the tens place

##### Summary
- When A+B < 10:
	- S = Z
	- HEX0 displays Z
	- HEX1 is blank
- When A+B $\geq$ 10
	- S = Z+6
	- HEX0 displays Z+6
	- HEX1 displays 1
- When A-B and A$\geq$B
	- S = Z
	- HEX0 displays Z
	- HEX1 is blank
- When A-B with A<\B
	- S = Z
	- HEX0 display twos complement
		- ($\bar Z+1$)
			- Can be obtained by 4-bit adder/subtractor calculating 0-Z
		- HEX1 displays -

##### Truth Tables
Correction Term:
Occurs when A+B $\geq$ 10
| k   | Z3  | Z2  | Z1  | Z0  | Z   | CT  |
| --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   | 0   |  0   |
| 0   | 0   | 0   | 0   | 1   | 1   |  0   |
| 0   | 0   | 0   | 1   | 0   | 2   |  0   |
| 0   | 0   | 0   | 1   | 1   | 3   |  0   |
| 0   | 0   | 1   | 0   | 0   | 4   |  0   |
| 0   | 0   | 1   | 0   | 1   | 5   |  0   |
| 0   | 0   | 1   | 1   | 0   | 6   |  0   |
| 0   | 0   | 1   | 1   | 1   | 7   |  0   |
| 0   | 1   | 0   | 0   | 0   | 8   |  0   |
| 0   | 1   | 0   | 0   | 1   | 9   |  0   |
| 0   | 1   | 0   | 1   | 0   | 10  |  6   |
| 0   | 1   | 0   | 1   | 1   | 11  |  6   |
| 0   | 1   | 1   | 0   | 0   | 12  |  6   |
| 0   | 1   | 1   | 0   | 1   | 13  | 6    |
| 0   | 1   | 1   | 1   | 0   | 14  | 6    |
| 0    | 1   | 1   | 1   | 1   | 15  | 6    |
| 1   | x    | x    | x    | x    | Z>15    | 6    |

![[Drawing 2022-11-13 18.52.47.excalidraw]]
$$ f = (z3\cdot z2)+(z1\cdot z3) + k $$
![[Drawing 2022-11-13 19.45.33.excalidraw]]

Control Output = 1:
Occurs When: A+B $\geq$ 10
Same as Correction Term

Control Output = -:
Occurs When: A-B and A<\B

| M   | k   | S             | CO  |
| --- | --- | ------------- | --- |
| 1   | 0   | Z             | 0    |
| 1   | 1   | -($\bar Z$+1) | -   |

if (M and $\bar k$)
	HEX[6] = 1
	CT = 1

![[Drawing 2022-11-13 20.00.46.excalidraw]]

When M = 0 is handled above

### Total Combined Circuit

![[Drawing 2022-11-13 20.07.42.excalidraw]]