### [[Confidence Interval]]
statistic $\pm$ (critical value($z^*$)) $\cdot$ (standard deviation of statistic)

The sample proportion $\hat p$ is the statistic we use to estimate $p$. The standard deviation of the sampling distribution of $\hat p$ is:
$$ \sigma_{\hat p} = \sqrt{\frac{p(1-p)}{n}} $$
Since we don't know $p$ we replace it with the sample proportion $\hat p$. This gives us the standard Error

This gives us:
$$ \hat p \pm z^*\sqrt{\frac{\hat p(1-\hat p)}{n}} $$
We only use this interval when the actual numbers of successes and failures in the sample are both at least 10

##### Plus 4
Confidence intervals created by the way above are often inaccurate unless the sample is very large. The actual confidence level is often less than the confidence level oyu asked for. What you need is the ==plus 4 estimate:==
$$ \tilde p = \frac{ \#\; of\; successes + 2}{n+4} $$
So the formula becomes:
$$ \tilde p \pm z^*\sqrt{\frac{\tilde p(1-\tilde p)}{n+4}} $$
### z Statistic:
$$ z = \frac{\hat p - p}{\sqrt{\frac{p_0(1-p_0)}{n}}} $$
### Choosing Sample Size for a Confidence Interval
$$ m = z^*\sqrt{\frac{\hat p(1-\hat p)}{n}} $$
Because the margin of error includes the sample proportion $\hat p$ we have to guess the latter value when choosing n. There are two ways to do it:
- Use a guess for $\hat p$ based on past experience or a pilot study
- Use $\hat p=.5$ (this is when margin of error is largest)

## Two Samples
### Sampling Distribution:
##### Mean:
$$ = p_1 - p_2 $$
##### Standard Deviation:
$$ \sqrt{\frac{p_1(1-p_1)}{n_1} + \frac{p_2(1-p_2)}{n_2}} $$
##### Confidence Interval
$$ (\hat p_1 - \hat p_2)\pm z^* \sqrt{\frac{p_1(1-p_1)}{n_1} + \frac{p_2(1-p_2)}{n_2}}  $$
Plus 4 Confidence Interval:
$$ \tilde p = \frac{ \#\; of\; successes + 1}{n+2} $$
$$\tilde p \pm z^*\sqrt{\frac{\tilde p_1(1-\tilde p_1)}{n_1+2} + \frac{\tilde p_2(1-\tilde p_2)}{n_2+2}}$$
##### Standardized Test Statistic
$$ z = \frac{statistic - parameter}{standard\; deviation\; of \; statistic} $$
$$ z = \frac{(\hat p_1 - \hat p_2) - 0}{standard\; deviation\; of \; statistic} $$
If $H_0$: $p_1 = p_2$ is true the parameters are the same. We call their common value p but we need to estimate p, so it makes sense to combine the data from the two samples. The Pooled sample proportion is:
$$ \hat p = \frac{\# \; of\; successes\;in\;both\;samples}{\#\;of\;individuals\;in\;both\;samples} $$
$$ z = \frac{(\hat p_1 - \hat p_2)}{\sqrt{\hat p(1-\hat p)(\frac{1}{n_1} + \frac{1}{n_2})}} $$
##### Choosing Sample Size:
$$ n = (\frac{z^*}{m})^2 (p_1^*(1-p_1^*) + p_2^*(1-p_2^*)) $$
Make sure to round up

