### Basic Amplifier Concepts
ideally an [[Amplifier]] produces an output signal with identical wave shape as the input signal, but with a larger [[Amplitude]]
$$ v_0(t) = A_vv_i(t) $$
$v_i(t)$ is the signal output applied to the input terminals of the amplifier

$v_0(t)$ is the output signal

$A_v$ is the voltage gain and $R_L$ is the [[Load Resistance]]

![[Pasted image 20230301180443.png]]

### Basic Amplifier Concepts
- If the gain of the Amiplifier $A_v$, is positive, the amplifier is called a [[Non-Inverting Amplifier]]
- If the gain of the Amplifier $A_v$, is negative, the amplified is called a [[Inverting Amplifier]]

### Model of an Electronic Amplifier
- The figure below shows the model of an electronic amplifier, including input [[Resistance]] $R_i$ and output resistance $R_o$
- The input resistance of the amplifier is the equivalent resistance seen when looking into the input terminals
![[Pasted image 20230302113215.png]]

- The open circuit voltage gain is defined as (When the load is open circuit)
$$ A_{voc} = \frac{v_o}{v_i} $$
- The current gain $A_i$ of the amplifier is:
$$ A_i = \frac{i_o}{i_i} $$
- $i_i$ is the [[Current]] delivered to the input terminals of the amplifier:
$$ i_i = \frac{v_i}{R_i} $$
- $i_o$ is the output current and is given by:
$$ i_o = \frac{v_o}{R_L} $$
- Thus:
$$ A_i = \frac{i_0}{i_i} = \frac{v_o/R_L}{v_i/R_i} = A_v\frac{R_i}{R_L} $$
- Where:
$$ A_v = \frac{v_o}{v_i} $$
- $A_v$ is the voltage gain of the amplifier with load resistance connected
- [[Power]] gain of the amplifier is defined as:
$$ G = \frac{P_o}{P_i} = \frac{v_oi_o}{v_ii_i} = A_vA_i = A_v^2\frac{R_i}{R_L} $$

### Loading Effects
- It is noted that not all of the internal voltage of the source appearss at the input terminals
- This is because a finite input resistance of the amplifier allows current to flow into the input terminals resulting in a voltage drop across the Internal resistance $R_s$ of the source
- Similarily, the voltage produced by the controlled source does not all appear across the load
- The reductions in Voltage are called [[Loading Effects]]
- Because of Loading Effects, the Voltage gains $A_v$ and $A_{vs}$ realized are less than the internal gain $A_{voc}$

### [[Cascaded Amplifiers]]
- Sometimes we connect the output of one amplifier to the input of another amplifier. this is called a [[Cascade Connection]]
![[Pasted image 20230302114345.png]]
- The overall gain of cascaded amplifier stages is the product of voltage gains of individual stages

### Power Gain and the Unit Decibel
- When a communication receiver is very sensitive to RF (Radio Frequency) signals, it may be able to pick up signals as small as $1\times 10^{-9}$ Watts
- This small signal is fed to a power amplifier or a cascade of power amplifiers to bring up the power level
- If the output of the power amplifier $P_0$ required is 1W when the input power to the power amplifier ($P_i$) is $1\times 10^{-9}$ Watts, the power gain of the Amplifier $G$ is:
$$ G = \frac{P_o}{P_i} = 10^9 $$
- If $G>1$, the system is referred to as an [[Amplifier]]
- If $G<1$, the system is referred to as an [[Attenuator]]

- $G$ can be a large quantity or a very small quantity
- Decibel allows us to represent these numbers by making them more manageable and understandable
- It is given by:
$$ G_{dB} = 10\log_{10}G $$
Ex: $G = 10000 = 10^4$ -> $G_{dB} = 10\log_{10}10000 = 10\log_{10}10^4 = 40dB$

#### Decibel Values
- Suppose Amlifier 1 has a power gain of $10^3$ say $G_1$, and Amplifier 2 has a gain of $10^4$ (say $G_2$). It is noted that $G_{1.dB} = 30dB$ and $G_{2.dB} = 40dB$
- The combined gain of the cascade of Amplifier 1 and 2 is given by:
$$ G = G_1G_2 = 10^3\times 10^4 = 10^7 $$
$$ G_{dB} = G_{1.dB} + G_{2.dB} = 70dB $$
### [[Operational Amplifier]]
![[Operational Amplifier]]

