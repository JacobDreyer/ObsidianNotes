## Minterms
- A minterm is an AND combination of all variables or thier complements
- Also known as a [[Standard Product]]
- There are $2^n$ maxterms. n = number of variables
| x   | y   | z   | Minterm                        | Name  |
| --- | --- | --- | ------------------------------ | ----- |
| 0   | 0   | 0   | $\bar x\cdot\bar y\cdot\bar z$ | $m_0$ |
| 0   | 0   | 1   | $\bar{x}\cdot\bar{y}\cdot z$   | $m_1$ |
| 0   | 1   | 0   | $\bar{x}\cdot y\cdot\bar{z}$   | $m_2$ |
| 0   | 1   | 1   | $\bar{x}\cdot y\cdot z$        | $m_3$ |
| 1   | 0   | 0   | $x\cdot\bar{y}\cdot\bar{z}$    | $m_4$   |
| 1   | 0   | 1   | $x\cdot\bar{y}\cdot z$         | $m_5$   |
| 1   | 1   | 0   | $x\cdot y\cdot\bar{z}$         | $m_6$   |
| 1   | 1   | 1   | $x\cdot y\cdot z$              | $m_7$      |
What function as a minterm returns true with the corresponding value
