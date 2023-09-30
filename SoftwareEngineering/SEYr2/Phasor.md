- [[Steady-State Sinusoidal Analysis]] is greatly simplified if the currents and voltages are represented as [[Vector]]s, also called Phasors
- When applying [[KCL]] and [[KVL]] in [[AC Circuit]]s, we may see expressions of the form:
$$ v(t) = 10\cos(\omega t) + 5\sin(\omega t + 60^o) + 5\cos(\omega t + 90^o)\quad (1) $$
- To obtain the peak value of $v(t)$ and it's [[Phase Angle]], we need to express equation (1) in the standard form
$$ v(t) = V_m \cos(\omega t + \theta) $$
- This could be accomplished by using [[Trig Identities]] which is too tedious work
- Instead we can represent each term in (1) by a vector in the [[Complex Number Plane]] known as a Phasor
- Then we can add the phasors with relative ease and convert the sum into the desired form
- For a sinusoidal signal or voltage of the form:
$$ v_1(t) = V_1\cos(\omega t+\theta_1) $$
- We define the phasor as:
$$ \boldsymbol V_1 = V_1\angle\;\theta_1 $$
- The phasor for a [[Sinusoid]] is a [[Complex Number]] having a magnitude equal to the peak value and having the same [[Phase Angle]] as the sinusoid
- Boldface letters are used for phasors. Many authors use $\vec V$ to denote phasors

- Example:
- If the sinusoid is: 
$$ v_2(t) = V_2\sin (\omega t + \theta_2) $$
- We need to express sin in terms of cos using:
$$ \sin(z) = \cos(z-90^o) $$
- Thus:
$$ v_2(t) = V_2\cos(\omega t + \theta_2 - 90^o) $$
- Then the phasor represnetation of $v_2(t)$ becomes
$$ \boldsymbol V_2 = V_2\angle(\theta_2-90^o) $$
- Like [[Voltage]]s sinusoidal currents are expressed in a similar manner
- For example, if the current is:
$$ i_1(t) = I_1\cos(\omega t + \theta_1) $$
- It is expressed in phasor form as:
$$ \boldsymbol I_1 = I_1\angle\theta_1 $$

### Adding Sinusoids using Phasors
- If the voltage signal is:
$$ v(t) = 10\cos(\omega t) + 5\sin(\omega t + 60^o) + 5\cos(\omega t+90^o) $$
- This can be expressed as:
$$ v(t) = 10\cos(\omega t) + 5\cos(\omega t-30^o) + 5\cos(\omega t + 90^o) $$
- Using [[Euler's Formula]]
$$ Cos(\theta) = Re(e^{j\theta}) = Re(\cos\theta + j\sin\theta) $$
- Where $Re()$ means that we retain only the real part of the quantity inside the parentheses
- and $j = \sqrt{-1}$
$$ v(t) = Re[10e^{j\omega t}] + Re[5e^{j(\omega t - 30^o)}] + Re[5e^{j(\omega t+90^o)}] $$
- We can write this as
$$ v(t) = Re[(10\angle0^o + 5\angle-30^o + 5\angle 90^o)e^{j\omega t}] $$
- We can write the complex numbers as:
$$ = 10\angle0^o + 5\angle-30^o + 5\angle90^o $$
$$ = 10+4.33-j2.50+j5 $$
$$ = 14.33 + j2.5 $$
$$ = 14.54\angle9.90^o $$
$$ = 14.54e^{j9.90^o} $$
- Thus the voltage can be written as:
$$ v(t) = Re[(14.54e^{j9.90^o})e^{j\omega t}] $$
$$ = Re[14.54e^{j(\omega t + 9.90^o)}] $$
$$ = 14.54\cos(\omega t + 9.90^o) $$
- This the sum of the 3 sinusoids can be written as one sinusoid
- To add sinusoids, we will first write the phasor for each term in the sum, add the phasors by using complex number arithmatic, and then write the simplified expression for the sum

### [[Phasors as Rotating Vectors]]
![[Phasors as Rotating Vectors]]

### [[Phase Relationship]]
![[Phase Relationship]]

### [[Complex Impedance - Inductance]]
![[Complex Impedance - Inductance]]
