1- The [[Impedance]] $\vec Z$ of a circuit is the ratio of the phasor voltage $V$ to the phasor current $I$ measured in [[Ohms]] $\ohm$
- That is:
$$ \vec Z = \frac{\vec V}{\vec I} $$
- [[Admittance]] is the reciprocal of [[Impedance]]
$$ \vec Y = \frac1{\vec Z} $$
$$ \vec Y = \frac{\vec I}{\vec V} $$
- [[AC Circuit]] analysis is highly simplified once phasor notations are employed. The circuit analysis becomes equivalent to the analysis we have done for [[DC Circuit]]s

### IMPEDANCES AND ADMITTANCES OF PASSIVE ELEMENTS
![[Pasted image 20230404193426.png]]

### [[Ohms Law]] and [[Kirchhoffs Laws]]
- Represent all voltages and currents in phasor form
- [[Resistance]], [[Inductance]], and [[Capacitance]] by their equivalent impedances
- [[Ohms Law]]:
$$ \vec V = \vec I\vec Z $$
- This is referred to as Ohm's law in frequency domain
- [[Kirchoff's Voltage Law]]
$$ \vec V_1 + \vec V_2+\cdots+\vec V_n = 0 $$
- [[Kirchoff's Current Law]]
$$ \vec I_1 + \vec I_2 + \cdots + \vec I_n = 0 $$
- These are referred to as the [[KVL]] and [[KCL]] in the frequency domain
- Solve for currents and voltages in frequency domain (using phasors) and convert them back to time domain

#### In Series:
$$ Z_{eq} = Z_1 + Z_2 + \cdots + Z_N $$

#### In Parallel
$$ Z_{eq} = \frac1{(\frac1{Z_1} + \frac1{Z_2} + \cdots + \frac1{Z_N})} $$
For N = 2 and Current:
$$ \vec I_1 = \frac{Z_2}{Z_1+Z_2}I $$
$$ I_2 = \frac{Z_1}{Z_1+Z_2}I $$
