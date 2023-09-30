[[Least-Squares Regression]]

When a scatterplot shows a linear relationship between a quantitative explanatory variable x and a quatitative response variable y we can use the least squares line fitted to the data to predict y for a fiven value of x.

If the data are a random sample from a larger population we need statistical inference to answer questions like:
- is there really a linear relationship
- What is the slope?
- How accurate is out prediction

### Regression Inference
We have n observations on a explanatory variable x and a response variable y
- for any fixed value of x; the response y varies according to a normal distribution.
- the mean of y has a straight line relationship with x given by: $\mu_y = \beta_0 + \beta_1x$
- The slope and intercept are unknown parameters
- The standard deviation of y(call it $\sigma$) is the same for all values of x.
	- The value of $\sigma$ is unknown

![[Pasted image 20221217110746.png]]

#### Simple Linear Regression Model:
$$ Data = Fit + Error $$
$$ y_i = (\beta_0+\beta_1x_i) + \epsilon_i $$
Where the $\epsilon_i$ are independent and normally distributed $N(0,\sigma)$

Linear regresion assumes equal variance of y( $\sigma$ is the same for all values of x)

The best estimate for $\mu_y = \beta_0 + \beta_1x$ is $\hat y = b_0 + b_1x$

Therefore the estimates are:
$\beta_1$ is $b_1 = r\frac{s_y}{s_x}$
$\beta_0$ is $b_0 = \bar y - b_1\bar x$

Confidence interval of $\beta_1$:
$$ b_1\pm t^*\cdot(standard\; error\; of\; estimate) $$
$t^*$ is the critical value for the [[t Distribution]] with $df = n-2$ having area C between $-t^*$ and $t^*$



##### Regression Standard Error
calculated from the residuals:

$$ s = \sqrt{\frac{\sum(y_i-\hat y_i)^2}{n-2}} $$

s is essentially an unbiased estimate of the regression standard deviation $\sigma$

##### Significance Test
To test hypothesis $H_0 : \beta_1 =$ hypothesized value compute test statistic:
$$ t = \frac{b_1-hypothesized\; value}{SE_{b_1}} $$
SE = standard error
Use the t distribution with $df = n-2$

## More Details
standard deviation (s) of the n residuals:
$$ s^2 = \frac{\sum(y_i-\hat y_i)^2}{n-2} = \frac{SSE}{DFE} = MSE $$
Mean Square Model: $MSM = SSM / DFM$
Mean Square Error: $MSE = SSE/DFE$

Sum of Squares Model: $SSM = \sum_{i=1}^n(\hat y_i - \bar y)^2 \qquad df=1$
Sum of Squares error: $SSE = \sum_{i=1}^n( y_i - \hat y_i)^2 \qquad df = n-2$
Sum of Squares Total: $SST = \sum_{i=1}^n(y_i - \bar y)^2\qquad df = n-1$

$SST = SS\; model + SS\; error$
$DFT = DF\; model + DF\; error$

#### Standard Errors
$$ SE_{b_1} = \frac{s}{\sqrt{\sum(x_i - \bar x_i)^2}} $$
$$ SE_{b_0} = s\sqrt{\frac{1}{n} + \frac{\bar x^2}{\sum(x_i - \bar x_i)^2}} $$
$$ SE_{\hat \mu} = s\sqrt{\frac{1}{n} + \frac{(x^*-\bar x)^2}{\sum(x^* - \bar x)^2}} $$
$$ SE_{\hat y} = s\sqrt{1+\frac{1}{n} + \frac{(x^*-\bar x)^2}{\sum(x^* - \bar x)^2}} $$

#### Inference for Correlation
When there is no clear explanatory variable the correlation test of significance should be used

Compute the test statistic:
$$ t = \frac{r\sqrt{n-2}}{\sqrt{1-r^2}} $$
$r =$ Correlation coefficient

The P-Value is the area under $t(n-2)$
