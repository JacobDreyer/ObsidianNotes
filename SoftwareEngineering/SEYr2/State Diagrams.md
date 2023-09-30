An abstract FSM is often represented with a state diagram. This is a graphical schematic of the FSM operation, providing a complete description of the FSM behaviour. It consists of 2 graphical elements:
- Circles represent the states of the FSM
- Lines (or arcs) with arrows represent the possible transisitions between states of the FSM

(its basically a flow chart)

#### Labels
Each of the states are identified by a label typically either by some representative or abstract name, or by the actual state of the flip flops. 

The transitions are also identified by a label, typically the input value that triggers the transition.

A [[Moore FSM]] also includes the output written on each state, while a [[Mealy FSM]] includes the output on each transition.

Note: States can not be defined by their output. Outputs can be the same as the state but this is not always the case

Often a state diagram has one transition with a final state, but no initial state. This is usually the “start” or “reset” transition, which identifies the starting state of the system. Alternatively, this transition arrow can be omitted if one of the states is clearly identified as the initial state