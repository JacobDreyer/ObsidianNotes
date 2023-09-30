## Part 1
Quick question: Does the following ripple counter count up or down?
![[Pasted image 20221121225734.png]]
up: I think bc Q' feeds into D whereas if Q feeds in its down. idk really know tho

## Part 2
Design a counter that count from zero up to 13 and then clears 0 using the asynchronous reset and counts up again (this repeats forever). You may assume the counter is initialized with a count of zero. The basic counter is shown below.

![[Pasted image 20221121231001.png]]

The inputs Ld , Up, and Dn are all active-high, Up takes priority over Dn, and Ld takes priority over both. The asynchronous reset “rst” has the highest priority, and is active-low. The inputs In indicate the parallel load value, the outputs A n indicate the current count, and the output W indicates when the count wraps around. Provide the logic expressions for the inputs Ld , U p , Dn, rst, and all In in terms of the outputs An , W, and the constants 0 and 1 to realize an up counter that counts to 13 and then clears 0 using the asynchronous reset and counts up again. If any input is irrelevant it can be left blank or written as x for “don’t care”.

| Input | Logic Expression                 |
| ----- | -------------------------------- |
| rst   | $\bar A_3+\bar A_2+\bar A_1$ |
| Ld    | 0                                |
| Up    | 1                                |
| Dn    | x                                |
| $I_3$ | x                                |
| $I_2$ | x                                |
| $I_1$ | x                                |
| $I_0$ | x                                |

| $A_3$ | $A_2$ | $A_1$ | $A_0$ | rst |
| ----- | ----- | ----- | ----- | --- |
| 1     | 1     | 1     | 0     | 0   |
| 1     | 1     | 1     | 1     | x    |

![[Drawing 2022-11-22 22.07.33.excalidraw]]

## Part 3
Design a counter that counts from 14 down to 6, the resets back to 14 and repeats. You may assume the counter is initialized with a count of 14. The basic counter is shown below

![[Pasted image 20221122221432.png]]

The inputs Ld , U p, and Dn are all active-high, U p takes priority over Dn, and Ld takes priority over both. The asynchronous reset “rst” has the highest priority, and is active-low. The inputs In indicate the parallel load value, the outputs A n indicate the current count, and the output W indicates when the count wraps around. Provide the logic expressions for the inputs Ld , U p , Dn, rst, and all In in terms of the outputs A n , W, and the constants 0 and 1 to realize an counter that counts from 14 down to 6 and then repeats. If any input is irrelevant it can be left blank or written as x for “don’t care”

| Input | Logic Expression |
| ----- | ---------------- |
| rst   | 1                |
| Ld    | $\bar A_3A_1\bar A_0$                 |
| Up    | 0                |
| Dn    | 1                |
| $I_3$ | 1                |
| $I_2$ | 1                |
| $I_1$ | 1                |
| $I_0$ | 0                 |

| $A_3$ | $A_2$ | $A_1$ | $A_0$ | Ld  |
| ----- | ----- | ----- | ----- | --- |
| 0     | 1     | 1     | 0     | 1   |
| 1     | 1     | 1     | 1     | x   |
| 0     | 0     | 0     | 0     | x   |
| 0     | 0     | 0     | 1     | x   |
| 0     | 0     | 1     | 0     | x   |
| 0     | 0     | 1     | 1     | x   |
| 0     | 1     | 0     | 0     | x   |
| 0     | 1     | 0     | 1     | x    |

![[Drawing 2022-11-22 22.24.09.excalidraw]]