![[Pasted image 20230405181559.png]]
- Let the applied voltage be:
$$ v(t) = V_m\cos(\omega t)\equiv V_m\angle0^o = \vec V $$
- This voltage is applied to a network of resistances, inductances, and capacitances ([[RLC Network]])
- The impedance of the circuit is:
$$ \vec Z = R+jX = |\vec Z|\angle\theta^o $$
- The phasor current is given by
$$ \vec I = \frac{\vec V}{\vec Z} = \frac{V_m\angle0^o}{|\vec Z|\angle\theta} = (\frac{V_m}{|\vec Z|})\angle-\theta = I_m\angle-\theta $$
### Pure Resistive Load
- When the circuit consists of pure resistance
$$ \vec Z = R+jX = R+j0 = R\angle 0^o $$
- Therefore, 
$$ \vec I = \frac{\vec V}{\vec Z} = \frac{V_m\angle 0^o}{R\angle0^o} = I_m\angle 0^o $$
- Where:
$$ I_m = \frac{V_m}{R} $$
- Since we know the voltage and current in phasor form, we can write equivalent waveforms in time domain and they are:
$$ v(t) = V_m\cos(\omega t) $$
$$ i(t) = I_m\cos(\omega t) $$
- Thus the instantaneaous power dissipated is given by:
$$ p(t) = v(t)i(t) = V_mI_m\cos^2(\omega t) $$
![[Pasted image 20230405182408.png]]

- It is noted that the voltage is in phase with current
- because p(t) is positive at all times, the energy flows continually from source to load and the average power is given by:
$$ P_{avg} = \frac{V_mI_m}2 $$

### Pure Inductive Load
- When the circuit consists of pure inductance
$$ \vec Z = 0+j\omega L = \omega L\angle 90^o $$
- Therefore:
$$ \vec I = \frac{\vec V}{\vec Z} = \frac{V_m\angle 0^o}{\omega L\angle 90^o} = I_m\angle-90^o $$
- Where:
$$ I_m = \frac{V_m}{\omega L} $$
- Since we know the voltage and current in phasor form, we can write equivalent waveforms in time domain and they are:
$$ v(t) = V_m\cos(\omega t) $$
$$ i(t) = I_m\cos(\omega t-90^o) = I_m\sin(\omega t) $$
- Thus, the instantaneuous power is given by:
$$ p(t) = v(t)i(t) = V_mI_m\cos(\omega t)\sin(\omega t) = \frac{V_mI_m}2\sin(2\omega t) $$
![[Pasted image 20230405183116.png]]
- It is noted that current lags the voltage by $90^o$
- Half the time the power is positive, showing that energy is delivered to the inductance, where it is stored in the magnetic field. For the other half the time power is negative, showing that the inductance returns the energy to the source
- The average power is zero. We say that reactive power flows from the source to the load

### Pure Capacitive Load
- When the circuit consists of pure inductance
$$ \vec Z = 0+\frac1{j\omega C} = \frac1{\omega C}\angle -90^o $$
- Therefore
$$ \vec I = \frac{\vec V}{\vec Z} = \frac{V_m\angle 0^o}{\frac1{\omega C}\angle -90^o} = I_m\angle 90^o $$
- Where
$$ I_m = \frac{V_m}{\frac{1}{\omega C}} $$
- Since we know the voltage and current in phasor form, we can write equivalent waveforms in time domain and they are
$$ v(t) = V_m\cos(\omega t) $$
$$ i(t) = I_m\cos(\omega t+90^o) = -I_m\sin(\omega t) $$
- Thus the instantaneous power is given by:
$$ p(t) = v(t)i(t) = -V_mI_m\cos(\omega t)\sin(\omega t) = -\frac{V_mI_m}{2}\sin(2\omega t) $$
- It is noted that current leads the voltage by $90^o$
- The power for capacitance carries the opposite sign as that for inductance. Thus reactive power is +ve for inductance and -ve for capacitance
- The average power is zero. We say that reactive power flows from the source to the load
![[Pasted image 20230405184255.png]]

### General Load
- This voltage is appled to a network of resistances, inductances, and capacitances (RLC network)
- The impedance of the network is:
$$ \vec Z = R+jX = |\vec Z|\angle\theta $$
- The phasor current in the circuit is given by:
$$ \vec I = \frac{\vec V}{\vec Z} = \frac{V_m\angle 0^o}{|\vec Z|\angle\theta} = \frac{V_m}{|\vec Z|}\angle-\theta^o = I_m\angle-\theta $$
$$ v(t) = V_m\cos(\omega t) $$
$$ i(t) = I_m\cos(\omega t - \theta^o) $$
- The voltage and current for a general RLC load for which the phase $\theta$ can be any value from $-90^o$ to $90^o$
- The instantaneous power is therefore iven by:
$$ p(t) = v(t)i(t) = V_mI_m\cos(\omega t)\cos(\omega t-\theta) $$
$$ p(t) = V_mI_m\cos\theta\cos^2\omega t + V_mI_m\sin\theta\cos\omega t\sin\omega t $$
$$ p(t) = \frac{V_mI_m}{2}\cos\theta(1+\cos2\omega t) + \frac{V_mI_m}2\sin]\theta\sin2\omega t $$
- Average power:
$$ P = \frac{V_mI_m}{2}\cos\theta $$
- It is noted that terms containing $\sin2\omega t$ and $\cos2\omega t$ have average values of 0
- Using the well known relationship
$$ V_{rms} = \frac{V_m}{\sqrt 2} $$
$$ I_{rms} = \frac{I_m}{\sqrt 2} $$
- The average power can be written as
$$ P = V_{rms}I_{rms}\cos\theta \;\; Watts $$
- The term $\cos\theta$ is called the [[Power Factor]]
- The power factor is the cosine of the phase difference between the voltage and the current
- It is also the cosine of the angle of the load impedance
- In our derivations we assumed the phase angle of the voltage to be zero. In general, if this value is $\theta_v$ and the corresponding phase angle of current is $\theta_i$ then:
$$ \theta = \theta_v - \theta_i $$
- $\theta$ is also called the [[Power Angle]]

##### [[Reactive Power]]
![[Reactive Power]]

##### [[Apparent Power]]
![[Apparent Power]]

### Power Calculations for General Load
- The impedance is 
$$\vec Z = R+jX = |\vec Z|\angle\theta^o$$
- Where R is the Resistance of the load and X is the reactance. This is illustrated in the diagram.
![[Pasted image 20230405194538.png]]
- From the figure 
$$ \cos(\theta) = \frac{R}{|\vec Z|} $$
$$ \sin(\theta) = \frac{X}{|\vec Z|} $$
- The average power is given by:
$$ P = \frac{V_mI_m}{2}\cos\theta = V_{rms}I_{rms}\cos\theta = \frac{I_m^2}2R = I_{rms}^2R $$
- Similarily the reactive power is given by:
$$ Q = \frac{V_mI_m}2\sin\theta = \frac{V_mI_m}2\frac{X}{|\vec Z|} = I_{rms}^2X = V_{rms}I_{rms}\sin\theta $$
- The apparent power is given by:
$$ S = \frac{V_mI_m}2 = V_{rms}I_{rms} $$

### [[Complex Power]]
![[Complex Power]]

### [[Law of Conservation of AC Power]]
![[Law of Conservation of AC Power]]
