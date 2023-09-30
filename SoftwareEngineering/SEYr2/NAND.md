$$ x\uparrow y = \bar{(xy)} = \bar x+\bar y $$
![[Drawing 2022-10-18 09.38.39.excalidraw]]
### NAND Implementations
##### NOT:
$$ f = \bar x \longrightarrow x\cdot x = x\longrightarrow\bar{x\cdot x} = \bar x\longrightarrow x\uparrow x = \bar x $$
![[Drawing 2022-10-18 09.08.15.excalidraw]]

##### AND:
$$ f(x,y) = xy = \bar{(\bar x\cdot \bar y)} = \bar{x\uparrow y} = (x\uparrow y)\uparrow(x\uparrow y) $$
![[Drawing 2022-10-18 09.16.57.excalidraw]]
##### OR:
$$ f(x,y) = x+y = \bar{(\bar x\cdot\bar y)}=(\bar x\uparrow\bar y)=(x\uparrow x)\uparrow(y\uparrow y) $$
![[Drawing 2022-10-18 09.23.14.excalidraw]]

### Converting to NAND
- We can add two NOT gates to either side of a wire without changing the circuit
- This means that for internal connections an inverting bubble can be placed at the output of one gate, if another is placed at the input of the following gate
- For variable inputs, inverting bubbles can be added to the input of any gate as long as that variable is replaced with its complement
- For the circuit output an inverting bubble can be placed there as long as another explicit NOT gate (or NAND equivalent) is placed before the output
- Any resulting invert-NOT gate can now be swapped with a standard NAND gate

