##### Note Info
Date: 2022/04/15
Course: Engineering
Class: [[Physics]]
Unit: Electrostatics
## Capacitors
##### Function:
- A [[Passive Device]] that stores energy directly into an [[Electric Field]] (its electric field
- The energy can be released by allowing the [[electric charge]]s to move
- This allows a cpacitor to store up energy and release it much quicker than something like a battery
- When a [[Voltage Source]] $v$ is connected to the capacitor, the source deposits a [[positive charge]] $+q$ on one plate and a [[negative charge]] $-q$ on the other
- The amount of [[Electric Charge]] stored by the capacitor $q$ is directly proportional to the applied [[voltage]] $v$ so that:
$$ q = Cv $$
- Where $C$ is a constant of proportionality known as the [[Capacitance]] of the Capacitor
- The unit of Capacitance is [[Farad]] (F), in honor of the [[English]] physicist [[Michael Faraday]]

##### Types
- The simplest example of a capacitor is two parallel plates that are [[Conductor]] seperated by a small gap
- Type of Capacitor depends on the dielectric material used in the construction
	- Common Types:
		- [[Polyester Capacitor]]
		- [[Ceramic Capacitor]]
		- [[Electrolyte Capacitor]]

##### More Info:
- Besides [[Resistors]], capacitors are the most common electrical components
- Capacitors are used extensively in [[Electronics]], [[Communications]], [[Computers]], and [[Power Systems]]

##### Construction:
- Capacitors are constructed by seperating two sheets of [[Conductor]] ([[Metallic]]) by a thin layer of [[insulating]] ([[Dielectric]], [[Inductor]]) material
- In a [[Parallel-Plate Capacitor]], the sheets are flat and parallel
- The insulating material between the plates, called a [[Dielectric]], can be [[air]], [[Mylar]], [[Polyester]], [[Polypropylene]], [[mica]], etc.

##### Characteristics:
- It is noted that when the [[voltage]] across a capacitor is not changing with time (DC voltage), the [[Current]] is 0
- A Capacitor is an open circuit to dc
- However, if a [[battery]] (dc voltage) is connected across a capacitor, the capacitor charges
- The voltage on a capacitor cannot change abrubtly
- Capacitor resists abrupt change in voltage across it
- Conversly, the current through a capacitor can change instantaneously
- the ideal capacitor does not dissipate energy
- Capacitors take [[power]] from the [[circuit]] when storing energy in its field and returns previously stored energy when delivering power to a circuit

The Circuit symbol for a Capacitor:
![[Pasted image 20230228210043.png]]

## Calculations
#### [[Current]] across a Capacitor:
$$ i = C\frac{dv}{dt} $$
##### Energy stored in the Capacitor that can be Returned to the [[Circuit]]
$$ w(t) = \frac12Cv^2(t) = \frac{q^2(t)}{2C} $$
##### Charge on a Capacitor
$$ q(t) = \int_{t_0}^ti(t)dt + q(t_0) $$
##### [[Voltage]] across a Capacitor
$$ v(t) = \frac1C\int_{t_0}^ti(t)dt + v(t_0) $$
Where:
$$ v(t_0) = \frac{q(t_0)}{C} $$


#### Capacitors in [[Parallel]]
- The equivalent [[Capacitance]] of N parallel-connected capacitors is the sum of the individual capacitances:
$$ C_{eq} = C_1 + C_2 + \cdots C_N $$

#### Capacitors in [[Series]]
$$ \frac1{C_{eq}} = (\frac{1}{C_1} + \frac{1}{C_2} + \cdots + \frac{1}{C_N}) $$

#### Cylinder Capacitor
$$ E = \frac{2k\lambda}{r} $$
- $\lambda$ = $Q/l$
	- $Q$ = total charge
	- $l$ = length of cylinder
- $r$ = ????

$$ \Delta V = \frac{2kQ}{l}\ln(b/a) $$
- $Q$ = total charge
- $l$ = length of cylinder
- $a$ = radius of inner cyclinder
- $b$ = radius to inner edge of outer cylinder

$$ C = \frac l{2k\ln(b/a)} $$
- $l$ = length of cylinder
- $a$ = radius of inner cylinder
- $b$ = radius to inner edge of outer cylinder 

### [[Capacitance]]
![[Capacitance]]
