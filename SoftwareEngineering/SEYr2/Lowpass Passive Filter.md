- A lowpass filter is formed when the output of an [[RC Circuit]] is taken off the capacitor
![[Pasted image 20230420172354.png]]
- The [[Transfer Function]] is given by:
$$ H(\omega) = \frac{V_0}{V_i} = \frac1{1+j\omega RC} $$
![[Pasted image 20230420172539.png]]
- The [[Half-Power Frequencies]] in the context of filters is referred to as the [[Cutoff Frequency]], $\omega_c$
- The cutoff frequency is obtained by setting the magnitude of $H(\omega)$ equal to $\frac1{\sqrt 2} = .707$
- Thus:
$$ |H(\omega_c)| = \frac1{\sqrt{1+\omega_c^2R^2C^2}} = \frac1{\sqrt 2} = .707 $$
- That is, the [[Cutoff Frequency]] is given by:
$$ \omega_c = \frac1{RC} $$
- The [[Cutoff Frequency]] is the frequency at which the [[Transfer Function]] $H$ drops in magnitude to $70.71\%$ of it's maximum value
- The cutoff frequency is also the frequency at which the [[Power]] dissipated in a circuit is half of it's maximum value
- A lowpass filter is designed to only pass frequencies from dc up to the cutoff frequency
- A lowpass filter can also be formed when the output of an [[RL Circuit]] is taken off the resistance