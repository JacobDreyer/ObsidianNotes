- At certain frequencies $\omega = \omega_1 = \omega_2$
- The average power dissipated is half the average power at $\omega = \omega_o$. That is:
$$ P(\omega_1) = P(\omega_2) = \frac12\frac{(V_m/\sqrt 2)^2}{R} = \frac{V_m^2}{4R} $$
- Hence $\omega_1$ and $\omega_2$ are called [[Half-Power Frequencies]]
- The half power frequencies are obtained by setting the magnitude of current at half-power frequencies ($\omega_1$ and $\omega_2$) equal to $\frac1{\sqrt 2}\times$ magnitude of current at resonant frequency ($\omega_o$). That is:
$$ \frac{V_m}{|Z|} = \frac{V_m}{\sqrt{R^2 + (\omega L - \frac1{\omega C})^2}} = \frac{V_m}{\sqrt2 R} $$
- Or:
$$ |Z| = \sqrt2R $$
- That is:
$$ \sqrt{R^2 + (\omega L - \frac1{\omega C})} = \sqrt2R $$
- Squaring both sides and simplifying, we get:
$$ \omega L - \frac1{\omega C} = \pm R $$
- Solving the above equation, we can obtain half-power frequencies
- That is:
$$ \omega_1 = -\frac R{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} $$
$$ \omega_2 = +\frac R{2L} + \sqrt{(\frac R{2L})^2 + \frac1{LC}} $$
- The relationship between half-power frequencies and resonant frequency is given by:
$$ \omega_o = \sqrt{\omega_1\omega_2} $$
- The resonant frequency thus is the geometric mean of the half-power frequencies
- The [[Bandwidth]] of the [[RLC Circuit]] is given by:
$$ B = \omega_2 - \omega_1 $$
- $B$ is also refered to as [[Half-Power Bandwidth]]

- Using 
$$  B = \frac RL = \frac{\omega_o}{Q}  $$
- and
$$ \omega_o = \frac1{\sqrt{LC}} $$
- [[Half-Power Frequencies]] can be expressed as:
$$ \omega_1 = -\frac{\omega_o}{2Q} + \omega_o\sqrt{1+(\frac1{2Q})^2} $$
$$ \omega_2 = +\frac{\omega_o}{2Q} + \omega_o\sqrt{1+(\frac1{2Q})^2} $$