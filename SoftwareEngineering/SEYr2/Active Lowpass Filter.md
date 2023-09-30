![[Pasted image 20230420181359.png]]
- The components selected for $Z_i$ and $Z_f$ determine whether the filter is lowpass or highpass (one of the components must be reactive)
- A lowpass filter:
![[Pasted image 20230420181522.png]]
$$ H(\omega) = \frac{V_0}{V_i} = -\frac{Z_f}{Z_i} $$
$$ Z_i = R_i $$
$$ Z_f = R_f||(\frac1{j\omega C_f}) $$
$$ H(\omega) = -\frac{R_f}{R_i}\frac1{1+j\omega C_fR_f} $$
- The [[Transfer Function]] is similar to the transfer function of [[Lowpass Passive Filter]], except that there is a low frequency ($\omega\to 0$) gain or dc gain of $-\frac{R_f}{R_i}$. The corner or [[Cutoff Frequency]] is given by:
$$ \omega_c = \frac1{R_fC_f} $$