## Maxterms
- is an OR combination of all input variables or their complements
- Also known as a [[Standard Sum]]
- There are $2^n$ maxterms n = # of variables
| x   | y   | z   | Maxterm                        |
| --- | --- | --- | ------------------------------ |
| 0   | 0   | 0   | $x+ y+ z$ |
| 0   | 0   | 1   | ${x}+{y}+\bar z$   |
| 0   | 1   | 0   | ${x}+\bar y+ {z}$   |
| 0   | 1   | 1   | ${x}+\bar y+\bar z$        |
| 1   | 0   | 0   | $\bar x+ {y}+{z}$    |
| 1   | 0   | 1   | $\bar x+{y}+\bar z$         |
| 1   | 1   | 0   | $\bar x+\bar y+{z}$         |
| 1   | 1   | 1   | $\bar x+\bar y+\bar z$              |
What function as a maxterm returns false with the corresponding value