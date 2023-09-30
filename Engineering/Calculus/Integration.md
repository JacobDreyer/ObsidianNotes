##### Note Info
Course: [[Engineering]]
Class: [[Calculus]]
Unit: Integration
Date: 2022/04/05

## Integration
- can be used by creating infinitly small slices of an object and summing them up to find the area of an object
- Defined as the limit of a sum of slices where the number of slices go to infinity
- The integral of an equation is found by taking the [[anti-derivatives]] of the equation. Then sub in the top number on the integral. Then subtract the equation with the lower number subbed in

##### [[Integration by Parts]]
- Used when the integral is too complicated to calculate
- Ex. $xe^x$
- Formula:
$$ \int u\cdot dv = u\cdot v - \int v\cdot du $$
##### [[Integrals of Rational Functions]]
$$ f(x) = \frac{P(x)}{Q(x)} $$
and degree of P(x) < degree of Q(x)
if it isnt then do long division so that it is

Steps:
- Given equation, factor denominator
- Seperate sections of denominator and have a constant on top of each one (so that each new segment is being added)
- make a common denomiator
- figure out what each of the constants must be equal to
- go back to when everything was seperated, sub in the constants, do integral

##### [[Inverse Substitutions]]
- Used for integrals that look like/have: $a^2 + x^2$
- consider a triangle. Determine where it makes most sense for each element to be located ($a^2$,  $x^2$ , ($a^2-x^2$))
- create expression using sin, tan that x is equal to
- sub in for ALL xs and solve and input dx
- Everything should be in terms of $\theta$ 
- simplify using [[Trig Identities]]
- do [[Integration]]
- Replace all instances of $\theta$ to be in terms of x

##### [[Improper Integrals]]
Type 1:
- one or both limits of [[Integration]] are infinity
- Integrate function, see if it is convergent (limit of answer goes to number)
$$ \int_a^\infty f(x)dx = \lim_{R\to\infty}\int_a^R f(x)dx $$
Type 2:
- f(x) is divergent as x approaches integration limits
- Same process as type 1 improper integral

