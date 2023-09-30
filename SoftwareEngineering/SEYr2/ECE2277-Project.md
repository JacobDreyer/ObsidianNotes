[[ECE2277-Project-ScratchWork]]
[[ECE2277ProjectReport.pdf]]
## Summary
A summary of the deliverables for this lab are enumerated below. 
1. Design a sequential circuit to loop through outputting a given sequence of digits. 
2. Describe this design process in the written report. 
3. Implement this sequential circuit in Quartus. 
4. Use the simulation tools in Quartus to verify that the circuit produces the correct output. 
5. Program your circuit to the FPGA so that your sequence of numbers is shown on one of the seven segment displays. 
6. Submit written report via OWL. A template for the project report is provided.

#### My Sequence
5, 4, 3, 1, 1, 2, 7

### Deriving a Circuit
| #   | $Q_3(t)$ | $Q_2(t)$ | $Q_1(t)$ | $Q_0(t)$ | Next | $Q_3(t+1)$ | $Q_2(t+1)$ | $Q_1(t+1)$ | $Q_0(t+1)$ |
| --- | -------- | -------- | -------- | -------- | ---- | ---------- | ---------- | ---------- | ---------- |
| 1   | 0        | 0        | 0        | 1        | 1(9) | 1          | 0          | 0          | 1          |
| 2   | 0        | 0        | 1        | 0        | 7    | 0          | 1          | 1          | 1          |
| 3   | 0        | 0        | 1        | 1        | 1    | 0          | 0          | 0          | 1          |
| 4   | 0        | 1        | 0        | 0        | 3    | 0          | 0          | 1          | 1          |
| 5   | 0        | 1        | 0        | 1        | 4    | 0          | 1          | 0          | 0          |
| 7   | 0        | 1        | 1        | 1        | 5    | 0          | 1          | 0          | 1          |
| 9   | 1        | 0        | 0        | 1        | 2    | 0          | 0          | 1          | 0           |

![[Drawing 2022-11-21 10.12.23.excalidraw]]
$$ Q_0(t+1) = (\bar Q_2 + Q_1 + \bar Q_0)(\bar {Q_3}) $$
$$ Q_1(t+1) = Q_3 + \bar Q_0 $$
$$ Q_2(t+1) = Q_2Q_0 + Q_1\bar Q_0 $$
$$ Q_3(t+1) = \bar Q_3\bar Q_2\bar Q_1Q_0 $$
