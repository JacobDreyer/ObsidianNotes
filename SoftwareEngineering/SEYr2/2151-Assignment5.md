## 1 Computation Exercises
##### 1.1
Find a binary linear code $C\subseteq\mathbb F_2^2$ with 2 elements
$$ C = \{(0,0),(1,1)\} $$
##### 1.2
Find a binary linear code $C\subseteq\mathbb F_2^5$ with 4 elements
$$ C = \{(0,0,0,0),(1,1,1,1),(0,0,1,1),(1,1,0,0)\} $$
##### 1.3
find a binary linear code $C\subseteq\mathbb F_2^8$ with $2^6$ elements. Your solution should be its generator matrix
$n=8$
$k= 6$

$$ G =
\begin{pmatrix}
1&0&0&0&0&0&0&0 \\
0&1&0&0&0&0&0&0 \\
0&0&1&0&0&0&0&0 \\
0&0&0&1&0&0&0&0 \\
0&0&0&0&1&0&0&0 \\
0&0&0&0&0&1&0&0 \\
\end{pmatrix}
$$
##### 1.4
Write down a [[Pseudo-Code]] algorithm that determines the hamming weight of a binary linear code C when its input is a generator matrix

```pseudo-code
//find codes:
change 0 to (# of rows in matrix)^2 to binary numbers
create array to store the sets of bits

do array multiplication of set of bits against matrix
store the new sets of bits in array2

//find weight
initialize counter with 0
initialize minWeight with # of bits in a set
loop i over array2
	loop j from i to end of array2
		loop k over # of bits
			if (array2[i] at bit k) + (array1[j] at bit k) is not a 
             multiple of 2
				increment counter by 1
	if counter is less than minWeight and does not equal 0
		minWeight becomes counter
	reset counter to 0

return winWeight
```

## 2 The Size of Binary Linear Code

![[Pasted image 20221129210312.png]]
![[Pasted image 20221129210352.png]]
![[Pasted image 20221129210506.png]]

## 3 Theory
##### 3.1.a
$$ d(\vec x, \vec x) = 0 $$
$$ d(\vec x, \vec x) = (x_1 + x_1)\mod 2 + \cdots (x_n+x_n)\mod 2 $$
$$ d(\vec x, \vec x) = (2x_i)\mod 2 $$
$2x_i$ is an even # (follows 2k)
Any even number divided 2 has a remainder of 0 so
$$ d(\vec x, \vec x) = 0+0+\cdots+0 = 0 $$
##### 3.1.b
$$ d(\vec x, \vec y) = d(\vec y, \vec x) $$
$$ (x_i + y_i)\mod 2 = (y_i + x_i)\mod 2 $$
$$ x_i+y_i = y_i+x_i $$
because order of addition does not matter these two are equal

##### 3.1.c
$$ d(\vec x, \vec y) \leq d(\vec x, \vec z) + d(\vec z, \vec y) $$
Let k be some + number
$$ (x_i + y_i)\mod 2 = (x_i+z_i)\mod 2 + (y_i + z_i)\mod 2 + k $$
x and y are the same:
assume $x_i = 1, \; y_i = 1 \; z_i = 1$
$$ 0 = 0+0 $$
assume $x_i = 1, \; y_i = 1 \; z_i = 0$
$$ 0 \leq 1+1 $$
x any y are different:
assume $x_i = 0, \; y_i = 1 \; z_i = 1$
$$ 1 \leq 1+0 $$
assume $x_i = 0, \; y_i = 1 \; z_i = 0$
$$ 1 \leq 0+1 $$

$\therefore$ for all possible combinations the statement holds

##### 3.2.a
because according to the theorem. If code C is t-error decoding then $\forall\vec w\in\mathbb F_2^n$
there is a ==unique== $\vec c\in C$ where $d(\vec c, \vec w)$ is less than or equal to t

so $d(\vec c_2, \vec w)$ must be greater than t so its greater than or equal to t+1 (because $c_i$ and $w_i$ are 0 or 1, no decimals)
$$ d(\vec c_1, \vec w) \leq t < d(\vec c_2,\vec w) $$
$$ d(\vec c_2, \vec w) \geq t+1 $$
by 3.1.c
$$ 2t+1 \leq d(\vec c_1, \vec c_2) \leq d(\vec c_1, \vec w) + d(\vec c_2, \vec w) $$
by 3.2.a
$$ t+(t+1)\leq d(\vec c_1, c_2)\leq d(\vec c_1, \vec w) + (t+1) $$
we know $d(\vec c_1, \vec w)\leq t$. this means in order for it to fit above it must equal t
$$ 2t+1\leq d(\vec c_1, \vec c_2) \leq 2t+1 $$
$$ d(\vec c_1, \vec c_2) = 2t+1 $$
so C is t error correcting
