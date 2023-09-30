- Consider an [[Inductance]] in which the [[Current]] is given by:
$$ i_L(t) = I_M\sin(\omega t+\theta) $$
- The voltage across an inductance then is given by:
$$ v_L(t) = L\frac{di_L(t)}{dt} $$
- Substituting the value of $i_L(t)$, we obtain
$$ v_L(t) = \omega LI_m\cos(\omega t+\theta) $$
- Expressing the voltage and current in [[Phasor]] form we get:
$$ \boldsymbol I_L = I_m\angle\theta-90^o $$
$$ \boldsymbol V_L = \omega LI_m\angle\theta = V_m\angle\theta $$
- The phasor diagram:
![[Pasted image 20230404191522.png]]
- The voltage phasor is given by:
$$  \boldsymbol V_L = \omega LI_m\angle\theta = V_m\angle\theta  $$
- Which can be written as:
$$ \boldsymbol V_L = (\omega L\angle 90^o)\times I_m\angle\theta-90^o $$
- But:
$$ \vec I_L = I_m\angle\theta-90^o $$
$$ \omega L\angle 90^o = j\omega L $$
- Thus:
$$ \vec V_L = (j\omega L)I_L $$
- Where $j\omega L$ is referred to as the [[Impedance]] of the [[Inductance]] and is denoted as $Z_L$
- and:
$$ \vec V_L = \vec Z_L\vec I_L $$
- The [[Phasor]] [[Voltage]] is equal to the impedance times the phasor current
- This is [[Ohms Law]] in [[Phasor]] form
- Impedances, in general are written as:
$$ \vec Z = R + jX $$
- Where $R$ is the resistive part and $X$ is the reactive part
- For a pure inductance $R=0$ and $X = \omega L$
- For a [[Capacitance]] we can similarily show the relationship between voltage and current phasors as:
$$ \vec V_C = \vec Z_C\vec I_C $$
- and:
$$ \vec Z_C = \frac1{j\omega C} = -j\frac1{\omega C} = \frac1{\omega C}\angle -90^o $$
- if:
$$ \vec V_C = V_m\angle \theta $$
- Then:
$$ \vec I_C = I_m\angle\theta+90^o $$
- And:
$$ \vec I_C = \frac{\vec V_C}{\vec Z_C} $$
![[Pasted image 20230404192626.png]]
- For a [[Resistance]], the phasors are related by:
$$ \vec V_R = R\vec I_R $$
- Because the resistance is real, the current and voltages are in phase
- If:
$$ \vec V_R = V_m\angle\theta $$
- Then:
$$ \vec I_R = I_m\angle\theta $$
- and:
$$ \vec I_R = \frac{\vec V_R}R $$
![[Pasted image 20230404192854.png]]

### Summary of Voltage Current Relationships
![[Pasted image 20230404192945.png]]

### [[Circuit Analysis using Impedances]]
![[Circuit Analysis using Impedances]]

### [[Mathematical Operations using Phasors]]
![[Mathematical Operations using Phasors]]
