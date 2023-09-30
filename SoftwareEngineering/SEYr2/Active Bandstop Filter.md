- A bandstop filter can be contstructed by parallel combination of a lowpass filter and a highpassfilter and a [[Summing Amplifier]]:
![[Pasted image 20230420222711.png]]
![[Pasted image 20230420222947.png]]
- Such a filter is also refered to as a [[Notch Filter]]
- Frequency response:
![[Pasted image 20230420222752.png]]
- The filter is designed such that the lower cutoiff frequency $\omega_1$ is set by the lowpass filter while the upper [[Cutoff Frequency]] $\omega_2$ is set by the highpass filter
- The gap between $\omega_1$ and $\omega_2$ is the [[Bandwidth]] of the filter
- The filter passes frequencies below $\omega_1$ and above $\omega_2$
- The [[Transfer Function]] is given by:
$$ H(\omega) = \frac{V_0}{V_i} = -\frac{R_f}{R_i}(-\frac1{1+j\omega C_1R} - \frac{j\omega C_2 R}{1+j\omega C_2 R}) $$
- The lowpass section sets the lower [[Cutoff Frequency]] as:
$$ \omega_1 = \frac1{RC_1} $$
- While the highpass section sets the upper cutoff frequency as:
$$ \omega_2 = \frac1{RC_2} $$
- Therefore the centre frequency is:
$$ \omega_o = \sqrt{\omega_1\omega_2} $$
- [[Bandwidth]] is:
$$ B = \omega_2 - \omega_1 $$
- and [[Quality Factor]] is:
$$ Q = \frac{\omega_o}B $$
- The [[Passband Gain]] is given by:
$$ K = \frac{R_f}{R_i} $$
- The magnitude of [[Transfer Function]] at $\omega_o$ is given by:
$$ |H(\omega_o)| = \frac{R_f}{R_i}\times\frac{2\omega_1}{\omega_1 + \omega_2} $$
