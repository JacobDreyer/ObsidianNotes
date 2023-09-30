### 1 Implementing Boolean Functions with a Decoder
Identify which of the given Boolean functions is implemented in the circuit diagram shown
1. The circuit diagram is shown below. The 3-to-8 decoder chip outputs are active-high. You may assume it is always enabled.
![[Pasted image 20221106170536.png]]
| x   | y   | z   | #   | f   | f1  | f2  | f3  | f4  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 1   | 0   | 1   | 0   | 1    |
| 0   | 0   | 1   | 1   | 0   |     | 0   |     | 0    |
| 0   | 1   | 0   | 2   | 0   |     | 0   |     | 0    |
| 0   | 1   | 1   | 3   | 0   |     | 0   |     | 0    |
| 1   | 0   | 0   | 4   | 1   |     | 1   |     | 1    |
| 1   | 0   | 1   | 5   | 0   |     | 1   |     | 0    |
| 1   | 1   | 0   | 6   | 1   |     |     |     | 1    |
| 1   | 1   | 1   | 7   | 1   |     |     |     | 1    |
$\therefore$ the answer is f4

2. The circuit diagram is shown below. The 3-to-8 decoder chip is active low. You may assume it is always enabled.
![[Pasted image 20221106170657.png]]
| x   | y   | z   | #   | f   | f1  | f2  | f3  | f4  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 1   | 1   | 0   | 1   | 1    |
| 0   | 0   | 1   | 1   | 1   | 0   |     | 1   | 1    |
| 0   | 1   | 0   | 2   | 0   |     |     | 0   | 0    |
| 0   | 1   | 1   | 3   | 1   |     |     | 1   | 1    |
| 1   | 0   | 0   | 4   | 0   |     |     | 0   | 0    |
| 1   | 0   | 1   | 5   | 0   |     |     | 0   | 1    |
| 1   | 1   | 0   | 6   | 1   |     |     | 1   |     |
| 1   | 1   | 1   | 7   | 1   |     |     | 1   |     |
$\therefore$ the answer is f3

### 2 Implementing Boolean Functions with a Multiplexer
Use the following 4 × 1 multiplexer circuit to implement the given Boolean functions by setting the data inputs D 0 , D 1 , D 2, and D 3 to the appropriate input from z , z 0 , 1, or 0 .
![[Pasted image 20221106170803.png]]
1. Implement the function f (x, y, z) = ¯x y¯ + ¯z in the circuit shown above, by identifying what connects to D0 , D1 , D2, and D3 .
| x   | y   | z   | f   | x+y |
| --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 1   | 0    |
| 0   | 0   | 1   | 1   | 0    |
| 0   | 1   | 0   | 1   | 1    |
| 0   | 1   | 1   | 0   | 1    |
| 1   | 0   | 0   | 1   | 2    |
| 1   | 0   | 1   | 0   | 2    |
| 1   | 1   | 0   | 1   | 3    |
| 1   | 1   | 1   | 0   | 3    |
D0 = 1
D1 = $\bar z$
D2 = $\bar z$
D3 = $\bar z$

2. Implement the function f (x, y, z) = ( x + z) (¯x + y + ¯z ) in the circuit shown above, by identifying what connects to D0 , D1 , D2, and D3 .
| x   | y   | z   | x+y | f   |
| --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   |
| 0   | 0   | 1   | 0   | 1   |
| 0   | 1   | 0   | 1   | 0   |
| 0   | 1   | 1   | 1   | 1   |
| 1   | 0   | 0   | 2   | 1   |
| 1   | 0   | 1   | 2   | 0   |
| 1   | 1   | 0   | 3   | 1   |
| 1   | 1   | 1   | 3   | 1    |
D0 = z
D1 = z
D2 = $\bar z$
D3 = 1

3. Implement the function f (x, y, z) = ¯yz + x in the circuit shown above, by identifying what connects to D0 , D1 , D2, and D3 .
| x   | y   | z   | x+y | f   |
| --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   |
| 0   | 0   | 1   | 0   | 1   |
| 0   | 1   | 0   | 1   | 0   |
| 0   | 1   | 1   | 1   | 0   |
| 1   | 0   | 0   | 2   | 1   |
| 1   | 0   | 1   | 2   | 1   |
| 1   | 1   | 0   | 3   | 1   |
| 1   | 1   | 1   | 3   | 1    |
D0 = z
D1 = 0
D2 = 1
D3 = 1

4. Implement the function f (x, y, z) = ( x + ¯z) (¯x + ¯y + z ) in the circuit shown above, by identifying what connects to D0 , D1 , D2, and D3.
| x   | y   | z   | x+y | f   |
| --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 1   |
| 0   | 0   | 1   | 0   | 0   |
| 0   | 1   | 0   | 1   | 1   |
| 0   | 1   | 1   | 1   | 0   |
| 1   | 0   | 0   | 2   | 1   |
| 1   | 0   | 1   | 2   | 1   |
| 1   | 1   | 0   | 3   | 0   |
| 1   | 1   | 1   | 3   | 1    |
D0 = $\bar z$
D1 = $\bar z$
D2 = 1
D3 = z

### 3 Analyzing Multiplexor Circuits
Determine the Boolean functions implemented with the following multiplexer circuits. Express the answer in canonical form, as requested
1. Analyze the following circuit, and express f (x, y, z ) as a POM.
![[Pasted image 20221106171012.png]]
| x   | y   | z   | f   |
| --- | --- | --- | --- |
| 0   | 0   | 0   | 1    |
| 0   | 0   | 1   | 1    |
| 0   | 1   | 0   | 1    |
| 0   | 1   | 1   | 0    |
| 1   | 0   | 0   | 1    |
| 1   | 0   | 1   | 1    |
| 1   | 1   | 0   | 0    |
| 1   | 1   | 1    | 0    |
![[Drawing 2022-11-06 19.55.53.excalidraw]]
$$ f = (\bar y+\bar z)(\bar x+\bar y) $$

2. Analyze the following circuit, and express f (x, y, z ) as a POM.
![[Pasted image 20221106171033.png]]
| x   | y   | z   | f   |
| --- | --- | --- | --- |
| 0   | 0   | 0   | 1    |
| 0   | 0   | 1   | 1    |
| 0   | 1   | 0   | 1    |
| 0   | 1   | 1   | 1    |
| 1   | 0   | 0   | 0    |
| 1   | 0   | 1   | 0    |
| 1   | 1   | 0   | 0    |
| 1   | 1   | 1    | 1    |
![[Drawing 2022-11-06 20.04.57.excalidraw]]
$$ f = (\bar x+y)(\bar x+z) $$

3. Analyze the following circuit, and express f (x, y, z ) as a SOM.
![[Pasted image 20221106171104.png]]
| x   | y   | z   | f   |
| --- | --- | --- | --- |
| 0   | 0   | 0   | 0    |
| 0   | 0   | 1   | 0    |
| 0   | 1   | 0   | 1    |
| 0   | 1   | 1   | 0    |
| 1   | 0   | 0   | 1    |
| 1   | 0   | 1   | 1    |
| 1   | 1   | 0   | 1    |
| 1   | 1   | 1    | 0    |
![[Drawing 2022-11-06 20.09.34.excalidraw]]
$$ f = x\bar y + y\bar z $$
