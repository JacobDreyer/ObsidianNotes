### Part 1
Answer the following questions regarding flip flops. In all these questions, the flip flops are falling edge-triggered. The input changes just after the falling edge of the clock, and is sustained for an entire clock cycle. An example timing diagram is shown below

![[Pasted image 20221116191705.png]]
##### Question 1.1
A falling edge-triggered D flip flop is initialized on clock cycle t = 0 using an asynchronous set. How does the state of the D flip flop change after each clock cycle, if the following sequence of inputs is provided?
| Clock Cycle | 0   | 1   | 2   | 3   | 4   |
| ----------- | --- | --- | --- | --- | --- |
| D           | 0   | 1   | 0   | 1   | 0   |
| Q           | 1   | 0   | 1   | 0   | 1    |

##### Question 1.2
A falling edge-triggered T flip flop is initialized on clock cycle t = 0 using an asynchronous reset. How does the state of the T flip flop change after each clock cycle, if the following sequence of inputs is provided?

| Clock Cycle | 0   | 1   | 2   | 3   | 4   |
| ----------- | --- | --- | --- | --- | --- |
| T           | 0   | 1   | 0   | 1   | 0   |
| Q           | 0   | 0   | 1   | 1   | 0    |
| Q(t+1)      | 0   | 1   | 1   | 0   | 0    |

##### Question 1.3
A falling edge-triggered JK flip flop is initialized on clock cycle t = 0 using an asynchronous reset. How does the state of the JK flip flop change after each clock cycle, if the following sequence of inputs is provided?

| Clock Cycle | 0   | 1   | 2   | 3   | 4   |
| ----------- | --- | --- | --- | --- | --- |
| J           | 1   | 0   | 0   | 1   | 0   |
| K           | 1   | 0   | 0   | 1   | 0   |
| Q           | 0   | 1   | 1   | 1   | 0    |
| Q(t+1)      | 1   | 1   | 1   | 0   | 0    |

### Part 2
You have developed an exciting new flip flop: the FG flip flop. It has two inputs F and G, and the usual outputs Q(t) , Q'(t), where Q'(t) = $\bar{Q ( t )}$. Your FG flip flop has the following characteristic table:

| F   | G   | State      |
| --- | --- | ---------- |
| 0   | 0   | Complement |
| 0   | 1   | Reset      |
| 1   | 0   | Set        |
| 1   | 1   | Hold           |

What is the characteristic equation for this flip flop?

$$ Q(t+1) = \bar GQ'(t) + FQ(t) $$

| F   | G   | Q   | Q(t+1) |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | 1       |
| 0   | 0   | 1   | 0       |
| 0   | 1   | 0   | 0       |
| 0   | 1   | 1   | 0       |
| 1   | 0   | 0   | 1       |
| 1   | 0   | 1   | 1       |
| 1   | 1   | 0   | 0       |
| 1   | 1   | 1    | 1       |

![[Drawing 2022-11-16 20.11.18.excalidraw]]

### Part 3
##### Question 3.1
Consider the following circuit diagram
![[Pasted image 20221117130919.png]]
Assume the flip flop was reset to Q = 0 at the start. The following input waveforms are then applied to the circuit.

![[Pasted image 20221117130953.png]]
Which of the following output waveforms is correct?

![[Pasted image 20221117131024.png]]

| Falling Edge # | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| -------------- | --- | --- | --- | --- | --- | --- | --- |
| x              | 0   | 1   | 0   | 0   | 0   | 0   | 0   |
| Q              | 0   | 0   | 1   | 1   | 1   | 1   | 1    |
| Q(t+1)         | 0   | 1   | 1   | 1   | 1   | 1   | 1    |

$\therefore$ 3

##### Question 3.2
![[Pasted image 20221117131116.png]]
Assume the flip flop was reset to Q = 0 at the start. The following input waveforms are then applied to the circuit.

![[Pasted image 20221117131137.png]]
Which of the following output waveforms is correct?

![[Pasted image 20221117131156.png]]

| Falling Edge # | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| -------------- | --- | --- | --- | --- | --- | --- | --- |
| x              | 0   | 0   | 0   | 0   | 1   | 0   | 0   |
| Q              | 0   | 1   | 1   | 1   | 1   | 1   | 1    |
| NOR            | 1   | 0   | 0   | 0   | 0   | 0   | 0    |
| Q(t+1)         | 1   | 1   | 1   | 1   | 1   | 1   | 1    |

$\therefore$ 1