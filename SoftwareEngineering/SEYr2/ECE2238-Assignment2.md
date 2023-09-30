Name of Student: Jacob Dreyer
Student ID: 251241714
Date: 2023/03/19

#### Answer Sheet:
##### 1:
$$ V_1 = 22.91V \qquad V_2 = 8.72V $$
##### 2:
$$ V_0 = 4V_1 - V_2 \qquad V_0 = 2V $$
##### 3:
$$ V_0 = 7.5V $$
##### 4:
$$ I_{8\ohm} = 1A \qquad P_{8\ohm} = 8W $$
##### 5:
$$ R = 1k\ohm $$
##### 6:
$$ R_1 = R_2 = R_3 = R_4 = 40k\ohm $$
##### 7:
$$ C_{eq} = 22.39\mu F $$

#### 1. Using nodal analysis find $V_1$ and $V_2$ in the circuit shown in figure 1
![[Pasted image 20230302175544.png]]
KCL for $V_1$:
Set node below 3kOhm resistor = to 0V
$$ .012 - .002 + \frac{V_1 - 0}{3000} + \frac{V_1 - V_2}{6000} = 0 $$

KCL for $V_2$:
$$ .002 + \frac{V_2 - V_1}{6000} + \frac{V_2-0}{6000} + \frac{V_2-0}{3000} $$
$$ -.002 = \frac{2V_2 - V_1}{6000} + \frac{2V_2}{6000} $$
$$ -12 = 4V_2 - V_1 $$
$$ V_1 = 4V_2 + 12 $$
Simplify Eqn 1:
$$ -.01 = \frac{2V_1}{6000} + \frac{V_1 - V_2}{6000} $$
$$ 60 = 3V_1 - V_2 $$
Sub in Eqn 2:
$$ V_2 = 3(4V_2 + 12) + 60 $$
$$ V_2 = 12V_2 + 96 $$
$$ 11V_2 = -96 $$
$$ V_2 = 8.72 V $$

(1) $$ \frac{60}{3} + \frac{V_2}3 = V_1 $$
$$ 20 + \frac{8.72}3 = V_1 = 22.91 $$

#### 2. (a) Find $V_0$ in terms of $V_1$ and $V_2$; (b) if $V_1 = 2V$ and $V_2 = 6V$ find $V_0$
![[Pasted image 20230318160828.png]]
$$ V_a = V_b $$
$$ V_a = V_1 = V_b $$
##### Nodal Analysis:
$$ \frac{V_b - V_2}{2} + \frac{V_b - V_0}{2} + \frac{V_b}{1} = 0 $$
$$ V_b - V_2 + V_b - V_0 + 2V_b = 0 $$
$$ 4V_b-V_2-V_0 = 0 $$
$$ 4V_1 - V_2 = V_0 $$
$$ 4(2) - 6 = V_0 $$
$$ 2V = V_0 $$

#### 3. Using the Superposition principle, find $V_0$ in the circuit shown in Fig. 3
![[Pasted image 20230303104445.png]]
$$ V_0 = .0015(2000) + V_{12V} $$
$$ R_{eq} = \frac{1}{\frac{1}{3} + \frac{1}{2}} + 2 = 3.2 $$
$$ I = 12/3.2 = 3.75 $$
$$ I_{V_0} = \frac{3}{2+3}(3.75) = 2.25 $$
$$ V_{12V} = .00225(2000) = 4.5 $$
$$ V_0 = 3 + 4.5 = 7.5 $$
#### 4. Using source transformation, determine the current and power in 8ohm resistor
![[Pasted image 20230303122832.png]]
$$ V_t = 30 $$
![[Drawing 2023-03-03 12.29.07.excalidraw]]
Node 1:
$$ \frac{30 - V}{18} + \frac{15-V}3 =  \frac{V - 0}{6}  $$

$$ 30-V + 6(15) - 6V = 3V $$
$$ 120 - 7V = 3V $$
$$ 120 = 10V $$
$$ 12\;V = V $$
$$ I_{8\ohm} = \frac{30-V}{18} = \frac{30-12}{18} = 1A $$
$$ P_{8\ohm} = I_{8\ohm}^2\times R = 1^2\times 8 = 8W $$


#### 5. determine the value of R such that the maximum power delivered to the load $R_L$ is $3mW$
![[Pasted image 20230318163250.png]]
$$ R_t = R_{eq} = \frac{1}{(\frac1R + \frac1R + \frac{1}{R})} $$
$$ = \frac{1}{\frac{3}{R}} = \frac{R}{3} $$
$V_t$:
$$ \frac{V_t - 1}{R} + \frac{V_t - 2}{R} + \frac{V_t - 3}{R} = 0 $$
$$ V_t - 1 + V_t - 2 + V_t - 3 = 0 $$
$$ 3V_t = 6 $$
$$ V_t = 2 $$
Solve:
$$ P_{max} = \frac{V_t^2}{4R_t} $$
$$ R_t = \frac{V_t^2}{4P_{max}} $$
$$ \frac R3 = \frac{2^2}{4(.003)} $$
$$ R = \frac{3}{.003} = 1000\;\ohm $$
#### 6. An averaging amplifier is a summer that provides an output equal to the average of the inputs. By using a proper input and feedback resistor values, one can get:
$$ -v_{out} = \frac14(v_1 + v_2 + v_3 + v_4) $$
	Design an OPAMP circuit that can provide the above mathematical function. In the design use the feedback resistance value of 𝑅𝑓 = 10𝑘Ω. Draw the OPAMP circuit diagram.
![[Drawing 2023-03-19 21.12.30.excalidraw]]

Node Law at 1:
$$ v_- = v_+ = 0 $$
$$ -\frac{v_0}{R_f} = \frac{v_1}{R_1} + \frac{v_2}{R_2} + \frac{v_3}{R_3} + \frac{v_4}{R_4}  $$
$$ -v_o = R_f\frac{v_1}{R_1} + R_f\frac{v_2}{R_2} + R_f\frac{v_3}{R_3} + R_f\frac{v_4}{R_4} $$
$$ \therefore \frac{R_f}{R_1} = \frac14 \; and \; R_1 = R_2 = R_3 = R_4 $$
$$ R_f = 10000 =  \frac14R_x $$
$$ 40000\ohm = 40k\ohm = R_1 = R_2 = R_3 = R_4 $$

#### 7. Obtain the equivalent capacitance, $C_{eq}$, of the network shown in Fig. 7.
![[Pasted image 20230319213111.png]]

Convert right side connection to delta connection:
$$ C_1 = \frac{C_a\times C_b}{C_a + C_b + C_c} = \frac{50\times 30}{50+30+20} = 15\mu F $$
$$ C_2 = \frac{C_a\times C_c}{C_a + C_b + C_c} = \frac{50\times 20}{50+30+20} = 10\mu F $$
$$ C_3 = \frac{C_b\times C_c}{C_a + C_b + C_c} = \frac{30\times 20}{50+30+20} = 6\mu F $$
![[Drawing 2023-03-19 21.31.36.excalidraw]]

$$ C_{eq} = 10 + \frac1{(\frac1{15+40} + \frac1{6+10})} = 22.39\mu F $$
