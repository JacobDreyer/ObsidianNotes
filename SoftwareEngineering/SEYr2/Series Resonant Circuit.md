### [[Resonance in AC Circuits]]
![[Resonance in AC Circuits]]

- Consider the [[RLC Circuit]] in the [[Frequency-Domain]] shown below:
![[Pasted image 20230418113417.png]]
- The input [[Impedance]] is given by:
$$ Z = H(\omega) = \frac{V_s}{I} = R+j\omega L + \frac1{j\omega C} $$
$$ Z = R + j(\omega L - \frac1{\omega C}) $$
- Resonance occurs when the imaginary part of the transfer function is zero. that is:
$$ Im(Z) = 0 = (\omega L - \frac1{\omega C}) $$
- The value of $\omega$ that satisfies this condition is called the [[Resonant Frequency]] $\omega_o$ and is given by:
$$ 0 = (\omega_o L - \frac1{\omega_o C}) $$
- Thus the resonant frequency is given by:
$$ \omega_o = \frac1{\sqrt{LC}}\;rad/s $$
- Since $\omega_o = 2\pi f_o$
$$ f_0 = \frac1{2\pi\sqrt{LC}}\;Hz $$
- At resonance:
	- The impedance is purely resistive, $Z = R$. That is, the LC combination acts like a short circuit and entire voltage appears across R
	- The voltage $V_s$ and $I$ are in phase, so that the [[Power Factor]] is unity
	- The magnitude of the transfer function $H(\omega) = Z(\omega)$ is minimum 
	- The inductor voltage and capacitor voltage can be much more than the source voltage
$$ |V_L| = \frac{V_m}R\omega_o L $$
$$ |V_C| = \frac{V_m}{R}\frac1{\omega_o C} $$
- The frequency response of the circuit's current magnitude is given by:
$$ I = |I| = \frac{V_m}{\sqrt{R^2 + (\omega L - \frac1{\omega C})^2}} $$
- Current amplitude vs frequency
![[Pasted image 20230418114535.png]]
- The average power dissipated by the RLC circuit at resonance is given by
$$ P(\omega) = \frac12{I^2}R $$
- The highest value of power disspated occurs when:
$$ I = \frac{V_m}R $$
- This occurs at $\omega = \omega_o$. the average power at this frequency is
$$ P(\omega_o) = \frac12\frac{V_m^2}{R} $$
### [[Half-Power Frequencies]]
![[Half-Power Frequencies]]

### [[Quality Factor]]
![[Quality Factor]]

- The sharpness of the frequency response of the RLC circuit is determined by the [[Quality Factor]] Q
- The higher the value of Q, the more selective the circuit is but smaller the [[Bandwidth]]
![[Pasted image 20230418122305.png]]
- The [[Selectivity]] of an [[RLC circuit]] is the ability to respond to a certain frequency and discriminate against all others
- The relationship between [[Bandwidth]] and [[Quality Factor]] is given by:
$$ B = \frac RL = \frac{\omega_o}{Q} $$
- Also, for large Q (Greater than 10)
$$ \omega_1 \cong \omega_o-\frac B2;\quad\omega_2\cong\omega_o+\frac B2 $$
- Using 
$$  B = \frac RL = \frac{\omega_o}{Q}  $$
- and
$$ \omega_o = \frac1{\sqrt{LC}} $$
- [[Half-Power Frequencies]] can be expressed as:
$$ \omega_1 = -\frac{\omega_o}{2Q} + \omega_o\sqrt{1+(\frac1{2Q})^2} $$
$$ \omega_2 = +\frac{\omega_o}{2Q} + \omega_o\sqrt{1+(\frac1{2Q})^2} $$
