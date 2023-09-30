A system that can be in a finite # of states, has finite inputs, produces a finite set of outputs.

An FSM is an abstract and generic concept. It can be implemented as a sequential circuit

### [[Deterministic FSM]]
![[Deterministic FSM]]

### [[Moore FSM]]
![[Moore FSM]]

### [[Mealy FSM]]
![[Mealy FSM]]

### [[Transducer]]
![[Transducer]]

### [[Acceptor]]
![[Acceptor]]


- The Set of all States is $Q$ 
	- The starting state is $s_0$ 
- For a [[Moore FSM]], the set of all acceptor states is $F$ : $F\subset Q$
- The set of all possible inputs is $\sum$ (a finite set)
	- if the FSM has $n$ binary inputs then $\sum$ has $2^n$ elements
	- The set of all possible input sequences is $\sum^*$ 
		- This is an infinite set because each input can be repeated an arbitrary number of times
		- The null sequence $\in$ (no input) is part of $\sum^*$
		- Subsets following paticular rules can be constructed. These are a Language $L$
- The [[Transition Function]] is $\delta$
	- This is the mapping of the particular inputs at each state cause a transition to other states
	- We write $\delta\; : \; Q\times\sum\to Q$
- The set of all possible outputs is $\Delta$ 
	- This is a Finite Set
	- If the FSM has m binary outputs the $\Delta$ has at most $2^m$ elements
- A [[Mealy FSM]] does not have acceptor states but it does have an output function:
	- $\omega\; : \; Q\times\sum\to \Delta$
	- This function identifies which transitions generate outputs

The System: $M = (Q, \sum, s_0, \delta, F)$ defines a [[Moore FSM]]

The System: $M = (Q,\sum,\Delta,s_0,\delta,\omega)$ defines a [[Mealy FSM]]

Consider a [[Moore FSM]] with three states A,B,and C and one binary input x.
The sytem starts in A. C produces one binary input y. Formally we have:
$Q=\{A,B,C\}$
$s_0 = A$
$F = \{C\}$
$\sum = \{0,1\}$
$\Delta = \{0,1\}$
$\sum^* = \{\in, 0, 1, 00, 01, 10, 11, 000, 001, 010, \cdots\}$

The [[Transition Function]] is probably best described by a state table where $Q(t+1) = \delta(Q(t), x)$
| Q(t) | x   | Q(t+1) |
| ---- | --- | ------ |
| A    | 0   | A      |
| A    | 1   | B      |
| B    | 0   | A      |
| B    | 1   | C      |
| C    | 0   | C      |
| C    | 1   | B       |

a valid trace of this FSM is (A,0,A,1,B,1,C,1,B) as this sequence of states and inputs obeys the transition function. The sequence (A,0,A,1,B,0,C,1,B) is not a trace because it doesnt obey the transfer function. From state B with input 0, $\delta(B,0) = A$ The language L of all input sequences that start from A and produce output in 4 or fewer steps is:
$$ L = \{11, 011, 0011, 1011\} $$
### [[Trace]]
![[Trace]]

### [[State Diagrams]]
![[State Diagrams]]

### Assigning States:
While a state diagram lists all the states in order to implement the circuit we need to map the states into binary numbers that can be strored on flip-flops. Two Common Approaches for N different states:
- Assign each state to as small a binary number as possible
- Assign each state to a one-hot binary number. This is a N-bit number where only one bit is set to 1

### [[State Table]]
![[State Table]]

### Simplifying the Diagram
- Simplify as much as possible, removing redundant states
- Choose the best assignment of states to binary numbers
- Simplify the required combinational logic as much as possible (kmaps)

##### State Reduction:
- Find all sets of equivalent states
- states are equivalent if all input sequences while in either states:
	- trigger a transition to the same state or an equivalent state, and 
	- generate exactly the same output

### Designing A Synchronous Sequential Circuit
- Choose the FSM model, Draw the [[State Diagrams]], Write the [[State Table]]
- Perform State Reduction
- Assign binary values to the states and write the binary coded state table
- Choose a type of flip flop. add the appropriate excitations to the binary coded state table
- Derive and Simplify the combinational logic for the flip flop inputs and the circuit outputs

### Analyzing Synchronous Sequential Circuits
1. Determine the expressions for the flip flop inputs in terms of the current state and input variables
2. Use those expressions and the appropriate flip-flop characteristic equation to determine the next state of each flip flop for every state/input combination
3. Determine the expressions for all outputs in terms of the current state and input variables.

Use this to determine the state table and from that the state diagram.

### Self Correcting Circuits
