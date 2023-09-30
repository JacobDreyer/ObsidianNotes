```ad-tldr
title: Definition: Multiplexors (MUX)

A Multiplexor is a combinational circuit that accepts $2^n+n$ inputs and one output. The output is equal to one of the $2^n$ inputs, while the remaining $+n$ inputs are used as a binary code to select the input
```

![[Pasted image 20221018125020.png]]

- We can also use smaller MUXs to build larger ones
	- Ex. We can use an 8 x 1 MUX and connect 2 using a 2 x 1 MUX to form a 16 x 1 MUX
- Most MUXs are designed with an additional input to enable the circuit
- MUXs can also be constructed from [[Tri-State Buffer]]s
