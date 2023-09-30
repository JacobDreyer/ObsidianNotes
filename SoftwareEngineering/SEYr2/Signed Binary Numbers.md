## Signed Binary Numbers
if a binary number is signed, the leftmost bit represents the sign (0 -> +ve, 1-> -ve)
The rest represents the number

![[Pasted image 20220919154436.png]]

#### To change +ve to -ve
- in signed magnitude: only change the sign bit
- complement (1s or 2s) all bits, including the sign bit in 2 other # systems

##### Signed 1's Complement
- a n-digit number is restricted to positive values with (n-1) digits
- Therefore a 1 in the MsD (left-most) indicates negative value
- The negative number is the original (positive) number in binary with each of the digits flipped
- There are 2 representations of 0
	- +0   0000
	- -0    1111

Adding
- add the binary number and the signed binary number
- no carry-out: correct
- carry-out: add to LSD(rightmost digit)

##### Signed-2's-complement is the common method
- Flip all the bits then add 1
- The sign bit has a negative value
$$ -12 = -128+64+32+16+4 = (11110100)_2 $$
Adding
- add
- Carry-out: don't add the Carry-out8

![[Pasted image 20220922152102.png]]