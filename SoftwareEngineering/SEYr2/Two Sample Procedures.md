When data comes from two random samples or 2 groups in a randomized experiment:

$\bar x_1 - \bar x_2$ is out best guess for $\mu_1 - \mu_2$

The Standard deviation of $\bar x_1 - \bar x_2$ is 
$$ \sigma_{\bar x_1 - \bar x_2} = \sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma^2_2}{n_2}} $$
Since we dont know $\sigma_1, \sigma_2$ we replace them with $s_1, s_2$(sample standard deviations) the result is the standard error of the statistic $\bar x_1 - \bar x_2$

We standardize the observed difference to obtain a t statistic that tells us how far the observed difference is from its mean in standard deviation units:
$$ t = \frac{(\bar x_1 - \bar x_2)}{\sqrt{\frac{s^2_1}{n_1} + \frac{s^2_2}{n_2}}} $$

we can use the smaller degress of freedom of $n_1, n_2$ for the df of ^

The [[Confidence Interval]] for $\mu_1 - \mu_2$:
$$ (\bar x_1 - \bar x_2) \pm {\sqrt{\frac{s^2_1}{n_1} + \frac{s^2_2}{n_2}}}$$

$$ df = \frac{(\frac{s^2_1}{n_1} + \frac{s^2_2}{n_2})^2}{\frac1{n_1-1}(\frac {s_1^2}{n_1})^2 + \frac1{n_2-1}(\frac {s_2^2}{n_2})^2} $$
### Pooled Two-Sample Procedures
Suppose both populations are normal and have the same standard deviations.

The pooled estimator of $\sigma^2$ is:
$$ s_p^2 = \frac{(n-1)s_1^2 + (n_2-1)s_2^2}{(n_1 + n_2 - 2)} $$
Confidence Interval:
$$ (\bar x_1 - \bar x_2) \pm t^*s_p\sqrt{\frac1{n_1} + \frac1{n_2}} $$
t statistic:
$$ t = \frac{\bar x_1 - \bar x_2}{s_p\sqrt{\frac1{n_1} + \frac1{n_2}}} $$
