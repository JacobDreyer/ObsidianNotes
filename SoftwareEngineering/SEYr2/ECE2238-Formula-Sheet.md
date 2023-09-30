#### Power and Energy
$$ p = vi $$
- $p$ = [[Power]]
- $v$ = [[Voltage]]
- $i$ = [[Current]]
- Units: $\frac{joules}{sec} = Watts$

#### [[Ohms Law]]
$$ v = iR $$
- $v$ = [[Voltage]]
- $i$ = [[Current]]
- $R$ = [[Resistance]]

#### [[Conductance]]
$$ G = \frac1R $$
- $G$ = [[Conductance]]
- $R$ = [[Resistance]]

#### [[Current in Parallel]]
$$ I_T = I_1 + I_2 + \cdots + I_n $$
- assuming same direction

#### [[Voltage in Series]]
$$ V_{eq} = V_1 + V_2 + \cdots + V_n $$
- assuming same direction

#### [[Resistance in Series]]
$$ R_{eq} = R_1 + R_2 + \cdots + R_n $$

#### [[Resistance in Parallel]]
$$ R_{eq} = \frac{1}{(\frac{1}{R_1} + \frac{1}{R_2} +\cdots + \frac{1}{R_n})} $$

#### [[Current Division Rule]]
For 2 seperate paths. Each with a resistor
$$ i_1 = \frac{v}{R_1} = i\frac{R_2}{R_1 + R_2} $$
$$ i_2 = \frac{v}{R_2} = i\frac{R_1}{R_1 + R_2} $$
- $i$ = total current going into split
- $i_1$ = current along path 1
- $i_2$ = current along path 2
- $R_1$ = resistance of path 1
- $R_2$ = resistance of path 2

#### [[Voltage Divider]]
For finding each voltage across multiple resistors connected in series
$$ v_1 = \frac{R_1}{R_1 + R_2 + \cdots R_n}v_{total} $$
$$ v_2 = \frac{R_2}{R_1 + R_2 + \cdots + R_n}v_{total} $$
$$ \vdots $$
### [[Capacitor]]s
##### Charge
$$ q=Cv $$
- $q$ = charge stored by the capacitor
- $v$ = applied voltage
- $C$ = Constant of proportionality = Capacitance

##### Capacitance (Parallel Plate)
$$ C=\epsilon\frac Ad $$
- $C$ = Capacitance
- $A$ = Surface area of plate
- $d$ = distance between plates
- $\epsilon$ = Permitivity of Dielectric

##### Permitivity
$$ \epsilon = \epsilon_0\epsilon_r $$
- $\epsilon$ = permitivity of Dielectric
- $\epsilon_0 = 8.85\times10^{-12}F/m$
- $\epsilon_r$ = depends on the dielectric material = relative dielectric constant

##### Current Across Capacitor
$$ i = C\frac{dv}{dt} $$
- $i$ = current
- $C$ = Capacitance
- $v$ = voltage

##### ==Voltage Across Capacitor==
$$ v(t) = \frac1C\int_{t_0}^t i(t)dt + v(t_0) $$
- $v(t)$ = voltage as a function of time
- $i(t)$ = current as a function of time
- $v(t_0)$ = Initial voltage on capacitor at time $t_0$

##### Initial Voltage
$$ v(t_0) = \frac{q(t_0)}{C} $$
- $v(t_0)$ = initial voltage
- $q(t_0$) = initial charge at time $t_0$
- $C$ = Capacitance

##### Energy Stored in Capacitor
$$ w(t) = \int_{v(t_0)}^{v(t)}Cv(t)dv(t) $$
Assuming $v(t_0) = 0$
$$ w(t) = \frac12Cv^2(t) $$
$$ w(t) = \frac{q^2(t)}{2C} $$
- $w(t)$ = energy stored in capacitor that can be returned to circuit
- $v(t)$ = voltage as a function of time
- $C$ = capacitance
- $q(t)$ = charge as a function of time

##### Capacitances in Parallel
$$ C_{eq} = C_1 + C_2 + \cdots + C_N $$

##### Capacitances in Series
$$ C_{eq} = \frac1{(\frac{1}{C_1} + \frac1{C_2} + \cdots + \frac1{C_3})} $$

### [[Inductor]]s
##### Voltage
$$ v(t) = L\frac{di(t)}{dt} $$
- $v(t)$ = Voltage as a function of time
- $i(t)$ = current as a function of time
- $L$ = Inductance

##### Inductance
$$ L = \frac{N^2\mu A}{l} $$
- $N$ = Number of turns
- $l$ = length
- $A$ = cross-sectional area
- $\mu = \mu_0\mu_r$ = permeability of the core

##### Current
$$ i(t) = \frac1L\int_{t_0}^tv(t)dt + i(t_0) $$
- $i(t)$ = Current as a function of time
- $v(t)$ = voltage as a function of time
- $L$ = Inductance
- $i(t_0)$ = total current for $-\infty<t<t_0$ and $i(-\infty) = 0$

##### Energy Stored in an Inductor
$$ w(t) = \int_{i(t_0)}^{i(t)}Li(t)di(t) $$
Assuming $i(t_0) = 0$
$$ w(t) = \frac12 Li^2(t) $$
- $w(t)$ = energy stored in inductor
- $i(t)$ = Current as a function of time
- $i(t_0)$ = total current for $-\infty<t<t_0$ and $i(-\infty) = 0$
- $L$ = inductance

##### Inductances in Series
$$ L_{eq} = (L_1 + L_2 + \cdots +L_n) $$

##### Inductances in Parallel
$$ L_{eq} = \frac1{(\frac1{L_1} + \frac1{L_2} + \cdots + \frac1{L_n})} $$

### [[Amplifiers]]
$$ v_o(t) = A_vv_i(t) $$
- $v_o(t)$ = The output signal
- $v_i(t)$ = the signal input
- $A_v$ = The voltage gain

##### Output Voltage
$$ v_o = (1+\frac{R_f}{R_i})v_i $$

##### Voltage Gain
$$ A_{voc} = \frac{v_o}{v_i} $$
- $A_{voc}$ = voltage gain
- $v_o$ = amplified voltage output (across $R_L$)
- $v_i$ = voltage output of normal/first/(circuit to amplify) (across $R_i$)

##### Current Gain
$$ A_i = \frac{i_o}{i_i} $$
- $A_i$ = current gain
- $i_o$ = current through second/amplified circuit
- $i_i$ = current through circuit to be amplified

$$ i_i = \frac{v_i}{R_i} $$
- $i_i$ = current through circuit to be amplified
- $v_i$ = voltage output of normal/first/(circuit to amplify) (across $R_i$)
- $R_i$ = load resistance of circuit to be amplified

$$ i_o = \frac{v_o}{R_L} $$
- $i_o$ = current through second/amplified circuit
- $v_o$ = amplified voltage output (across $R_L$)
- $R_L$  = Load resistance of amplified circuit

##### Power Gain
$$ G = \frac{P_o}{P_i} = \frac{v_oi_o}{v_ii_i} = A_vA_i = A_v^2\frac{R_i}{R_L} $$

##### Cascaded Amplifiers
$$ A_v = A_{v1}\times A_{v_2} = \frac{v_{o2}}{v_{i_1}} $$
$$ G = G_1G_2 $$

##### Decibels
$$ G_{dB} = 10\log_{10}G $$
- $G_{dB}$ = Power Gain in decibels

### Sinusoidal Currents and Voltages
$$ v(t) = V_m\cos(\omega t+\theta) $$
- $v(t)$ is voltage as a function of time
- $V_m$ is the peak value of the voltage
- $\omega = 2\pi f$ = the [[Angular Frequency]]
	- $f$ is the [[Frequency]]
- $\theta$ is the [[Phase Angle]]

##### Power from a Sinusiodal Voltage Source
$$ p(t) = \frac{v^2(t)}R $$
- $p(t)$ = power as a function of time
- $v(t)$ = voltage as a function of time
- $R$ = Resistance

##### Energy Delivered in one Period
$$ E_T = \int_0^Tp(t)dt $$
- $E_T$ = energy delivered in one period
- $T$ = length of the period
- $p(t)$ = power as a function of time

##### Average Power
$$ P_{avg} = \frac{E_T}T = \frac1T\int_0^Tp(t)dt = \frac{V_{rms}^2}R = I_{rms}^2 R $$
- $P_{avg}$ = average power
- $E_T$ = Total energy delivered in one period
- $T$ = Period/length of period
- $p(t)$ = power as a function of time
- $V_{rms}$ = Root mean square value of a periodic voltage
- $R$ = Resistance
- $I_{rms}$ = Root mean square for a periodic current

##### Root Mean Square (RMS) / Effective Value
$$ V_{rms} = [\frac1T\int_0^Tv^2(t)dt]^{\frac12} = \frac{V_m}{\sqrt 2} $$
$$ I_{rms} = [\frac1T\int_0^Ti^2(t)dt]^\frac12 $$
- $V_{rms}$ = root mean square value of a period voltage $v(t)$
- $I_{rms}$ = Root neab square value of a periodic current
- $v(t)$ = (periodic) voltage as a function of time
- $i(t)$ = periodic current as a function of time
- $T$ = period
- $V_m$ = peak value of the voltage


### Changing sin to cos
$$ \sin(x) = \cos(x-90^0) $$

### [[Phasor]]s
$$ \boldsymbol V_1 = V_1\angle\theta_1 = V_1e^{i\theta} $$
- $\boldsymbol V_1$ is the phasor for function: $v_1(t) = V_1\cos(\omega t+\theta_1)$
- $i = \sqrt{-1}$ 
$$ v(t) = V_m\cos(\omega t + \theta) = Re[V_me^{i(\omega t+\theta)}] $$
$$ V_me^{i(\omega t + \theta)} = V_m\angle\omega t+\theta $$

##### [[Euler's Formula]]
$$ \cos(\theta) = Re(e^{i\theta}) = Re(\cos\theta + i\sin\theta) $$
- $Re$ = Retain only the real part
- $i = \sqrt{-1}$

##### Converting [[Complex Number]]s
From form ($a + bi$) to ($r\angle\theta^0$):
$$ r = \sqrt{a^b + b^2} $$
$a>0$:
$$ \theta = \arctan(\frac ba) $$
$a < 0,\;\; b\geq 0$:
$$ \theta = \arctan(\frac ba) + \pi $$
$a<0,\quad b<0$:
$$ \theta = \arctan(\frac ba) - \pi $$
$a=0,\quad b>0$:
$$\theta = \frac\pi2$$
$a=0\quad b<0$:
$$ \theta = -\frac\pi2 $$
$a=0,\quad b=0$:
$$ \theta = undefined $$
From ($r\angle\theta^0$) to ($a + bi$)
$$ a = r\cos\theta $$
$$ b = r\sin\theta $$

##### Mathematical Operations
$$ z = x+iy = r\angle\phi =r(\cos\phi + i\sin\phi) $$
Given:
$$ z_1 = x_1 + iy_1 = r\angle\phi_1 $$
$$ z_2 = x_2 + iy_2 = r_2\angle\phi_2 $$
Addition:
$$ z_1+z_2 = (x_1+x_2) + i(y_1+y_2) $$
Subtraction:
$$ z_1-z_2 = (x_1-x_2) + i(y_1-y_2) $$
Multiplication:
$$ z_1z_2 = r_1r_2\angle(\phi_1+\phi_2) $$
Division:
$$ \frac{z_1}{z_2} = \frac{r_1}{r_2}\angle(\phi_1-\phi_2) $$
Reciprocal:
$$ \frac1{z_1} = \frac1{r_1}\angle-\phi_1 $$
Square Root:
$$ \sqrt{z_1} = \sqrt{r_1}\angle\frac{\phi_1}2 $$
Complex Conjugate:
$$ z_1^* = x_1-iy_1 = r_1\angle-\phi_1 = r_1 $$

### Complex Impedances
##### Inductance:
$$ \boldsymbol Z_L = i\omega L $$
- $\omega$ = [[Angular Frequency]]
- $L$ = [[Inductance]]
- $\boldsymbol Z_L$ = [[Impedance]] 
- $i = \sqrt{-1}$

##### Capacitance:
$$ \boldsymbol Z_C = \frac1{i\omega C} $$
- $\boldsymbol Z_C$ = Impedance for Capacitor
- $\omega$ = [[Angular Frequency]]
- $C$ = Capacitance
- $i = \sqrt{-1}$

##### Resistance:
$$ \boldsymbol Z_R = R $$
- $\boldsymbol Z_R$ = Impedance of Resistor
- $R$ = Resistance

##### Impedance in General
$$ \boldsymbol Z = R+iX $$
- $\boldsymbol Z$ = impedance
- $R$ = Resistive Part
- $X$ = Reactive Part (reactance)
- $i = \sqrt{-1}$
$$ \sin(\theta) = \frac{X}{|\boldsymbol Z|} $$
- $\theta$ = phase angle

##### [[Admittance]]
$$ \boldsymbol Y = \frac1{\boldsymbol Z} $$
- $\boldsymbol Y$ = Admittance
- $\boldsymbol Z$ = Impedance

##### Ohm's Law in Phasor Form
$$ \boldsymbol V = \boldsymbol I\boldsymbol Z $$
- $\boldsymbol V$ = Voltage in phasor form
- $\boldsymbol I$ = Current in phasor form
- $\boldsymbol Z$ = Impedance

##### [[Kirchoff's Voltage Law]]
$$ \boldsymbol V_1 + \boldsymbol V_2+\cdots+\boldsymbol V_n = 0 $$

##### [[Kirchoff's Current Law]]
$$ \boldsymbol I_1 + \boldsymbol I_2 + \cdots + \boldsymbol I_n = 0 $$

##### Impedance in Parallel
$$ \boldsymbol Z_{eq} = \frac1{(\frac1{\boldsymbol Z_1} + \frac1{\boldsymbol Z_2} + \cdots + \frac1{\boldsymbol Z_n})} $$

##### Impedance in Series
$$ \boldsymbol Z_{eq} = \boldsymbol Z_1 + \boldsymbol Z_2 + \cdots + \boldsymbol Z_n $$

##### Average Power in a sinusoidal circuit
$$ P = \frac{V_mI_m}2\cos\theta = V_{rms}I_{rms}\cos\theta = Re(\boldsymbol S) $$
- $V_m$ = peak voltage
- $I_m$ = peak current
- $\theta$ = power angle
- $V_{rms}$ = root mean squared voltage
- $I_{rms}$ = root mean squared current
- $\boldsymbol S$ = Complex Power

##### Angle of the load Impedance (Power Angle)
$$ \theta = \theta_v - \theta_i $$
- $\theta_v$ = phase angle of the voltage
- $\theta_i$ = phase angle of the current

##### Peak Instantaneuos Power (Reactive Power)
$$ Q = V_{rms}I_{rms}\sin\theta = Im(\boldsymbol S) $$
- $\theta$ = phase angle/power angle
- $V_{rms}$ = root mean squared voltage
- $I_{rms}$ = root mean squared current
- $Im()$ = Imaginary part
- $\boldsymbol S$ = Complex Power

##### Apparent Power
$$ S = V_{rms}I_{rms} $$
- $V_{rms}$ = root mean squared voltage
- $I_{rms}$ = root mean squared current

##### How the 3 relate:
$$ P^2 + Q^2 = S^2 $$
- $S$ = Apparent Power
- $P$ = Average Power
- $Q$ = Reactive Power

##### [[Complex Power]]
$$ \boldsymbol S = \frac12 \boldsymbol V\boldsymbol I^* = \boldsymbol V_{rms} \boldsymbol I_{rms}^* = \frac12V_{m}I_{m}\angle\theta = P+iQ = |\boldsymbol S| = \sqrt{P^2 + Q^2} $$
- $\boldsymbol S$ = Complex Power
- $\boldsymbol V$ = Voltage in phasor form
- $\boldsymbol I$ = Current in phasor form
- $\boldsymbol V_{rms}$ = root mean squared voltage
- $\boldsymbol I_{rms}$ = root mean squared current
- $^*$ = denotes [[Complex Conjugate]]
- $\theta = \theta_v - \theta_i$ = power angle 
- $V_m$ = Peak Voltage
- $I_m$ = peak current
- $P$ = average power
- $Q$ = Reactive Power

##### Conservation of AC Power
$$ \boldsymbol S = \boldsymbol S_1 + \boldsymbol S_2+\cdots + \boldsymbol S_n $$

### Frequency Response
##### [[Transfer Function]]
4 Types: Slides label them all $\boldsymbol H(\omega)$ but I don't know if that means they are equal or not so I will label them differently here
$$ \boldsymbol H_{vg}(\omega) = \frac{\boldsymbol V_o(\omega)}{\boldsymbol V_i(\omega)} = voltage\; gain $$
$$ \boldsymbol H_{ig}(\omega) = \frac{\boldsymbol I_o(\omega)}{\boldsymbol I_i(\omega)} = current\; gain $$
$$ \boldsymbol H_{ti}(\omega) = \frac{\boldsymbol V_o(\omega)}{\boldsymbol I_i(\omega)} = transfer\; impedance $$
$$ \boldsymbol H_{ta}(\omega) = \frac{\boldsymbol I_o(\omega)}{\boldsymbol V_i(\omega)} = transfer\; admittance $$
- Subscript $i$ = input
- Subscript $o$ = output
- $\boldsymbol V(\omega)$ = phasor voltage as a function of angular frequency
- $\boldsymbol I(\omega)$ = phasor current as a function of angular frequency

##### Common Substitution
$$ s = i\omega $$

### Resonance
##### Resonant Frequency
$$ \omega_o = \frac1{\sqrt{LC}} $$
- $\omega_o$ = Resonant frequency
- $L$ = Inductance
- $C$ = Capacitance

##### Inductor Voltage
$$ |\boldsymbol V_L| = \frac{V_m}{R}\omega_o L $$
- $\boldsymbol V_L$ = voltage across inductor in phasor form
- $V_m$ = peak voltage
- $R$ = resistance
- $\omega_o$ = Resonant frequency
- $L$ = Inductance

##### Capacitor Voltage
$$ |\boldsymbol V_C| = \frac{V_m}R\frac1{\omega_oC} $$
- $\boldsymbol V_C$ = Voltage across capacitance in phasor form
- $V_m$ = peak voltage
- $R$ = Resistance
- $\omega_o$ = resonant frequency
- $C$ = Capacitance

##### Frequency Response of the Circuit's Current Magnitude
$$ I = |\boldsymbol I| = \frac{V_m}{\sqrt{R^2 + (\omega L-\frac1{\omega C})^2}} $$
- $I$ = Current
- $\boldsymbol I$ = Current in phasor form
- $V_m$ = peak voltage
- $R$ = Resistance
- $\omega$ = angular frequency
- $L$ = inductance
- $C$ = Capacitance

##### Average Power Dissipated at Resonance
$$ P(\omega) = \frac12I^2R $$
- $P(\omega)$ = Power as a function of frequency
- $I$ = Current
- $R$ = Resistance

##### Highest Value of Average Power Dissipated
$$ P(\omega_o) = \frac12\frac{V_m^2}R $$
Occurs when
$$ I = \frac{V_m}R $$
- $V_m$ = Peak Voltage
- $P(\omega_o$) = average power dissipated at resonance
- $R$ = Resistance
- $I$ = Current

##### [[Half-Power Frequencies]]
$$ \omega_1 = -\frac{R}{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} = -\frac{\omega_o}{2Q} + \omega_o\sqrt{1+(\frac1{2Q})^2} $$
$$ \omega_2 = +\frac{R}{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} = +\frac{\omega_o}{2Q}+\omega_o\sqrt{1+(\frac1{2Q})^2} $$
$$ \omega_o = \sqrt{\omega_1\omega_2} $$
For Large $Q$ (Greater than 10)
$$ \omega_1 \cong \omega_o - \frac B2  $$
$$ \omega_2 \cong \omega_o + \frac B2 $$
- $\omega_1, \omega_2$ = Half power frequencies
- $\omega_o$ = Resonant Frequency
- $R$ = Resistance
- $L$ = Inductance
- $C$ = Capacitance
- $Q$ = Quality Factor
- $B$ = Bandwidth

##### Power at [[Half-Power Frequencies]]
$$ P(\omega_1) = P(\omega_2) = \frac{V_m^2}{4R} $$
- $P(\omega_1),P(\omega_2)$ = Power at half power frequencies
- $V_m$ = Peak voltage
- $R$ = Resistance

##### Bandwidth
$$ B = \omega_2 - \omega_1 = \frac RL = \frac{\omega_o}Q $$
- $B$ = Bandwidth
- $\omega_2, \omega_1$ = Half-power frequencies
- $R$ = Resistance
- $L$ = Inductance
- $Q$ = Quality Factor
- $\omega_o$ = Resonant frequency

##### [[Quality Factor]]
$$ Q = \frac{\omega_o L}R = \frac1{\omega_o CR} $$
- $Q$ = Quality Factor
- $\omega_o$ = Resonant Frequency
- $L$ = Inductance
- $C$ = Capacitance
- $R$ = Resistance

### Filters
##### [[Lowpass Passive Filter]] Transfer Funtion
$$ \boldsymbol H(\omega) = \frac1{1+i\omega RC} $$
- $\boldsymbol H(\omega)$ = Transfer function
- $i = \sqrt{-1}$
- $\omega$ = angular frequency
- $R$ = Resistance
- $C$ = Capacitance

##### [[Lowpass Passive Filter]] Cutoff Frequency
$$ \omega_c = \frac1{RC} $$
- $\omega_c$ = cutoff frequency
- $R$ = Resistance
- $C$ = Capacitance

##### [[Highpass Passive Filter]] Transfer Function
$$ \boldsymbol H(\omega) = \frac{i\omega RC}{1+i\omega RC} $$
- $\boldsymbol H(\omega)$ = Transfer function
- $i = \sqrt{-1}$
- $R$ = Resistance
- $C$ = Capacitance
- $\omega$ = angular frequency

##### [[Highpass Passive Filter]] Cutoff Frequency
$$ \omega_c = \frac1{RC} $$
- $\omega_c$ = cutoff frequency
- $R$ = Resistance
- $C$ = Capacitance

##### Passive [[Bandpass Filter]] Transfer Function
$$ \boldsymbol H(\omega) = \frac{R}{R+i(\omega L - \frac1{\omega C})} $$
- $\boldsymbol H(\omega)$ = Transfer Function 
- $R$ = Resistance
- $\omega$ = angular frequency
- $L$ = Inductance
- $C$ = Capacitance

##### Bandpass Filter Other Quantities
- Frequency Response ($|\boldsymbol I|$) = Same as defined for resonant circuit
- Average power ($P(\omega)$), Highest Average Power($P(\omega_o$)) and Power at Half-Power Frequencies ($P(\omega_1), P(\omega_2)$) = Same as defined above for resonant circuit
- Half power Frequencies ($\omega_1, \omega_2$) = Same as defined above for resonant circuit
- Cutoff frequencies = Half power Frequencies
- Centre Frequency = Resonant frequency ($\omega_o$)
- Bandpass ($B$) = Same as defined above for resonant circuit
- Quality Factor ($Q$) = Same as defined above for resonant circuit

##### Passive [[Bandstop Filter]] Transfer Function
$$ \boldsymbol H(\omega) = \frac{i(\omega L - \frac1{\omega C)}}{R+i(\omega L-\frac1{\omega C})} $$
- $\boldsymbol H(\omega)$ = Transfer Function 
- $R$ = Resistance
- $\omega$ = angular frequency
- $L$ = Inductance
- $C$ = Capacitance

##### Bandstop Filter Other Quantities
- Frequency Response ($|\boldsymbol I|$) = Same as defined for resonant circuit
- Average power ($P(\omega)$), Highest Average Power($P(\omega_o$)) and Power at Half-Power Frequencies ($P(\omega_1), P(\omega_2)$) = Same as defined above for resonant circuit
- Half power Frequencies ($\omega_1, \omega_2$) = Same as defined above for resonant circuit
- Cutoff frequencies = Half power Frequencies
- Centre Frequency = Resonant frequency ($\omega_o$)
- Bandpass ($B$) = Same as defined above for resonant circuit
- Quality Factor ($Q$) = Same as defined above for resonant circuit

##### [[Active Lowpass Filter]] Transfer Function
$$ \boldsymbol H(\omega) = -\frac{R_f}{R_i}\frac1{1+i\omega C_fR_f} $$
- $\boldsymbol H(\omega)$ = Transfer Function
- $R_f$ = Resistance of Resistor $f$ (across OpAmp)
- $R_i$ = Resistance of Resistor $i$ (Before Opamp)
- $i = \sqrt{-1}$
- $\omega$ = Angular Frequency
- $C_f$ = Capacitance of Capacitor $f$ (across OpAmp)

##### [[Active Lowpass Filter]] Cutoff Frequency
$$ \omega_c = \frac1{R_fC_f} $$
- $\omega_c$ = Cutoff Frequency
- $R_f$ = Resistance of Resistor $f$ (across OpAmp)
- $C_f$ = Capacitance of Capacitor $f$ (across OpAmp)

##### [[Active Highpass Filter]] Transfer Function is
$$ \boldsymbol H(\omega) = -\frac{i\omega R_fC_i}{1+i\omega R_iC_i} $$
- $\boldsymbol H(\omega)$ = Transfer Function
- $R_f$ = Resistance of Resistor $f$ (across OpAmp)
- $R_i$ = Resistance of Resistor $i$ (Before Opamp)
- $i = \sqrt{-1}$
- $\omega$ = Angular Frequency
- $C_i$ = Capacitance of Capacitor $i$ (Before Opamp)

##### [[Active Highpass Filter]] Cutoff Frequency
$$ \omega_c = \frac1{R_iC_i} $$
- $\omega_c$ = Cutoff Frequency
- $C_i$ = Capacitance of Capacitor $i$ (Before Opamp)
- $R_i$ = Resistance of Resistor $i$ (Before Opamp)

##### [[Bandpass Active Filter]] Transfer Function
$$ \boldsymbol H(\omega) = -\frac{R_f}{R_i}\frac1{1+i\omega C_1 R}\frac{i\omega C_2 R}{1+i\omega C_2 R} $$
- $\boldsymbol H(\omega)$ = Transfer Function
- $R_f$ = Inverter $f$ resistance (across OpAmp)
- $R_i$ = Inverter $i$ Resistance (Before Opamp)
- $\omega$ = angular frequency
- $C_1$ = Capacitor of Lowpass Filter
- $C_2$ = Capacitor of highpass Filter
- $R$ = Resistance of both resistors in both the lowpass filter and highpass filter

##### [[Bandpass Active Filter]] Cutoffs
$$ \omega_2 = \frac1{RC_1} $$
$$ \omega_1 = \frac1{RC_2} $$
- $\omega_2$ = Upper Cutoff Frequency
- $\omega_1$ = Lower Cutoff Frequency
- $R$ = Resistance of both resistors in both the lowpass filter and highpass filter
- $C_1$ = Capacitor of Lowpass Filter
- $C_2$ = Capacitor of highpass Filter

##### [[Bandpass Active Filter]] Other Quantities:
- $\omega_o$ = Resonant frequency = Centre Frequency = can be calculated same as in resonant circuit defined above
- $B$ = Bandwidth = can be calculated same as in resonant circuit defined above
- $Q$ = Quality Factor = can be calculated same as in resonant circuit defined above

##### [[Bandpass Active Filter]] Passband Gain
$$ K = |\boldsymbol H(\omega_o)| = \frac{R_f}{R_i}\frac{\omega_2}{\omega_1 + \omega_2} $$
- $K$ = Passband Gain
- $\boldsymbol H(\omega_o)$ = Transfer Function at resonant frequency/centre frequency
- $\omega_2$ = Upper Cutoff Frequency
- $\omega_1$ = Lower Cutoff Frequency
- $R_f$ = Inverter $f$ resistance (across OpAmp)
- $R_i$ = Inverter $i$ Resistance (Before Opamp)

##### [[Active Bandstop Filter]] Transfer Function
$$ \boldsymbol H(\omega) = -\frac{R_f}{R_i}(-\frac1{1+i\omega C_1R} - \frac{i\omega C_2R}{1+i\omega C_2 R}) $$
- $\boldsymbol H(\omega)$ = Transfer Function
- $R_f$ = Inverter $f$ resistance (across OpAmp)
- $R_i$ = Inverter $i$ Resistance (Before Opamp)
- $\omega$ = angular frequency
- $C_1$ = Capacitor of Lowpass Filter
- $C_2$ = Capacitor of highpass Filter
- $R$ = Resistance of both resistors in both the lowpass filter and highpass filter

##### [[Active Bandstop Filter]] Cutoffs
$$ \omega_1 = \frac1{RC_1} $$
$$ \omega_2 = \frac1{RC_2} $$
- $\omega_2$ = Upper Cutoff Frequency
- $\omega_1$ = Lower Cutoff Frequency
- $R$ = Resistance of both resistors in both the lowpass filter and highpass filter
- $C_1$ = Capacitor of Lowpass Filter
- $C_2$ = Capacitor of highpass Filter

##### [[Active Bandstop Filter]] Other Quantities:
- $\omega_o$ = Resonant frequency = Centre Frequency = can be calculated same as in resonant circuit defined above
- $B$ = Bandwidth = can be calculated same as in resonant circuit defined above
- $Q$ = Quality Factor = can be calculated same as in resonant circuit defined above

##### [[Active Bandstop Filter]] Passband Gain:
as $\omega\to 0$ and $\omega\to\infty$
$$ K = \frac{R_f}{R_i} $$
Not 100% sure this is correct like for pass band but:
$$ K = |\boldsymbol H(\omega_o)| = \frac{R_f}{R_i}\frac{2\omega_1}{\omega_1 + \omega_2} $$
- $K$ = Passband Gain
- $\boldsymbol H(\omega_o)$ = Transfer Function at resonant frequency/centre frequency
- $\omega_2$ = Upper Cutoff Frequency
- $\omega_1$ = Lower Cutoff Frequency
- $R_f$ = Inverter $f$ resistance (across OpAmp)
- $R_i$ = Inverter $i$ Resistance (Before Opamp)