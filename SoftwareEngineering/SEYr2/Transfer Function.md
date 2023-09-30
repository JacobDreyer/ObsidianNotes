- The transfer function $H(\omega)$, also called the [[Network Function]], is a very useful tool for finding the [[Frequency Response]] of a circuit
- The frequency response of a circuit is the plot of the circuit's transfer function $H(\omega)$ versus $\omega$ varying from $\omega = 0$ to $\omega = \infty$
- The transfer function $H(\omega)$ of a circuit is the frequency-dependent ratio of a [[Phasor]] output $Y(\omega)$ (an element voltage of current) to a phasor input $X(\omega)$ (source voltage or current)
$$ H(\omega) = \frac{Y(\omega)}{X(\omega)} $$
- Assuming zero-initial conditions
- Since the input and output can be either voltage or current, there are 4 possible transfer functions
$$ H(\omega) = \frac{V_0(\omega)}{V_i(\omega)} = Voltage\;Gain $$
$$ H(\omega) = \frac{I_o(\omega)}{I_i(\omega)} = Current \; Gain $$
$$ H(\omega) = \frac{V_o(\omega)}{I_i(\omega)} = Transfer \; Impedance $$
$$ H(\omega) = \frac{I_o(\omega)}{V_i(\omega)} = Transfer Admittance $$
- Where subscripts $o$ and $i$ denote output and input values
- To obtain transfer function, first obtain the frequency-domain equivalent of the circuit by replacing resistors, inductors, and capacitors by their impedances $R$, $j\omega L$, and $\frac1{j\omega C}$. Then using any circuit techniques obtain appropriate quantities to determine $H(\omega)$
- Determine the [[Frequency Response]] of a circuit by plotting the magnitude and phase of the transfer function of frequency
- The transfer function $H(\omega)$ can be expressed in terms of it's numerator polynomial $N(\omega)$ and denominator polynomial $D(\omega)$ as:
$$ H(\omega) = \frac{N(\omega)}{D(\omega)} $$
- $H(\omega)$ assumes that common numerator and denominator factors have canceled, reducing the ratio to lowest terms.
	- The roots of $N(\omega) = 0$ are called the ZEROS of $H(\omega)$
	- Similarily, the roots of $D(\omega) = 0$ are called the POLES of $H(\omega)$
- To avoid complex algebra, replace $j\omega$ temporarily with $s$, when working with $H(\omega)$ and replace $s$ with $j\omega$ at the end
$$ H(s) = \frac{N(s)}{D(s)} $$
- a ZERO is the value of $s = j\omega$ that makes $H(s)$ zero and POLE is the value of $s = j\omega$ that makes $H(s)$ infinite
- Also, a ZERO is a root of the numerator polynomial $N(s)$ that results in a zero value of the transfer function
- And a POLE is the root of the denominator polynomial $D(s)$ that results in a value of transfer function as infinite
- For example if:
$$ H(s) = \frac{(s+2)(s+5)}{(s+3)(s+10)} $$
- Then $z = -2$ and $z = -5$ are ZEROs
- and $p = -3$ and $p = -10$ are POLEs
