## Up
Consider a 4-bit binary ripple counter that counts up and is rising-edge-triggered. This covers the range 0 to 15. requires 4 flip flops $Q_0,Q_1,Q_2,Q_3$ 

The count should increase for each clock pulse:
- $Q_0$ toggles each pulse
- $Q_1$ should toggle every other, or, by the falling edge of $Q_0$
- $Q_2$ should toggle every fourth, or, by the falling edge of $Q_1$
- Repeat

Because each flip-flop has a propogation delay there is lag for each bit that increases as n increases

#### Implementation using T flip flops
![[Pasted image 20221114160232.png]]
##### Falling Edge Triggered:
![[Pasted image 20221114160410.png]]

## Down
An easy way to do this is simply take the Q's as the out puts rather than the Qs

However we would like to design a counter where the output is the same as the actual state of the circuit.
- $Q_0$ remains the same
- The subsequent states should be complemented, so a down counter should toggle on the rising edge of the previous state
![[Pasted image 20221114160943.png]]
