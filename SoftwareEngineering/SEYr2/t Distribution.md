When we don't know the standard deviation $\sigma$ we can estimate it using the sample standard deviation $s_x$. 

However this new statistic does not have [[Normal Distribution]].

It instead has a t Distribution. A t distribution is similar to a normal distribution except it has more area in the tails and the peak is shorter

There is a different t distribution for each sample size. It is determined by the Degrees of Freedom (df)
$$ df = n-1 $$

The standarized value: the t statistic:
$$ t = \frac{\bar x - \mu}{\frac{s_x}{\sqrt n}} $$

As the degrees of freedom increases the t density curve becomes closer to the standard normal curve

A [[Confidence Interval]] for $\mu$ is
$$ \bar x\pm t^* \frac{s_x}{\sqrt n} $$
where the margin of error is:
$$ t^* \frac{s_x}{\sqrt n} $$

### Using t Procedures
- Sample size of at least 15:
	- can be used unless in presence of outliers or strong skewness
- Sample size less than 15
	- Use t procedures if the data appears to be close to normal
- Large samples ( > 40)
	- the t procedures can be used even for clearly skewed distributions.

### [[Two Sample Procedures]]
![[Two Sample Procedures]]

### Choosing Sample Size
1. Get initial sample size by replacing $t^*$ with $z^*$. Compute n = $(z^*s^*/m)^2$ and round up to nearest integer
2. Use this sample size to obtain $t^*$ and check whether $m\geq t^*s^*/\sqrt n$ 
3. If the requiment is not satisfied increase n by 1 and repeat step 2

### Power
The probability that the test will reject the null hypothesis when the alternative value of the mean is true.

##### Power of the Two-Sample t Test
Non-Centrality Parameter
$$ \delta = \frac{|\mu_1 - \mu_2|}{\sigma\sqrt{\frac1{n_1} + \frac1{n_2}}} $$
Power = $P(z>t^*-\delta)$
