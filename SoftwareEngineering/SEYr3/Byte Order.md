![[Pasted image 20230919091322.png]]
Each Section is 8 bits

- Byte order of the architecture matters
- [[UTF-16]] starts text with the special [[Code Point]]:
	- 1111111011111111 (65,279, 0xFEFF)
	- called [[zero-width non-breaking space]]
- The dual code point
	- 1111111111111110 (65,534) is never assigned
- [[UTF-16LE]] and [[UTF-16BE]] may avoid this


