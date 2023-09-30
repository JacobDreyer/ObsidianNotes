##### Question 1
As you increase the margin of error in a confidence interval,
- [x] The Confidence interval increases
- [ ] the confidence interval decreases
- [ ] The confidence interval remains the same

##### Question 2
The time needed for college students to complete a certain paper-andpencil maze follows a Normal distribution with a mean of 30 seconds and a standard deviation of 3 seconds. You wish to see whether the mean time $\mu$ is changed by vigorous exercise, so you have a group of nine college students exercise vigorously for 30 minutes and then complete the maze. Assume that $\sigma$ remains unchanged at 3 seconds. The hypotheses you decide to test are $H_0:\mu = 30$ versus $H_a:\mu\neq 30$ Suppose it takes the nine students an average of $\bar x$ = 32.05 seconds to complete the maze. At the 1% significance level, what can you conclude?
- [ ] $H_0$ should be rejected because the P-value is less than 0.01
- [x] $H_0$ should not be rejected because the P-value is greater than 0.01.
- [ ] $H_0$ should be rejected because the P-value is less than 0.01.
- [ ] $H_0$ should not be rejected because the P-value is greater than 0.01.

First we want to calculate P-Value
![[Drawing 2022-11-08 20.33.49.excalidraw]]
P-Value = 2 x area of right shaded area = 2 x P($\bar x$ > 32.05 )

P($\bar x$ > 32.05 ) = probability that $\bar x$ is greater than 32.05

We now have to standardize both these values. recall [[Standardized Value]] $z = \frac{x-\mu}{\sigma}$

$\mu$ is given as 30. and standard deviation of $\bar x = \sigma/\sqrt n$ 
$$ \mu = 30 \qquad \sigma = \frac{\sigma_2}{\sqrt n} = \frac3{\sqrt9} = 1 $$
$$ Pvalue = 2\times P(z > (32.05-30)/1) = 2\times P(z > 2.05) $$
$$ = 2\times P(z < -2.05) = 2\times .0202 = .0404 $$
Used Table of Standard Normal Probabilities

Significance Level $\alpha$ is given as .01
.0404 is greater than .01 so we should retain the null hypothesis

##### Question 3
Is the mean height for all adult American males between the ages of 18 and 21 now over 6 feet? Let $\mu$ represent the population mean height of all adult American males between the ages of 18 and 21. What are the appropriate null and alternative hypotheses?
- [ ] $H_0:\mu = 6$ vs $H_a:\mu < 6$
- [ ] $H_0:\mu = 6$ vs $H_a:\mu \neq 6$
- [x] $H_0:\mu = 6$ vs $H_a:\mu > 6$

because it is asking if the mean is over 6ft

##### Question 4
It is known that driving can be difficult in regions where winter conditions involve snow-covered roads. For cars equipped with all-season tires traveling at 90 kilometers per hour, the mean stopping time in fresh snow is known to be 215 meters, with a standard deviation of $\sigma = 2.5$ meters. It is often claimed that automobiles in such areas should be equipped with special tires to compensate for such conditions, especially with respect to stopping distance. A manufacturer of tires made for driving in fresh snow claims that vehicles equipped with its tires have a decreased stopping distance. A study was done using a random sample of nine snow tires from the manufacturer on a snow-covered test track. The tests resulted in a mean stopping distance of $\bar x$ = 212.9 meters. Using the sample results, and assuming that stopping distance is a Normally distributed random variable, what is the value of the test statistic?
- [ ] 0.05
- [x] -2.52
- [ ] -9.36
- [ ] -1.04
- [ ] -1.96

Given:
$\mu = 215$
$\bar x = 212.9$
$\sigma = 2.5$
$n = 9$

Test Statistic:
$$ z = \frac{\bar x - \mu}{\frac{\sigma}{\sqrt n}} = \frac{212.9-215}{\frac{2.5}{\sqrt{9}}} = -2.52 $$
##### Question 5
Assume the red areas in the figures represent the P-values calculated from a data set. Which figure has the larger P-value?
![[Pasted image 20221108210956.png]]
- [ ] Figure 1
![[Pasted image 20221108211024.png]]
- [x] Figure 2
- [ ] Both have approximately the same P-Value

Figure B has Larger Area therefore larger probability therefore larger P-Value

##### Question 6
Confidence intervals are resistant to outliers in the data set.
- [ ] True
- [x] False

##### Question 7
A study was conducted on the reaction time of female subjects over the age of 50 to a particular light stimulus using a specific type of red light. A random sample of 45 female subjects from this age group in the population was selected, and the subjects’ reaction times (in seconds) were determined. Based on the test data, the 99% confidence interval estimate for $\mu$ was determined to be (0.66, 0.78). From this interval we can conclude that
- [ ] this interval contains the sample mean with probability 0.99.
- [ ] this interval has a probability of 0.99 of enclosing the true mean $\mu$
- [ ] in the long run, this interval will contain the true mean $\mu$ 99% of the time.
- [x] we have 99% confidence in this interval, because in repeated sampling from the population, the method used to determine such confidence intervals will produce intervals 99% of which will contain $\mu$
- [ ] we have 99% confidence that this interval contains $\mu$ , because if we repeated testing over and over again, 99% of the time this interval would contain $\mu$

##### Question 8
Practical significance will always lead to statistical significance
- [ ] true
- [x] false

##### Question 10
Researchers are studying the yield of a crop in two locations. The researchers are going to compute independent 90% confidence intervals for the mean yield at each location. What is the probability that at least one of the intervals will cover the true mean yields at their location?
- [ ] 0.81
- [ ] 0.19
- [x] 0.99
- [ ] 0.95

Probability that interval for field A contains $\mu$ or that intervale for field B contains $\mu$
$$ P(A\; or\; B) $$
$$ P(A) = .9\qquad P(B) = .9 $$
$$ P(A\; or\; B) = P(A) + P(B) - P(A\; and \; B) $$
$$ = P(A) + P(B) - P(A)P(B) $$
$$ = .9 + .9 - .9^2 = 1.8 - .081 = .99 $$
