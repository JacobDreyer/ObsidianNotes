## Boolean Algebra
- used to find simpler and cheaper [[Binary Logic]] Circuits
- Defined with:
	- A set of binary elements B={0,1} which has 2 discrete values:
		- 0: False, Open, Off, Low
		- 1: True, Close, On, High
	- A set of Binary Operators on B
		- AND ($\cdot$); OR(+); NOT($\bar x$)
	- A number of unproven axioms or [[Postulates]]
![[Pasted image 20220928102530.png]]


#### Basic Theorems
\` = $\bar x$
. = $\cdot$
- Theorem 1:
	- x + x = x
	- x . x = x
- Theorem 2:
	- x + 1 = 1
	- x . 0 = 0
- Thorem 3: 
	- (x')' = x
- Theorem 4 (Associative):
	- x + (y + z) = (x + y) + z
	- x . (y . z) = (x . y) . z
- Theorem 5 (DeMorgan):
	- (x + y)' = x'y'
	- (xy)' = x' + y'
- Theorem 6 (Absorption)
	- x + xy = x
	- x(x + y) = x


- Basic Theorems must be proved from the [[Postulates]] using Boolean algebra
- The validity of Theorems can be shown by means of [[Truth Table]]s

- Duality Principle: Every algebraic expression of boolean algebra remains valid if the operators and identity elements are interchanged

#### Operator Precedence
1. Parantheses
2. NOT
3. AND
4. OR

![[Boolean Functions]]


