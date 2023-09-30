Most practical memory storage element

Using flip flops with a clock signal helps to synchronize memory storage with the output of other parts of the circuit.

However what if the data input to the flip flop is used elsewhere?

- A rising [[Signal Edge]]-triggered D flip flop will only store input D at the instant of the clock's rising edge
- But the clock will keep ticking capturing input D each time, and we may want to store data for more than one clock cycle

### Asynchronous Inputs
Many flip flops are created with an additional asyncrnous input. these override the clock signal to force a paticular behaviour.

The three common inputs are Enable, Set and Reset
- Set forces Q = 1
- Reset Forces Q = 0
- Enable enables the flip flop

If a flip flop has a set and a reset one will have priority

### Circuit Symbols
![[Pasted image 20221109145342.png]]
1: input 2 = falling edge clock
3: bottom = active low (need rst = 1 for normal operation)

### Types of Flips Flops
##### D Flip Flop
- Stores the input ???
![[Pasted image 20221109152917.png]]

##### JK Flip Flop
$$ D = JQ' + \bar KQ $$
[[Characteristic Equation]]:
$$ Q(t+1) = JQ' + \bar KQ $$
[[Truth Table]] and Diagram
| J   | K   | JQ' | K'Q | Q(t+1) |
| --- | --- | --- | --- | ------ |
| 0   | 0   | 0   | Q   | Q(t)   |
| 0   | 1   | 0   | 0   | 0      |
| 1   | 0   | Q'  | Q   | 1      |
| 1   | 1   | Q'  | 0   | Q'(t)       |
![[Drawing 2022-11-09 15.04.04.excalidraw]]

Functionality:

##### T Flip Flop
- "Toggle Flip Flop"
- Can be built from a [[D Flip Flop]] or a [[JK Flip Flop]]
- Has a hold state and a Complement State

[[Characteristic Equation]]:
$$ Q(t+1) = TQ' + \bar TQ $$
| T   | TQ' | $\bar T$Q | Q(t+1) |
| --- | --- | --------- | ------ |
| 0   | 0   | Q         | Q(t)   |
| 1   | Q'  | 0         | Q'(t)       |
![[Pasted image 20221109151743.png]]
