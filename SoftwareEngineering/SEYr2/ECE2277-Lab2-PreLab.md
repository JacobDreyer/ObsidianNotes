To prepare for the in-person lab exercise, derive the logic circuit that determines whether or not a 4-bit code is a valid BCD value.
1. The 4-bit input is assigned the variables w, x, y, z, where w is the most significant and z is the least significant bits. Therefore, (w, x, y, z) = (1, 0, 0, 0) is $8_{BCD}$, and (w, x, y, z) = (0, 0, 0, 1) is $1_{BCD}$.
2. The logic output is f(w, x, y, z) = 1 if the sequence (w, x, y, z) is a invalid BCD value, and f(w, x, y, z) = 0 if the sequence (w, x, y, z) is a valid BCD value.
![[Drawing 2022-10-18 22.18.19.excalidraw]]
![[Drawing 2022-10-18 22.32.00.excalidraw]]
$$ c = (3)+(2)+(1)=6\qquad c = (4)+(3)+(2)=9 $$
| w   | x   | y   | z   | $w(x+y)$ | desired | Number |
| --- | --- | --- | --- | -------- | ------- | ------ |
| 0   | 0   | 0   | 0   | 0        | 0       | 0       |
| 0   | 0   | 0   | 1   | 0        | 0       | 1       |
| 0   | 0   | 1   | 0   | 0        | 0       | 2       |
| 0   | 0   | 1   | 1   | 0        | 0       | 3       |
| 0   | 1   | 0   | 0   | 0        | 0       | 4       |
| 0   | 1   | 0   | 1   | 0        | 0       | 5       |
| 0   | 1   | 1   | 0   | 0        | 0       | 6       |
| 0   | 1   | 1   | 1   | 0        | 0       | 7       |
| 1   | 0   | 0   | 1   | 0        | 0       | 9       |
| 1   | 0   | 1   | 0   | 1        | 1       | 10       |
| 1   | 0   | 1   | 1   | 1        | 1       | 11       |
| 1   | 1   | 0   | 0   | 1        | 1       | 12       |
| 1   | 1   | 0   | 1   | 1        | 1       | 13       |
| 1   | 1   | 1   | 0   | 1        | 1       | 14       |
| 1   | 1   | 1   | 1   | 1        | 1       | 15       |


