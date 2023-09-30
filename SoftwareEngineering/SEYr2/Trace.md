Understanding the behaviour of a [[Finite State Machine]] M is essentially finding all the traces

A trace is a sequence of states and inputs (or a set of states and transitions) that creates an allowed path through the FSM's operating behaviour. A trace can start and stop at any arbitrary state. A trace that starts at state A with input x must proceed to state $B = \delta(A, x)$. i.e. the state given by the [[Transition Function]] for the given starting state and input.

In other words for a FSM with $n$ states if $Q = \{A_i\}_{0\leq i\leq n-1}$ and $m$ inputs $\sum = \{ x_j\}_{0\leq j\leq m-1}$ 

A trace through $M$ with $N$ steps is:
$$ (A_{i_0}, x_{j_0}, A_{i_1}, x_{j_1}, \cdots, A_{i_N}, x_{j_N}) $$
where $A_{i_q}$ is the appropriate next state based on the previous state and input combination:
$$ A_{i_q} = \delta(A_{i_{q-1}}), \quad for\quad 0\leq i_q \leq n-1 \quad and\quad0\leq j_q\leq m-1 $$
