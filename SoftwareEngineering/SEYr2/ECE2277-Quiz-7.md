### 1
d.  a mealy type FSM

### 2
11110110

### 3
| Q(t) | x   | Q(t+1) | Output y |
| ---- | --- | ------ | -------- |
| 0    | 0   | 0      | 1        |
| 0    | 1   | 1      | 1        |
| 1    | 0   | 1      | 1        |
| 1    | 1   | 0      | 0         |

### 4
Implementation with D flip flops
| Q(t) | x   | Q(t+1) | Output y | Excitation (naxt val into D) |
	| ---- | --- | ------ | -------- | ---------------------------- |
	| 0    | 0   | 0      | 1        | 0                            |
	| 0    | 1   | 1      | 1        | 1                            |
	| 1    | 0   | 1      | 1        | 1                            |
	| 1    | 1   | 0      | 0        | 0                            |
![[Drawing 2022-12-07 20.18.18.excalidraw]]
$$ Q(t+1) = Q(t)x' + Q(t)'x $$
$$ y = Q(t)'+x' $$
### 5
Implementation with T Flip Flops
| Q(t) | x   | Q(t+1) | Output y | Excitation (naxt val into T) |
| ---- | --- | ------ | -------- | ---------------------------- |
| 0    | 0   | 0      | 1        | 0                            |
| 0    | 1   | 1      | 1        | 1                            |
| 1    | 0   | 1      | 1        | 0                            |
| 1    | 1   | 0      | 0        | 1                            |
![[Drawing 2022-12-07 20.50.22.excalidraw]]
$$ T = x $$
### 6
Implementation with JK flip flops
| Q(t) | x   | Q(t+1) | Output y | Excitation (naxt val into J) | K   |
| ---- | --- | ------ | -------- | ---------------------------- | --- |
| 0    | 0   | 0      | 1        | 0                            | 1   |
| 0    | 1   | 1      | 1        | 1                            | 0   |
| 1    | 0   | 1      | 1        | 1                            | 0   |
| 1    | 1   | 0      | 0        | 0                            | 1   |
![[Drawing 2022-12-08 08.57.47.excalidraw]]
$$ J = Q(t)x' + Q(t)'x $$
$$ K = Q(t)'x' + Q(t)x $$
