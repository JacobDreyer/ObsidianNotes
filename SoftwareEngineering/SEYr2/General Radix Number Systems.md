## General Radix Number Systems
Continuation of [[Decimal Number System]]

In general any radix or base can be used
The number X in radix r is represented by:
$$ (x_{k-1}x_{k-2}\cdots x_1x_0\quad .\quad x_{-1}x_{-2}\cdots x_{-m})_r  = a_{k-1}\times r^{k-1} + a_{k-2}\times r^{k-2} + a_{-m}\times r^{-m}$$
- . : the radix point distinguishes positive powers of r from negative powers or r
- $x_{-m}$ is called the LSD (Least significant digit)
- $x_{k-1}$ is called the MSD (Most significant Digit)
- 

#### Common Radices
r = 2
The Number system is called binary and each digit $x_i$ is a bit ($0\leq x_i \leq 1$)

$$ (10110.101)_2 = 1\times2^4 + 0\times2^3 + 1\times2^2 +1\times2^1 + 0\times2^0 + 1\times2^{-1} + 0\times2^{-2} + 1\times2^{-3} $$

= 22.625

##### Other Common Radices
r = 8 (octal)

r = 10 (decimal)

r = 16 (hexadecimal)

| Base 7 | Base 10 |
| ------ | ------- |
| 0      | 0       |
| 1      | 1       |
| 2      | 2       |
| 3      | 3       |
| 4      | 4       |
| 5      | 5       |
| 6      | 6       |
| 10     | 7       |
| 11     | 8       |
| 12     | 9       |
| 13     | 10        |
- 0-6 = 7 digits
#### Converting to a Different Base
1. Convert a number in base r -> decimal
	- $= 1\times2^4 + 0\times2^3 + 1\times2^2 +1\times2^1 + 0\times2^0 + 1\times2^{-1} + 0\times2^{-2} + 1\times2^{-3}$
	- solve
2. Convert Decimal number -> a number in base R
	- Divide the number and all successive quotients by R and accumalating the reminders

Convert $(89)_{10}$ to binary
$$ (89)_{10} = (x_6x_5x_4x_3x_2x_1x_0)_2 $$
$$ = (1011001)_2 $$
| Integer | Remainder |
| ------- | --------- |
| 89      |           |
| 44      | 1 = $x_0$ |
| 22      | 0 = $x_1$ |
| 11      | 0 = $x_2$ |
| 5       | 1 = $x_3$ |
| 2       | 1 = $x_4$ |
| 1       | 0 = $x_5$ |
| 0       | 1 = $x_6$ |
|         |           |
89/2 = 44 with a remainder of 1. 44/2 = 22 with no remainder. etc...

##### Fractional Part Conversion
- Repeat multiplying the fractional part by R
- The process continues until the fraction becomes 0 or until the number of digits have sufficient accuracy

Convert .8125 to binary
| decimal   | new decimal | digit        |
| --------- | ----------- | ------------ |
| .8125 * 2 | 1.625       | $x_{-1}$ = 1 |
| .625 * 2  | 1.25        | $x_{-2}$ = 1 |
| .25 * 2   | .5          | $x_{-3}$ = 0 |
| .5 * 2    | 1.0         | $x_{-4}$ = 1 |                      |
$.8125 = (0.1101)_2$

#### Conversion between Binary and Octal/Hex
- sine $2^3 = 8$ and $2^4 = 16$, each octal digit corresponds to 3 bits and each hex digit corresponds to 4 bits.
- Partition the binary # into groups of 3/4 bits
	- starting from the binary point and proceeding left and right
![[Pasted image 20220912100234.png]]
find the group you created in the binary coloumn of the table and find what it corresponds to. replace

can also solve each chunk
101 = $1*2^2 + 0*2^1 + 1*2^0$
       = 5

#### Binary Arithmetic
##### Addition
![[Drawing 2022-09-12 16.25.34.excalidraw]]
- Arithmetic operations with numbers in base r follow the same rules as for decimal numbers
- r acts like 10 does in decimal. if you reach 10 carry over

##### Multiplication
![[Drawing 2022-09-12 16.28.55.excalidraw]]
- 1101 (top #) * highlighted part of 101 (bottom #)

##### Subtraction
![[Drawing 2022-09-12 17.10.54.excalidraw]]
