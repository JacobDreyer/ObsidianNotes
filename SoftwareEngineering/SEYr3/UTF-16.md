- A [[code unit]] consists of 2 bytes
- [[Code Point]]s below 65,536 are in a single code unit
- Higher code points are represented as 
	- 110110XXXXXXXXX 110111XXXXXXXXX
	- (after subtracting 65,536)
- This makes sense because [[Unicode]] assigns not code units between the numbers 11011000000000 (55,296) and 110111111111111 (57,343)
- 