```ad-tldr
title: Definition: Combinational Circuit

a circuit whose output is a function of only the given outputs
```

```ad-tldr
title: Definition: [[Sequential Circuit]]
a circuit whose output depends on both the given inputs and the current state of the circuit
```

## Combinational Circuit
- consists of a set of input variables, an arrangement of [[Logic Gates]], and a set of output variables
- for $n$ input variables, there are $2^n$ binary input combinations. For each possible input combination, there is a corresponding set of $m$ outputs 
- a combinational circuit is basically a set of m boolean functions, each accepting n variables 
- Can also be specified with a [[Truth Table]] with n inputs and m outputs
- Is it Combinational?
	- If any block is labeled as a "memory element" the circuit is sequential not combinational
	- If there is any feedback in the circuit - the output from any gate is connected back to its input - the circuit is sequential
	- If neither of these the circuit is Combinational

### Analysis and Design
- for a given circuit diagram, we need to analyze that diagram to determine the set of [[boolean functions]] and/or the [[Truth Table]] that the circuit implements. It is also usefull to understand the practical function of the circuit
- For a desired funcitonality, set of [[Boolean Functions]], and/or [[Truth Table]], we also need to be able to design a combinational circuit that will implement that functionality
