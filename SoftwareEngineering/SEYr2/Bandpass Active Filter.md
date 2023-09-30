- an [[Active Lowpass Filter]] may be combined with an [[Active Highpass Filter]] to form an active bandpass filter, that will have a gain $K$ over the required range of frequencies
![[Pasted image 20230420221256.png]]
![[Pasted image 20230420221439.png]]
- The block diagram shows cascade of a [[Unity-gain lowpass filter]], [[Unity-gain highpass filter]], and an [[Inverter]] with gain $-\frac{R_f}{R_i}$
![[Pasted image 20230420221421.png]]
- The analysis of a bandpass filter is relatively simple. Its [[Transfer Function]] is obtained by multiplying transfer functions of lowpass filter, highpass filter, and the inverter.
$$ H(\omega) = \frac{V_0}{V_i} = (-\frac1{1+j\omega C_1R})(-\frac{j\omega C_2R}{1+j\omega C_2R})(-\frac{R_f}{R_i}) $$
- The lowpass section sets the upper [[Cutoff Frequency]] as:
$$ \omega_2 = \frac1{RC_1} $$
- while the highpass section sets the lower [[Cutoff Frequency]] as:
$$ \omega_1 = \frac1{RC_2} $$
- Centre frequency:
$$  \omega_o = \sqrt{\omega_1\omega_2} $$
- [[Bandwidth]]
$$ B = \omega_2-\omega_1 $$
- [[Quality Factor]]
$$ Q = \frac{\omega_o}{B} $$
- To find the [[Passband Gain]] $K$, we can write the transfer function as:
$$ H(\omega) = -\frac{R_f}{R_i}\frac{j\frac\omega{\omega_1}}{(1+j\frac\omega{\omega_1})(1+j\frac\omega{\omega_2})} = -\frac{R_f}{R_i}\frac{j\omega\omega_2}{(\omega_1 + j\omega)(\omega_2+j\omega)} $$
- At the centre frequency $\omega_o$ the magnitude of the transfer function is:
$$ |H(\omega)| = |-\frac{R_f}{R_i}\frac{j\omega_o\omega_2}{(\omega_1 + j\omega_o)(\omega_2+j\omega_o)}| = \frac{R_f}{R_i}\frac{\omega_2}{\omega_1 + \omega_2} $$
- Which is the [[Passband Gain]]
