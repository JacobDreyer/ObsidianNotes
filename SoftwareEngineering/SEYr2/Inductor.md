- An inductor is a [[Passive Device]] designed to store [[Energy]] in its [[Magnetic Field]] and finds numerous applications in [[Electronic]] and [[Power Systems]]
- Common Applications include [[Power Supply]]s, [[Transformer]]s, [[Radio]]s, [[TV]]s, [[Radar]]s, and [[Electric Motors]]
- An inductor consists of a coil of [[Conductor]] wire
- To enhance the inductive effect, a practical inductor is usually formed into a cylindrical coil with many turnings of wire
- If [[Current]] is allowed to pass through an inductor, it is found that the [[Voltage]] across the inductor is directly proportional to the time rate of change of the current:
$$ v(t) = L\frac{di(t)}{dt} $$
- Where L is the [[Constant of Proportionality]] called the [[Inductance]] of the inductor
- The unit of inductance is [[Henry]] (H), named in honour of the [[American]] inventor [[Joseph Henry]]
	- [[Inductance]] is the property whereby an inductor exhibits opposition to the change of current flowing through it

### Characteristics
- It is noted that when [[voltage]] across an inductor is zero, then the current is constant
- An inductor is a short circuit to dc
- A discontinuous change in the [[current]] through an inductor requires an infinite voltage which is physically not possible
- The inductor opposes an abrupt change in [[current]] through it
- conversely, the [[voltage]] across an inductor can change abruptly
- an ideal inductor does not dissipate energy
- Inductor takes power from circuit when storing energy in its magnetic field and returns previously stored energy when delivering power to the circuit

##### Circuit Symbol:
![[Pasted image 20230228213414.png]]

### Current:
$$ i(t) = \frac1L\int^t_{t_0}v(t)dt + i(t_0) $$
### Voltage:
$$ p(t) = v(t)i(t) = L\frac{di(t)}{dt}i(t) $$
### Energy Stored in an Inductor
$$ w(t) = \int_0^{i(t)}Li(t)di(t) = \frac12Li^2(t) $$

### Inductances in Series
$$ L_{eq} = (L_1 + L_2 + L_3) $$
### Inductances in Parallel
$$ L_{eq} = \frac1{\frac1{L_1} + \frac1{L_2} + \frac1{L_3}} $$
