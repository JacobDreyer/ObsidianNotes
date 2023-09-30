## Question 1
1. Use KCL to find currents $i_1, i_2$, and $i_3$ in the circuit diagram shown in Fig. 1(a)
![[Pasted image 20230302181007.png]]

Node B:
$$ 6-7-i_2 = 0 $$
$$ i_2 = -1 $$
Node A:
$$ i_1 = 1+6 = 7 $$
Node C:
$$ 7 = 2 + i_3 $$
$$ i_3 = 5 $$
2. In the circuit shown in Fig. 1(b), find the following: (i) current $I_0$, (ii) voltage across $6k\ohm$ resistor, $V_{6k\ohm}$ and (iii) power supplied by 12 mA source $P_{12mA}$
![[Pasted image 20230302181408.png]]

$$ R_{4-12} = \frac1{\frac1{4} + \frac1{12}} = 3 $$
$$ i_{p1} = \frac{6}{3 + 3 + 6}(12) = 6 $$
$$ i_0 = \frac{12}{16}(6) = \frac346 = 4.5mA $$
(ii)
$$ i_{6k\ohm} = .5mA $$
$$ V_{6k\ohm} = IR = .006\times 6000 = 36V $$
(iii)
$$ P = IV = I^2R = .012^2\times 3000 = .432 W $$

3. In the circuit shown in Fig. 1(c), find (i) $v_1$ and (ii) $v_2$
![[Pasted image 20230302182703.png]]

Loop:
$$ 32-8 + 4i - 2i = 0 $$
$$ 24 + 2i = 0 $$
$$ i = -12 $$
$$ v_1 = 4(-12) = -48 V $$
$$ v_2 = 24V $$
## Question 2
1. In the circuit shown in Fig. 2(a), find the following: (i) $R_{ab}$, equivalent resistance between terminals $a$ and $b$, (ii) $R_{bc}$, equivalent resistance between terminals $b$ and $c$, and (iii) $R_{de}$, equivalent resistance between terminals $d$ and $e$
![[Pasted image 20230302184459.png]]
$$ R_{ab} = 5||(5+4+4) = \frac{1}{\frac1{5} + \frac1{13}} = 3.61 $$
$$ R_{bc} = 4||(5+5+4) = \frac1{\frac1{4}+\frac1{14}} = 3.11 $$
$$ R_{de} = 10 + (5+4)||(5+4) + 12 = 22 + 4.5 = 26.5 $$
2. In the circuit shown in Fig. 2(b). find the following: (i) number of nodes in the circuit. (ii) use nodal analysis to find voltage of $V_0$, and (iii) specify voltages of all nodes in the circuit.

(i): 4 nodes

(ii): 
Node 2 Formula
$$ \frac{V_2 - V_1}{6000} + \frac{V_2 - 0}{6000} + \frac{V_2-V_3}{12000} = 0\qquad (1) $$
$$  \frac{V_2 - 12}{6000} + \frac{V_2 - 0}{6000} + \frac{V_2-6}{12000} = 0\qquad (1)  $$
$$ 2V_2-24 + 2V_2 + V_2 - 6 = 0 $$
$$ 5V_2 = 30 $$
$$ V_2 = 6 $$
$$ V_2 - V_3 = 6-6 = 0 $$
| Node   | Voltage |
| ------ | ------- |
| Node 1 | 12      |
| Node 2 | 6       |
| Node 3 | 6       |
| Node 4 | 0        |

## Question 3
1. In the circuit shown in Fig. 3(a): (i) find thevenin's equivalent circuit at terminals $ab$ and specify values of Thevenin's voltage source $V_t$ and Thevenin's Resistance $R_t$, and (ii) find Norton's equivalent circuit at terminals $ab$ and specify values of Norton's Current Source $I_n$ and Norton's Resistance, $R_n$
![[Pasted image 20230302201246.png]]
$$ R_{eq} = R_t = (6+6)||(4) = \frac1{\frac{1}{6+6} + \frac1{4}} = 3 $$
$$ V_t = I_2R_{4} = 1.5(4) = 6V $$
$i_2 = \frac{6}{6+10}(4) = 1.5$
(ii):
$$ V_t = R_tI_n $$
$$ I_n = \frac{V_t}{R_t} = \frac63 = 2 $$

2. In the circuit shown in Fig. 3(a), a load resistance $R_L$ is to be connected between terminals $a$ and $b$. What value of $R_L$ would you choose so that maximum power from the circuit is delivered to the load Resistance? What is the value of this power?
$$ R_L = R_t = 3\ohm $$
$$ P = iv = i^2r = (\frac66)^2(3) = 3 $$
3. In the circuit shown in Fig. 3(b), apply superposition principle to find the voltage $v_0 = v_{5A} + v_{12V}$, where $V_{5A}$ is the voltage across $2\ohm$ resistor due to 5A current source and $v_{12V}$ is the voltage across the $2\ohm$ resistor due to $12V$ voltage source 

$$ v_0 = 2.5(2) + 2.4 = 7.4 V $$

## Question 4
1. Find the equivalent capacitance, $C_{eq}$ for the circuit shown in Fig. 4(a)
$$ C_{eq} = ((C||(2C))+C)||C  $$
$$ C_{eq} = \frac1{\frac1{(\frac1{\frac1C + \frac1{2C}} + C)} + \frac1C} = \frac85C $$
2. The Current through a 1mH inductor is $i(t) = 20\cos(100t)mA$. Find the voltage $v(t)$ across the inductor at $t = \pi/200s$ and the energy $W_L(t)$ stored in the inductor at $t = \pi/100s$
$$ v = L\frac{di}{dt} = -.001\cdot2000\sin(100t)\cdot 10^{-3} $$
$$ v = .002\sin(100t) $$
3. Under DC conditions find the current $i$ through the inductor and $v$ across the capacitor in the circuit shown in Fig. 4(b)
![[Pasted image 20230302210004.png]]



