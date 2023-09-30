- An op amp is an electronic unit that behaves like a [[voltage]]-controlled [[Voltage Source]]
- An op amp is an active circuit element designed to perform mathematical operations of addition, subtraction, division, [[differentiation]], and [[Integration]]
- An op amp is an electronic device consisting of a complex arrangement of [[Resistors]], [[Transitor]]s, [[Capacitor]]s, and [[Diode]]s
- A full discussion of what is inside the op amp is beyond the scope of this course
- It will suffice to treat the op amp as a circuit building block and use it to realize various mathematical functions
- In this course we will consider only ideal op amps

![[Pasted image 20230316131111.png]]
- Typical op amp integrated circuit package

![[Pasted image 20230316131142.png]]
- Eight-pin configuration of typical op amp package

![[Pasted image 20230316131223.png]]
- Equivalent circuit model of an op amp

### Ideal Operational Amplifier
- To facilitate the understanding of op amp circuits, we assume ideal op amps
- An op amp is ideal if:
	- Infinite Loop Gain ($A_{voc} \cong \infty$) (Typical value = $10^8$)
	- Infinite input Resistance ($R_i \cong \infty$) (Typical value = $10^3$)
	- Zero output resistance ($R_o\cong 0$) (Typical Value = 10 Ohm)
- Although assuming an ideal op amp provides only an approximate analysis, most modern amplifiers have such large gains and input resistances that the approximate analysis is a good one
- Two Important characteristics of the op amp:
	1. The currents into both input terminals is zero
	2. The voltage across the terminals is negligible:
$$ v_d = v_2 - v_1 \cong 0 $$
$$ v_1 = v_2 $$
![[Pasted image 20230316131951.png]]
- It has one inverting terminal (-ve) and one non-inverting terminal (+ve)
- We can realize various mathematical functions such as addition, subtraction, [[Integration]], and [[differentiation]] by connecting [[Resistors]], [[Capacitor]]s, and [[Inductor]]s to an op amp

### [[Inverting Amplifier]]
![[Inverting Amplifier]]

### [[Non-Inverting Amplifier]]
![[Non-Inverting Amplifier]]

### [[Summing Amplifier]]
![[Summing Amplifier]]

### [[Difference Amplifier]]
![[Difference Amplifier]]

### [[Differentiator]]
![[Differentiator]]

### [[Integrator]]
![[Integrator]]

