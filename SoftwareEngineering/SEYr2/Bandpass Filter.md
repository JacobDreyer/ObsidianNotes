- An [[RLC Resonance Circuit]] provides a bandpass filter when the output is taken off the [[Resistors]]
![[Pasted image 20230420173759.png]]
- The [[Transfer Function]] is given by:
$$ H(\omega) = \frac{V_0}{V_i} = \frac R{R+j(\omega L - \frac1{\omega C})} $$
- The [[Frequency Response]] of the circuit's current magnitude is given by:
$$ |I| = \frac{V_m}{\sqrt{R^2 + (\omega L - \frac1{\omega C})^2}} $$
- current amplitude vs frequency for the bandpass filter:
![[Pasted image 20230420174053.png]]
- The average [[Power]] dissipated by the [[RLC Circuit]] is given by:
$$ P(\omega) = \frac12|I|^2R $$
- The highest power is dissipated at [[Resonance]]
$$ P(\omega_o) = \frac12(\frac{V_m}R)^2R = (\frac{V_m}{\sqrt 2})^2\frac1R $$
- At $\omega = \omega_1,\omega_2$ the dissipated power is half the maximum power value, that is:
$$ P(\omega_1) = P(\omega_2) = \frac{(\frac{V_m}{\sqrt 2})^2}{2R} = \frac{V_m^{\;2}}{4R} $$
- $\omega_1, \omega_2$ are called [[Half-Power Frequencies]]
- The half-power frequencies are obtained by setting magnitude of current at half-power frequencies ($\omega_1$ and $\omega_2$) equal to $\frac1{\sqrt 2}\times$ magnitude of current at resonant frequency ($\omega_0$). That is:
$$ \frac{V_m}{|Z|} = \frac{V_m}{\sqrt{R^2 + (\omega L - \frac1{\omega C})^2}}  = \frac{V_m}{\sqrt 2R} $$
- Or:
$$ |Z| = \sqrt 2R $$
- That is:
$$ \sqrt{R^2 + (\omega L - \frac1{\omega C})^2} = \sqrt 2R $$
- Simplifying we get:
$$ \omega L - \frac1{\omega C} = \pm R $$
- to obtain $\omega_2$ we solve:
$$ \omega L - \frac1{\omega C} = +R $$
$$ \omega_2 = +\frac R{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} $$
- Similarily, for $\omega_1$, we can solve:
$$ \omega L - \frac1{\omega C} = -R $$
$$ \omega_1 = -\frac{R}{2L} + \sqrt{(\frac{R}{2L})^2 + \frac1{LC}} $$
- The [[Bandwidth]] of the circuit is defined as:
$$ B = \omega_2 - \omega_1 $$
![[Pasted image 20230420175503.png]]
- The bandpass filter passes a band of frequencies $\omega_1 < \omega < \omega_2$ centered on $\omega_0$
- The centre frequency is given by:
$$ \omega_0 = \frac1{\sqrt{LC}} $$
- Since the bandpass filter is a [[Series Resonant Circuit]], the [[Half-Power Bandwidth]], the [[Bandwidth]], and [[Quality Factor]] are given by:
$$ \omega_1 = -\frac{R}{2L} + \sqrt{(\frac{R}{2L})^2 + \frac1{LC}} $$
$$ \omega_2 = +\frac R{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} $$
$$ B = \omega_2 - \omega_1 = \frac RL = \frac{\omega_0}Q $$
$$ Q = \frac{\omega_0 L}{R} = \frac1{\omega_0 CR} $$
- The bandpass filter can also be formed by cascading the [[Lowpass Passive Filter]] (with cutoff frequency = $\omega_2$) with the [[Highpass Passive Filter]] (with cutoff frequency = $\omega_1$)