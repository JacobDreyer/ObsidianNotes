## Describing Distributions
#### Measuring Centre
##### Mean
$$ \bar{x} = \frac{x_1+x_2+\cdots+x_n}{n} $$

##### Median
- The midpoint of a distribution
	- Half the numbers are larger
	- Half Smaller
- If the # of observations is even the median is the average of the centre 2 points

##### Comparing Mean and Median
- The mean and median of a roughly symetric distribution are close together
- If the distribution is exactly symmetric the mean and median are exactly the same
- In a skewed distribution the mean is usually farther out in the long tail than the median

#### Measuring Spread
##### The Quartiles
- Arrange the observations in increasing order and find the median
- The first Quartile $Q_1$ is the median of observations located to the left of the median in the ordered list 
- The third Quartile $Q_3$ is the median of the observations located to the right of the median in the ordered list

#### The Five-Number Summary
- The minimum and maximum values alone tell us little about the distributions as a whole. Likewise, the median and quartiles tell us little about the tails of a distribution.
- To get a quick summary of both spread, combine all five numbers

![[BoxPlot]]

#### The [[Standard Deviation]]
- The most common measure of spread looks at how far each observation is from the mean. This measure is called the standard deviation.
- measures the average distance of the observations from their mean.
$$ s_x^2 = \frac{(x_1 - \bar x)^2 + (x_2-\bar x)^2 + \cdots + (x_n-\bar x)^2}{n-1} = \frac{1}{n-1}\sum(x_i-\bar x)^2 $$
- s measures spread about the mean and should only be used  when the mean is an appropriate measure of centre
- s = 0 only when all observations are the same value
- s is not resistant to outliers
- s has same units of measurements as the data

#### Choosing
- Median and IQR are usually better for a skewed distribution or a distribution with outliers
- Use mean and standard deviation only for symmetric distributions without outliers

```ad-note
Sometimes, the overall pattern of a large number of observations is so regular we caan describe it by a smooth curve. [[Density Curves]]
```
