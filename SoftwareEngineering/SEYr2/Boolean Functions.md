## Boolean Functions
- is an expression formed with:
	- binary variables
	- the binary operators OR, AND, and NOT
	- Parantheses
- $F_1(x,y,z) = x + y \;'\; z$
- For a given value of the variables, the function can either be 0 or 1
- Any boolean function can be represented in a [[Truth Table]]

#### Synthesis
- Implementation of schematic from the expression/truth table is called synthesis

#### Forms
- Boolean functions can be represented in different ways. Canonical and standard forms are two of them.
##### Canonical
- Sum of minterms (Canonical SOP)
- Product of maxterms (Canonical POS)

##### Standard
- Sum of Products (SOP): $f(x,y,z) = y+x'y+xy'z$
- Product of Sums (POS): $g(x,y,z) = x(x'+y+z)(y'+z')$

#### Cost
- The sum of 3 quantities
	- The number of inputs for each gate in the cicuit. The complement of a variable is interpreted as a seperate input. If an input is used for multiple gates the variable is counted that many times
	- Logic gates in the circuit. NOT gates used to complement an input do not count
	- .# of internal inputs. connections from a NOT gate used to complement an input are not considered here.

![[Minterms]]
