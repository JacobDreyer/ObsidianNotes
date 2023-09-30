##### Note Info
Date: 2022/04/14
Link to: [[Formulas]]
# Physics Formulas
- Refer to [[Units]] for units of properties
- Refer to [[Constant]] for a list of constants

##### Electric Charge and Force
==[[Coulomb's Law]]==
- The [[Electric Force]] exerted by an [[Electric Charge]]d particle $q_1$ on a second charge $q_2$
$$ F_{12} = \frac{kq_1q_2}{r^2}\hat{r} $$
$k$ = [[Coulomb's Constant]] = $8.988\cdot10^9 \frac{N\;m^2}{C^2}$
$\hat r$ = [[Unit Vector]] pointing from charge 1 to charge 2

==[[Electric Field]]==
- Suppose there is a [[Electric Force]] F acting on an [[Electric Charge]] $q_0$. 
- The electric field (of the other charge q causing the force) at the location of $q_0$ is:
$$ \vec{E} = \frac{\vec{F}}{q_0} =  k\frac{q}{r^2}\hat r $$
- Or electric field due to $q$ at distance r
$$ \vec E = -(\frac{\partial V}{\partial x},\frac{\partial V}{\partial y},\frac{\partial V}{\partial z}) $$

==[[Electric Dipole]]==
Dipole Torque in an Electric Field:
$$ \vec{\tau} = \vec{p}\times\vec{E} = pE\sin\varphi $$
- $\vec p$ = dipole moment
- $\varphi$ = angle between [[Electric Field]] and $\vec p$
- $\vec E$ = Electric Field

Dipole Moment:
$$ \vec p = qd $$
- $d$ = distance between the 2 charges
- $q$ = magnitude of [[electric charge]]s

On-Axis [[Electric Field]] of an Electric Dipole
$$ E = \frac{2kp}{x^3} $$
- $k$ = [[Coulomb's Constant]] = $8.988\cdot10^9 \frac{N\;m^2}{C^2}$
- $p$ = dipole moment
- $x$ = distance away from dipole (On-axis)

==[[Continuous Charge Distributions]]==
[[Electric Field]] at the end of a finite charged wire:
$$ \vec E = -k\frac{Q}{a(l+a)}\hat i $$
- $l$ = length of wire
- $a$ = distance from end of wire
- $Q$ = total [[electric charge]] of wire

[[Electric Field]] perpindicularly from an infite charged wire
$$ \vec E = \frac{2k\lambda}{r}\hat r $$
- points radially away from wire
- $\lambda$ = linear charge density
- $r$ = distance from wire (perpindicularly)

[[Electric Field]] from an infinite plane of [[electric charge]]
$$ \vec E = 2\pi k\sigma\hat y $$
- $\sigma$ = charge per unit area
- points perpindicularly away from plane

On-Axis [[Electric Field]] due to a ring of charge
$$ \vec E = \frac{kxQ}{(x^2+a^2)^{3/2}} \hat{x}$$
- $Q$ = total charge
- $a$ = radius of ring
- $x$ = distance from ring
- Points away along axis of ring

[[Electric Field]] between two plates([[Capacitor]])(Also electric field along a wire):
$$ E = \Delta V/l $$
- $l$ = distance between the 2 plates
- $\Delta V$ = [[Potential Difference]]

Electric Field of Cylinder [[Capacitor]]
$$ E = \frac{2k\lambda}{r} $$
- $\lambda$ = $Q/l$
	- $Q$ = total charge
	- $l$ = length of cylinder
- $r$ = ????

#### Electric Potential
==[[Work]]==

$$ W_{AB} = -(U_B-U_A) $$
- $W_{AB}$ = work to get from A to B
- $U_B$, $U_A$ = Potential energy at A and B

==The [[Electric Potential Energy]] of a system of two point charges==
$$ U = \frac{kqq_0}{r} $$
- $q$, $q_0$ = charge of the two point charges
- r = distance between them

==[[Electric Potential]]==
$$ V = \frac{U}{q_0} = \frac{kq}{r} $$
- $q_0$ = a test charge in [[Electric Field]] of $q$
- U = [[Electric Potential Energy]]

==[[Work]] from a Battery==
voltage of a battery can tell you how much [[Work]] the battery does on each coulomb of charge.
$$ W = q\Delta V $$
- $W$ = work
- $\Delta V$ = Potential Difference across battery

==[[Electric Potential]] of a Charged Disk==
$$ V_P = \frac{2Qk}{a^2}(\sqrt{x^2+a^2}-|x|) $$
- $a$ = radius of disk
- $Q$ = total charge
- $x$ = distance from disk

[[Electric Potential]] Due to Uniformly Charged Ring
$$ V = \frac{kQ}{\sqrt{x^2 + R^2}} $$
- $V$ = Electric Potential
- $Q$ = Charge of ring
- $x$ = distance from ring (on axis)
- $R$ = Radius of ring

==[[Potential Difference]]==
The difference in [[Electric Potential]] between two points
$$ \Delta V = -\int_A^B \vec{E}\cdot d\vec s$$


[[Potential Difference]] between two plates
$$ \Delta V = El = Ql/\epsilon_0A$$
- $l$ = distance between the plates
- $A$ = area of plate
- $\epsilon_0$ = [[Permittivity of Free Space]] = $8.854\cdot10^{-12}\; \frac{C^2}{N\;m^2}$
- $Q$ = Total Charge

Potenial Difference of Cylinder [[Capacitor]]
$$ \Delta V = \frac{2kQ}{l}\ln(b/a) $$
- $Q$ = total charge
- $l$ = length of cylinder
- $a$ = radius of inner cyclinder
- $b$ = radius to inner edge of outer cylinder

[[Potential Gradient]] using [[Spherical Coordinates]]
$$ \vec\nabla = (\frac{\partial}{\partial r}\hat r + \frac1r\frac{\partial}{\partial\theta}\hat\theta + \frac{1}{r\sin\theta}\frac{\partial}{\partial\varphi}\hat\varphi $$

==[[Capacitance]]==
Of two parrallel plates
$$ C = Q/V = A\epsilon_0/d $$
- $Q$ = total charge
- $V$ = [[Potential Difference]]
- $A$ = Area
- $\epsilon_0$ = [[Permittivity of Free Space]] = $8.854\cdot10^{-12}\; \frac{C^2}{N\;m^2}$
- $d$ = distance between plates

Of a cylinder [[Capacitor]]
$$ C = \frac l{2k\ln(b/a)} $$
- $l$ = length of cylinder
- $a$ = radius of inner cylinder
- $b$ = radius to inner edge of outer cylinder 

==the [[Work]] stored in the [[Capacitor]] as its [[Electric Potential Energy]]:==
$$ W = \frac12CV^2 $$
- $C$ = [[Capacitance]]
- $V$ = [[Potential Difference]]

Energy Density in a Capacitor
$$ u = U/\Omega = \frac12\epsilon_0E^2$$
- $u$ = Energy Density
- $U$ = [[Electric Potential Energy]]
- $\Omega$ = Volume
- $\epsilon_0$ = [[Permittivity of Free Space]] = $8.854\cdot10^{-12}\; \frac{C^2}{N\;m^2}$
- $E$ = [[Electric Field]]

==[[Dielectric]]==
Dielectric constant:
$$ E = \frac{E_0}{\kappa}\qquad V = \frac{V_0}{\kappa}\qquad C = \kappa C_0\qquad U = \frac{U_0}{\kappa} $$
- $E$, $E_0$ = New and original [[Electric Field]]
- $V$, $V_0$ = New and original [[Potential Difference]]
- $C$, $C_0$ = New and original [[Capacitance]]
- $U$, $U_0$ = new and original stored energy ([[Energy and Energy Density in Capacitors]])
- $\kappa$ = Dielectric constant

#### [[Circuit]]
[[Current]]
$$ I = \frac{\Delta Q}{\Delta t} $$
- $I$ = [[Current]]
- $\Delta Q$ = Change in charge (amount of charge past a point)
- $\Delta t$ = change in time (amount of time it takes)

[[Drift Velocity]]
$$ v_d = a\tau $$
- $v_d$ = drift velocity
- $a$ = acceleration
- $\tau$ = time between collisions

[[Current]] Current Density
$$ J = \frac{I}{A} = qnv_d = \frac{q^2n\tau}{m}E = \sigma E$$
- $q$ = charge on each carrier
- $v_d$ = [[Drift Velocity]]
- $n$ = number of charges per unit volume
- $\tau$ = time between collisions
- $m$ = mass
- $E$ = [[Electric Field]]
- $\sigma$ = conductivity
- $A$ = Cross-sectional Area

[[Current]]
$$ I = \sigma AE = qnv_dA $$
- $\sigma$ = conductivity
- $E$ = [[Electric Field]]
- $A$ = Cross-sectional Area
- $n$ = number of charges per unit volume
- $q$ = charge on each carrier
- $v_d$ = [[Drift Velocity]]
- $I$ = [[Current]]

==[[Resistivity]]==
$$ \rho = \frac1{\sigma} $$
- $\sigma$ = conductivity

conductivity:
$$ \sigma = \frac{q^2n\tau}{m} $$
- $q$ = charge on each carrier
- $n$ = number of charges per unit volume
- $\tau$ = time between collisions
- $m$ = mass
- $E$ = [[Electric Field]]

Resistance:
$$ R = \frac{\rho l}{A} $$
- $R$ = resistance
- $\rho$ = resistivity
- $l$ = length of wire
- $A$ = Cross-sectional area




##### Series [[Circuit]]
Voltage([[Potential Difference]]) of a Series Circuit
$$ \Delta V = \Delta V_1 + \Delta V_2 $$

[[Capacitance]] of a Series Circuit
$$ \frac1{C_{eq}} = (\frac1{C_1} + \frac1{C_2}) $$

[[Current]] in a Series Circuit
$$ I = I_1 = I_2 $$

Voltage across a Resistor in Series:
$$ V_1 = \frac{\epsilon R_1}{R_1+R_2} $$

[[Resistance]] in a Series Circuit
$$ R_{eq} = R_1 + R_2 $$

##### Parallel [[Circuit]]
Voltage([[Potential Difference]]) of a Parallel Circuit
$$ \Delta V_1 = \Delta V_2 = \Delta V $$

[[Capacitance]] of a Parallel Circuit
$$ C_{eq} = C_1+C_2 $$

[[Current]] in a Parallel Circuit
$$ I = I_1 + I_2 $$

[[Resistors]] in Parallel
$$ R_{eq} = (\frac1{R_1}+\frac1{R_2})^{-1} $$

[[Current]] through [[Resistors]] in Parallel
$$ I_1 = I\frac{R_2}{R_1+R_2} $$
- $I$ = Current through battery


###### [[Resistor Capacitor Circuits]]
[[Current]] at time t:
$$ I(t) = I(0)e^{-t/RC} $$
- $I(0)$ = Original Current
- $t$ = time
- $R$ = [[Resistance]] of [[Circuit]]
- C = [[Capacitance]] of [[Capacitor]]


[[Voltage]] across [[Capacitor]] as it charges
$$ V_C = \epsilon(1-e^{-t/RC}) $$
- $\epsilon$ = [[Electromotive Force]] (emf)
- $t$ = time
- $R$ = [[Resistance]]
- $C$ = [[Capacitance]]

[[Voltage]] across [[Capacitor]] when Discharging a RC circuit
$$ V_C = V_0e^{-t/RC} $$
- $V_0$ = starting voltage
- $t$ = time
- $R$ = [[Resistance]]
- $C$ = [[Capacitance]]


###### [[Ohm's Law]]
$$ \Delta V = IR $$
- $I$ = [[Current]]
- $R$ = [[Resistance]]
- $\Delta V$ = Voltage([[Potential Difference]])

###### [[Electrical Power]]
$$ P = I\Delta V $$
- $I$ = [[Current]]
- $\Delta V$ = [[Potential Difference]](voltage)


#### Magnetism
###### [[Magnetic Force]]
$$ \vec F = q\vec v\times\vec B = qvB\sin\theta $$
- $q$ = [[Electric Charge]]
- $\vec v$ = velocity
- $\vec B$ = [[Magnetic Field]]
- $\theta$ = angle between $\vec B$ and $\vec v$

Radius of Circular motion due to [[Magnetic Force]]
$$ r = \frac{mv}{|q|B} $$
- $m$ = mass
- $v$ = velocity of charge
- $q$ = charge of charge
- $B$ = magnetic field magnitude

Period to complete one circular orbit
$$ T = \frac{2\pi r}{v} = \frac{2\pi m}{|q|B} $$
- $r$ = radius of circular motion
- $m$ = mass
- $v$ = speed of charge
- $q$ = charge of charge
- $B$ = Magnetic field magnitude

[[Frequency]]:
$$ f = \frac1T $$
- $T$ = Period

[[Magnetic Force]] on an [[Current]] Carrying [[Conductor]]
$$ F = I\vec L\times\vec B = ILB\sin(\theta) $$
- $I$ = [[Current]]
- $L$ = Length of [[Conductor]]
- $B$ = [[Magnetic Field]]
- $\theta$ = angle between $B$ and $L$

[[Magnetic Torque on Current Loop]] (sqaure):
$$ \tau = BIla\sin\theta = \vec\mu\times\vec B$$
- $\tau$ = torque on loop
- $B$ = [[Magnetic Field]]
- $I$ = [[Current]]
- $l$, $a$ = height and width of loop
- $\theta$ = angle between vector pointing out of loop and magnetic field
- $\vec\mu$ = Magnetic Dipole Moment ([[Magnetic Moment]])

Magnetic Dipole Moment ([[Magnetic Moment]])
$$ \vec\mu = IN\vec A $$
- $I$ = Current through loop
- $N$ = Number of loops
- $\vec A$ = Magnitude of Area in direction out of loop
- $\vec\mu$ = Magnetic Dipole Moment. Same direction as $\vec A$ 

[[Hall Effect]]
$$ V_H = Eh = v_dBh = \frac{IB}{nqt} $$
- $V_H$ = [[voltage]] across width of conductor
- $h$ = width of conductor
- $E$ = [[Electric field]]
- $v_d$ = drift velocity
- $B$ = [[Magnetic Field]]
- $n$ = density of charge carriers
- $t$ = thickness of conductor in direction of $B$
- $q$ = charge

[[Magnetic Force]] Between Two [[Current]] Carrying Wires
$$ \frac FL = \frac{\mu_0I_1I_2}{2\pi d} $$
- $F$ = [[Magnetic Force]] (acts on each wire)
- $\mu_o$ = [[Permeability Constant]] = $4\pi\cdot10^{-7}$ ($T\; m/A$) or ($N/A^2$)
- $I_1$, $I_2$ = [[Current]] of wires
- $d$ = distance between wires
- $L$ = Length of wires
- $I_1$ and $I_2$ same direction -> Force is attractive
- $I_1$ and $I_2$ opposite direction -> Force is repulsive

###### [[Magnetic Field]]
Of Current Carying Wires:
![[Pasted image 20220416211849.png]]
[[Magnetic Field]] of a [[Current]] Carrying Wire
$$ B = \frac{\mu_0I}{2\pi y} $$
- $B$ = [[Magnetic Field]]
- $\mu_0$ = [[Permeability Constant]] = $4\pi\cdot10^{-7}$ ($T\; m/A$) or ($N/A^2$)
- $I$ = [[Current]]
- $y$ = distance from wire

[[Magnetic Field]] on axis of [[Current]] Loop
$$ B = \frac{\mu_0Ia^2}{2(x^2+a^2)^{3/2}} $$
- $\mu_0$ = [[Permeability Constant]] = $4\pi\cdot10^{-7}$ ($T\; m/A$) or ($N/A^2$)
- $I$ = [[Current]]
- $a$ = radius of loop
- $x$ = distance from loop (On-axis)

If super far away from loop so x>>a or Magnetic Dipole:
$$ B = \frac{\mu_0\mu}{2\pi x^3}  $$
- $\mu_0$ = [[Permeability Constant]] = $4\pi\cdot10^{-7}$ ($T\; m/A$) or ($N/A^2$)
- $\mu$ = [[Magnetic Moment]]
- $x$ = distance from loop
- $B$ = [[Magnetic Field]]

[[Magnetic Field]] of Loops And Magnetic Field of [[Solenoids]]
$$ B = \frac{\mu_0NI}{2R} = \mu_0nI $$
- $n$ = # of loops per unit length
- $N$ = Number of Loops
- $I$ = [[Current]]
- $\mu_0$ = [[Permeability Constant]] = $4\pi\cdot10^{-7}$ ($T\; m/A$) or ($N/A^2$)

###### [[Magnetic Induction]]
[[Magnetic Flux]]:
$$ \Phi_B = \vec{B}\cdot\vec{A} = BA\cos\theta = \int\vec{B}\cdot d\vec A $$
- $B$ = [[Magnetic Field]]
- $A$ = Area of plane surface
- $\Phi_B$ = Magnetic Flux
- $\theta$ = angle between vector perpindicular to surface and Magnetic Field

[[Faraday's Law]]
$$ \epsilon = -\frac{\Delta\Phi_B}{\Delta t} $$
- $\epsilon$ = [[Electromotive Force]](EMF)
- $\Phi_B$ = [[Magnetic Flux]]
- $t$ = time

Slider Moving in a [[Magnetic Field]] ([[Motional EMF]])
$$ \epsilon = -BvL $$
- $\epsilon$ = [[Electromotive Force]]
- $B$ = [[Magnetic Field]]
- $v$ = speed slider is travelling at
- $L$ = Length of slider

$$ E = vB $$
- $E$ = [[Electric Field]]
- $B$ = [[Magnetic Field]]
- $v$ = speed slider is travelling at

$$ V_{ab} = BvL $$
- $B$ = [[Magnetic Field]]
- $v$ = speed slider is travelling at
- $L$ = Length of slider
- $V_{ab}$ = [[Potential difference]] between ends of slider

#### [[Oscillations]] and Waves
Angular Frequency
$$ \omega = \frac{2\pi}T $$
- $T$ = Period
- $\omega$ = [[Angular Frequency]]

###### [[Oscillations]]
$$ x(t) = A\cos(\omega t + \varphi) $$
$$ v(t) = -A\omega\sin(\omega t + \varphi) $$
$$ a(t) = -A\omega^2\sin(\omega t + \varphi) $$
$$ a = -\omega^2x $$
- $x$ = position of object
- $A$ = [[Amplitude]]
- $\varphi$ = phase constant (shift)
- $\omega$ = [[Angular Frequency]]
- $a$ = [[Acceleration]]
- $v$ = Velocity

###### [[Mass-Spring System]]
[[Angular Frequency]] of a mass spring system:
$$ \omega = \sqrt{\frac km} $$
- $\omega$ = [[Angular Frequency]]
- $k$ = Spring Constant
- $m$ = mass on spring

###### [[Simple Pendulum]]
Tangential Force on a simple Pendulum
$$ F_t = -mg\sin\theta $$
- $m$ = mass
- $g$ = acceleration due to gravity = 9.81
- $\theta$ = angle between string direction and gravity direction(straight up and down)
- $F_t$ = tangential force (force causing swinging)

Arc Length from [[Equilibrium]] point to Bob Position
$$ s = l\theta $$
- $s$ = Arc Length
- $l$ = length of string
- $\theta$ = angle between string and string at equilibrium

Tangential Acceleration
$$ a = \frac{d^2s}{dt^2} = l\frac{d^2\theta}{dt^2} $$
- $s$ = Arc Length
- $\theta$ = angle between string and string at equilibrium
- $a$ = tangential accleration

Acceleration of Angle
$$ \frac{d^2\theta}{dt^2} = -\frac gl\sin\theta $$
- $g$ = acceleration due to gravity = 9.81
- $l$ = length of string
- $\theta$ = angle between string and string at equilibrium

[[Simple Pendulum]] Equation
$$ \theta(t) = A\cos(\omega t + \varphi) $$
- $\theta$ = angle between string and string at equilibrium
- $A$ = [[Amplitude]]
- $\varphi$ = phase constant (shift)
- $\omega$ = [[Angular Frequency]]

[[Angular Frequency]] of a [[Simple Pendulum]]
$$ \omega = \sqrt\frac gl $$
- $g$ = acceleration due to gravity = 9.81
- $l$ = length of string

###### [[Physical Pendulum]]
[[Torque]] of a Physical Pendulum
$$ \tau = -lmg\sin\theta = I\frac{d^2\theta}{dt^2} $$
- $\tau$ = torque
- $l$ = distance from pivot point to [[Centre of Gravity]]
- $m$ = mass
- $g$ = acceleration due to gravity = 9.81
- $\theta$ = angle from vertical
- $I$ = [[Moment of Inertia]]
- $\frac{d^2\theta}{dt^2}$ = [[Angular Acceleration]] ($\alpha$)

[[Angular Acceleration]]
$$ \frac{d^2\theta}{dt^2} = \frac{mgl}{I}\theta $$
- $l$ = distance from pivot point to [[Centre of Gravity]]
- $m$ = mass
- $g$ = acceleration due to gravity = 9.81
- $\theta$ = angle from vertical
- $I$ = [[Moment of Inertia]]
- $\frac{d^2\theta}{dt^2}$ = [[Angular Acceleration]] ($\alpha$)

Formula for Physical Pendulum and SHM
$$ \theta(t) = A\cos(\omega t + \varphi) $$
$$ \omega^2 = \frac{mgl}{I} $$
- $l$ = distance from pivot point to [[Centre of Gravity]]
- $m$ = mass
- $g$ = acceleration due to gravity = 9.81
- $\theta$ = angle from vertical
- $I$ = [[Moment of Inertia]]
- $\omega$ = [[Angular Frequency]]
- $A$ = Amplitude
- $\varphi$ = phase shift

###### [[Circular Motion]]
Location in a single plane (looking from side)
$$ x = R\cos(\omega t) $$
$$ y = R\cos(\omega t - \frac\pi2) $$
- $x$, $y$ = location
- $R$ = Radius of motion
- $\omega$ = [[Angular Frequency]]

##### [[Energy in SHM]]
[[Kinetic Energy]]
$$ K = \frac12mv^2 $$
- $m$ = mass
- $v$ = velocity
- $K$ = Kinetic Energy

[[Elastic Potential Energy]]
$$ U = \frac12kx^2 $$
- $U$ = Elastic Potential Energy
- $k$ = Spring constant
- $x$ = displacement from [[Equilibrium]]

Total [[Energy]]
$$ E = \frac12kA^2 $$
- $k$ = spring constant
- $A$ = Amplitude
- $E$ = total energy of system

###### [[Properties of Waves]]
Wave travelling along a string
$$ y(x,t) = A\cos(kx-\omega t) = A\cos(k(x-vt)) $$
- $A$ = amplitude
- $\omega$ = angular frequency = $2\pi/T$
- k = wavenumber = $2\pi/\lambda$
- $\lambda$ = wavelength = $2\pi/k$
- $v$ = wave speed

Wave Speed:
$$ v = \frac{\lambda}{T} = f\lambda = \frac{\omega}{k} $$
- $v$ = speed
- $T$ = period
- $f$ = [[Frequency]]
- $\lambda$ = wavelength
- $\omega$ = [[Angular Frequency]]
- $k$ = [[Wave Number]]

[[Wave Number]]
$$ k = 2\pi/\lambda $$
- $\lambda$ = [[Wavelength]]

[[Wave Equation]]
$$ \frac{d^2z}{dt^2} = \frac{T\;d^2z}{\mu \; dx^2}= v^2\frac{d^2z}{dx^2}  $$
- $v$ = velocity of propogation of the wave
- $T$ = tension in the string
- $\mu$ = mass per unit length of string

Velocity of wave
$$ v = \sqrt{\frac T\mu} $$
- $v$ = velocity of propogation of the wave
- $T$ = tension in the string
- $\mu$ = mass per unit length of string

[[Standing wave]] Equation:
$$ z(x,t) = A\cos(\omega t)\sin(\frac{n\pi x}{L}) $$
- $L$ = length of string
- $n$ = # of nodes - 1 (including ends)
- $\lambda$ = wave length = $2\pi/k$ = $2L/n$
- $\omega$ = [[Angular Frequency]]
- $x$ = location along string

a node is where the displacement is always 0

Frequency of [[Standing wave]]:
$$ f = \frac{k}{2\pi}\sqrt{\frac{T}{\mu}} = \frac{1}{\lambda}\sqrt{\frac{T}{\mu}} = \frac{n}{2L}\sqrt{\frac{T}{\mu}} $$
- $L$ = length of string
- $n$ = # of nodes - 1 (including ends)
- $\lambda$ = wave length = $2\pi/k$ = $2L/n$
- $T$ = tension in string
- $\mu$ = mass per unit length of string

###### Wave [[Power]]
$$ P = \mu v\omega^2 A^2sin^2(kx-\omega t) $$
$$ \bar{P} = \frac{\mu v\omega^2 A^2}2 $$
- $v$ = transverse velocity of string(not propogation speed)
- $A$ = Amplitude of wave
- $\omega$ = [[Angular Frequency]]
- $\mu$ = mass per unit length
- $k$ = [[Wave Number]]
- $P$ = Wave Power
- $\bar{P}$ = Average Wave Power
- $x$ = distance along string
- $t$ = time

###### [[Wave Intensity]]
$$ I = \frac PA $$
- $I$ = Wave Intensity
- $P$ = [[Wave Power]]
- $A$ = Area

[[Sound]] Wave Intensity
$$ I = \frac P{4\pi r^2} $$
- $I$ = Wave Intensity
- $P$ = [[Wave Power]]
- $r$ = distance from origin of sound