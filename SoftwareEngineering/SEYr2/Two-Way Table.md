## Two Way Table
- A [[Two-Way Table]] describes two categorical variables, organizing counts according to a row variable and a column variable. Each combination of values for these two variables is called a cell

Young Adults by Gender and Chance of Getting Rich by Age 30
|                  | Female | Male | Total |
| ---------------- | ------ | ---- | ----- |
| Almost no Chance | 96     | 98   | 194   |
| Some chance      | 426    | 286  | 712   |
| A 50-50 Chance   | 696    | 720  | 1416  |
| A good Chance    | 663    | 758  | 1421  |
| Almost Certain   | 486    | 597  | 1083  |
| Total            | 2367   | 2459 | 4826      |

![[Marginal Distribution]]
![[Conditional Distribution]]
#### Consider:
- [[Simpson's Paradox]]

### Testing Hypotheses
We want to test the hypothesis ($H_0$) that there is no relationship between the two categorical values.

To test it we compare actual counts in the table vs the expected counts(the counts when $H_0$ is true(there is no relationship))
$$ expected\; count = \frac{row\; total\times column\; total}{n} $$
#### Chi-Square Statistic
This is the test statistic we use to make the comparison between expected and actual values
$$ \chi^2 = \sum\frac{(observed-expected)^2}{expected} $$
The sum is over all cells in the table
The larger the values of $\chi^2$ the better the evidence against $H_0$ 

#### Chi-Square Distribution
Only take positive values and are skewed to the right. A particular $\chi^2$ is specified by its degrees of freedom.

For a two way table with r rows and c columns the Chi-Square distribution has degrees of freedom = $(r-1)(c-1)$

The P-Value is the area under the density curve to the right of the value of the test statistic

#### When to use it
You can use the chi-square test when the average of the expected counts is 5 or more and all individual expected counts are 1 or greater.

In the special case of a 2x2 table all four expected counts should be 5 or more

#### Independent Random Samples
Suppose we have c independent random samples from c different populations.

We classify the individuals within each sample according to a categorical variable that takes on r values.

we now have an rxc table that has been obtained differently yet we can use the chi square test on

In this situation we test if: the distribution of the categorical variable is the same in each of the c populations

#### Procedure:
1. Calculate descriptive statistics
2. find the expected counts and use them to compute $\chi^2$
3. Compare $\chi^2$ to the chi square values from table F to find approximate P-Value
4. Draw a conclusion about the association between the row and column variables

This procedure can be applied for:
- Test for Independence: Take ==one== SRS and classsify indivduals according to 2 categorical variables
- Compare Several Populations: 
	- Select several SRSs from each population (the different populations are how they are divided)(these are the explanatory variables)
	- Classify each indivual according to a response variable

#### Chi-Square Test for Goodness of Fit


