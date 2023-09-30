- They are materials that have properties in between that of [[Conductor]]s and [[Insulators]]
	- Ex: [[Silicon]], [[Germanium]], [[Gallium Arsenide]]
- A semiconductor is a substance, a solid chemical element or compound, that can conduct electricity under some conditions, making it a good medium for the control of electrical current
- Most electronic devices are fabricated using [[Silicon]]
- The [[Lattice Structure]] of [[Silicon]]:
![[Pasted image 20230423123248.png]]
- At sufficiently high temperatures, thermal energy causes the atoms in the lattice to vibrate
- When sufficient [[Kinetic Energy]] is present, some of the [[Valence Electrons]] break with the lattice and become availible for conduction of current
- As the temperature increases, more free [[Electrons]] become availible for conduction
- The [[Resistance]] of semiconductor material decreases as the temperature increases
- Thus, many of the semiconductor properties are a function of the temperature

### Doping of SemiConductor
- The semiconductor is a relatively poor conductor of electric current, as current requires move of charge
- Semiconductor in this situation is termed as [[Intrinsic]]
- To create semiconductor material that can more easily conduct, it must be [[Doped]]
- Doping is the process of adding precise amounts of very small concentration of certain so-called impurities called [[Dopants]]
- By doping we can create two types of semiconductors: [[P-type Semiconductor]] and [[N-type Semiconductor]]
- One of the common impurities added is [[Arsenic]] (As); each atom has 5 [[Valence Electrons]]. The doped semiconductor becomes a [[N-type Semiconductor]]
- To create a [[P-type Semiconductor]] [[Boron]] (B) is added to an [[Intrinsic Semiconductor]]; Boron has 3 [[Valence Electrons]]
![[Pasted image 20230423124131.png]]

### [[Semiconductor Diode]]
- In [[N-type Semiconductor]]s current is predominately by means of free electrons
- Thus, in n-type semiconductors, the [[Majority Carrier]]s are [[Electrons]]
- In [[P-type Semiconductor]]s current is due to holes or [[positive charge]]s
- Thus in a p-type semi-conductor, the [[Majority Carrier]]s are holes or positive charges
- A [[P-N Diode]] can be created by bringing together a p- and n-type region within the same semiconductor lattice:
![[Pasted image 20230423124602.png]]
- When the junction is formed, the electrons from their region of high concentration in n material diffuse into p material
- Simultaneously, high density holes in the p material diffuse into n material
- Thus, p-n junction is formed, refered to as the [[Depletion Region]]

### [[Ideal Diode]] Circuit Model
- Ideal diode is simply an idealized two terminal electronic device
- For an Ideal Diode:
	- Rule 1: if the voltage on the p-side is made more positive than the voltage on the n-side ([[Forward Bias]]), then the ideal diode conducts current as a closed switch
	- Rule 2: if the voltage on the n-side is made more positive than the voltage on the p-side ([[Reverse Bias]]), then the ideal diode will not conduct, and appears as an open switch
![[Pasted image 20230423125329.png]]
![[Pasted image 20230423125353.png]]
### Circuit with [[Ideal Diode]]
- Consider the circuit shown in the figure, which consists of a 1.5V battery, an [[Ideal Diode]], and a $1k\ohm$ [[Resistors]]
![[Pasted image 20230423125554.png]]
- A technique is required to determine whether this diode is conducting or not
- To do this, we first assume that the diode is conducting (or equivalently $V_D\geq 0$)
- This enables us to substitute a short circuit in place of the diode.
- Since the diode is now represented by a short circuit, $V_D = 0$
- The series current is given by:
$$ i_D = \frac{1.5}{1000} = 1.5mA $$
- Since the direction of the current and the diode voltage are consistent with the assumption that the diode is forward biased it must be concluded that the diode is indeed conducting'
- Suppose that the diode is reverse biased. (The diode is replaced by an open circuit)($V_D$ is the voltage across it)
- Apply [[KVL]]:
$$ 1.5 = v_D + 1000\times i_D $$
- But the result $v_D = 1.5V$ is contrary to the initial assumption that $v_D < 0$
- Thus assuming that the diode is OFF leads to an inconsistent answer
- Therefore the diode must be conducting

##### Steps to Determine Conduction State of Ideal Diode
1. Assume a diode conduction state (ON or OFF)
2. Substitute ideal diode model into circuit (short circuit if ON, and open circuit if OFF)
3. Solve for diode current and voltage, using linear circuit analysis techniques
4. If the solution is consistent; the assumption is right. If it is inconsistent; the assumption is wrong and is in the opposite conduction state

### [[Rectification]] (Converting [[AC]] to [[DC]])
- One of the important applications of semiconductor diodes is rectification
- Rectification means the ability to convert AC signal with ZERO Average (DC) value to signal with non-zero average DC value
- The application of the semiconductor diode as a rectifier is veryu usefull in obtaining dc voltage supplies from the readily avalible AC line voltage
![[Pasted image 20230423133505.png]]
- The diode will conduct only when the input voltage is +ve and the diode is off when the input is negative
- Rectifier input and output:
![[Pasted image 20230423133614.png]]
- When the diode is conducting, the unknown $v_L$ and $i_D$ are given by:
$$ i_D = \frac{v_i}{R_L},\; when\; v_i>0 $$
$$ v_L = i_DR_L $$
- The average value of the load voltage is obtained by integrating the load voltage over one period and dividing by the period
$$ V_{L,DC} = \frac{\omega}{2\pi}\int_0^{\pi/\omega}155.56\sin(\omega t)dt $$
- The rectification circuit is refered to as [[HALF-WAVE rectifier]], since it preserves only one-half of the waveform

### [[Full-Wave Rectifier]]
- A Half-wave Rectifier is one simple method of converting AC energy to DC energy
- A half-wave rectifier, however, is not a very efficient AC-DC conversion circuit, because it fails to utilize one-half the energy availible in the AC energy
- Another rectifier commonly availible off the shelf as a single integrated circuit package is a [[Bridge Rectifier]]
![[Pasted image 20230424094346.png]]
- To analyze use:
![[Pasted image 20230424094520.png]]
- $D_1$ and $D_3$ conduct during the positive half of the cycle
- $D_2$ and $D_4$ conduct during the negative half of the cycle
- Because of the structure of the bridge, the flow of current through the load is in the same direction (c to d)a
- The input and output waveforms:
![[Pasted image 20230424094739.png]]
- Although the half-wave and full-wave rectifiers aeffectively convert AC signals with zero DC to a signal with a non-zero average voltage the rectifiers output is still an oscillating waveform
- A [[Ripple Filter]] ([[Lowpass Filter]]) is used to smoothen the DC signal across the load
![[Pasted image 20230424095029.png]]
![[Pasted image 20230424095044.png]]
