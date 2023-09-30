Very usefull building black for more complicated circuits, although they are not very cost efficient.

```ad-tldr
title: Definition: n-bit decoder

is a [[Combinational Logic]] circuit that accepts n inputs and returns $2^n$ outputs. The output corresponding to the binary value inputs is 1 or 0, all other outputs are the opposite value. 
```

### Active High vs Low
- Active High means that it goes to 1 when selected but idles at 0
- Active Low means that it goes to o when selected but idles at 1

- The output of an active-high decoder is essentially a minterms
- The output of a active-low decoder is a maxterm
- So there is no way to simplify the circuit

### Truth Table for an Active high 3 bit decoder:
![[Pasted image 20221018102805.png]]
