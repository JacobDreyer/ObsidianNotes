##### Question 1
The proportion of supermarket customers who do not buy store-brand products is to be estimated. Which of the following scenarios would lead to a sampling distribution of the sample proportion with the lowest variability?
- [ ] Sample 100 customers from the roughly 2000 customers who shop at one store location.
- [ ] Sample 100 customers from the roughly 20,000 customers who shop at the stores citywide.
- [ ] Sample 200 customers from the roughly 2000 customers who shop at one store location
- [x] Sample 300 customers from the roughly 20,000 customers who shop at the stores citywide.

Variability decreases as you increase sample size:
$$ \sigma_{\hat p} = \sqrt{\frac{p(1-p)}{n}} $$
300 is the largest Sample Size 

##### Question 2
It is claimed that 55% of marriages in the state of California end in divorce within the first 15 years.

A large study was started 15 years ago and has been tracking hundreds of marriages in the state of California. Suppose 100 marriages are randomly selected.

What is the probability that fewer than 20 of them ended in divorce?
- [x] Less than .0001
- [ ] .0055
- [ ] .0130
- [ ] .0229
X = # of marriges that end in divorce
 = Binomial Distribution Bin(100, 0.55)

for normal approximation: $np \geq 10$ and n(1-p) > 10:
100 x .55 = 55
opposite = 45

For normal Approximation:
$\mu = np$
$\sigma = \sqrt{np(1-p)}$  
standardize with these variables
$$ P(X < 20) = P(z < -7.035) $$
No values in table A. However as numbers get bigger probabilities get smaller.

##### Question 3
The number of undergraduates at Johns Hopkins University is approximately 2000, and the number at Ohio State University is approximately 40,000.

A simple random sample of 50 undergraduates at Johns Hopkins University will be obtained to estimate the proportion of all Johns Hopkins students who feel that drinking is a problem among college students.

A simple random sample of 50 undergraduates at Ohio State University will be obtained to estimate the proportion of all Ohio State students who feel that drinking is a problem among college students.

What can we conclude about the sampling variability in the sample proportion, $\hat p$ calculated from the sample at Johns Hopkins, as compared to that in the sample proportion from Ohio State?
- [ ] The sample proportion from Johns Hopkins will have less sampling variability than that from Ohio State.
- [ ] The sample proportion from Johns Hopkins will have more sampling variability than that from Ohio State.
- [x] The sample proportion from Johns Hopkins will have about the same sampling variability as that from Ohio State.
- [ ] It is impossible to make any statements about the sampling variability of the two samples, because the students surveyed were different.

$$ \sigma_{\hat p} = \sqrt{\frac{p(1-p)}{n}} $$
##### Question 4
A comprehensive report called the Statistical Report on the Health of Canadians was produced in 1999. It reported that 42% of Canadians 12 years of age or older had their most recent eye examination within the previous year.

If a random sample of 20 Canadians in this age group were selected, the probability that 6, or 30%, of the selected individuals had their most recent eye examinations in the previous year would be:
- [x] $\begin{pmatrix} 20 \\ 6 \end{pmatrix} (0.42)^6(0.58)^{14}$
- [ ] $\begin{pmatrix} 20 \\ 14 \end{pmatrix} (0.42)^{14}(0.58)^{6}$
- [ ] $\begin{pmatrix} 12 \\ 6 \end{pmatrix} (0.42)^6(0.58)^{6}$ 
- [ ] $\begin{pmatrix} 20 \\ 6 \end{pmatrix} (0.3)^6(0.7)^{14}$
- [ ] $\begin{pmatrix} 20 \\ 14 \end{pmatrix} (0.3)^{14}(0.58)^{6}$

X = # of individuals with eye examinations
$$ P(X=6) = \begin{pmatrix}n\\6\end{pmatrix}p^6(1-p)^{n-6} $$
n = 20
p = .42
$$ = \begin{pmatrix}20\\6\end{pmatrix}(.42)^6(.58)^{14} $$
##### Question 5
A college basketball player is known to make 80% of his free throws. At the end of a game, his team is losing by two points. He is fouled attempting a three-point shot and is awarded three free throws.

Assuming that each free throw is independent, what is the probability that he makes at least two of the free throws?
- [ ] .384
- [ ] .64
- [ ] .8
- [x] .896

X = # of free throws made
$$ P(X\geq 2) = P(X = 2) + P(X = 3) $$
$$ = \begin{pmatrix}3\\2\end{pmatrix}.8^2.2^1 + \begin{pmatrix}3\\3\end{pmatrix}.8^3.2^0 $$
$$ = .896 $$
##### Question 6
A random variable X is Normally distributed with mean $\mu_X = 75$ and $\sigma_X = 8$

Let Y be a second Normally distributed random variable with mean $\mu_Y = 70$ and $\sigma_Y = 12$

It is also known that X and Y are independent of one another

Let W be a random variable that is the difference between X and Y; that is, W = X – Y.

What can be said about the distribution of W?
- [ ] W is N(0, 20).
- [ ] W is N(5, 20)
- [ ] W is N(5, –4).
- [x] W is N(5, 14.4).
- [ ] W is N(0, 14.4).

W is normally distributed N($\mu_W, \sigma_W$)
$\mu_W = 5$
$\sigma_W = \sqrt{\sigma_x^2 + \sigma_y^2} = 14.4$

##### Question 7
A study was done to compare the amount of time per day that students at public and private universities spend on Facebook.

The study was composed of 200 students from a private university and 300 students from a public university.

The time that students at a private university spent on Facebook had a Normal distribution with a mean of 220 minutes and a standard deviation of 36 minutes.

The time that students at a public university spent on Facebook had a Normal distribution with a mean of 200 minutes and a standard deviation of 49 minutes

The distribution of the time that students from a community college spend on Facebook is twice the distribution of the time that students from a public university spend on Facebook.

What is the variance of the distribution for community college students?
- [ ] 2401
- [x] 9604
- [ ] 4802
- [ ] None of the Above

C = 2P

$$ \sigma^2_C = \sigma^2_{2P} = 2^2\sigma_p^2 = 4\cdot \sigma_P^2 = 4\cdot 49^2 = 9604 $$
##### Question 8
A study was done to compare the amount of time per day that students at public and private universities spend on Facebook.

The study was composed of 200 students from a private university and 300 students from a public university.

The time that students at a private university spent on Facebook had a Normal distribution with a mean of 220 minutes and a standard deviation of 36 minutes.

The time that students at a public university spent on Facebook had a Normal distribution with a mean of 200 minutes and a standard deviation of 49 minutes.

What is the probability that students at a private university spend less time on Facebook than students at a public university?
- [x] .37
- [ ] .63
- [ ] 0
- [ ] None of the Above

X = time spent by private uni
Y = time spent by public uni

$$ P(X < Y) = P(X-Y < 0) = P(W < 0) $$
$W = N(20, \sqrt{36^2+49^2}) = N(20,60.8)$
$$ = P(z < \frac{0-20}{60.8}) = P(z < -.33) = .3707 $$
##### Question 9
The number of undergraduates at Johns Hopkins University is approximately 2000, and the number at Ohio State University is approximately 40,000.

Suppose that the actual proportion of undergraduates at Johns Hopkins University who feel that drinking is a problem among college students is 67%.

A simple random sample of 50 undergraduates at Johns Hopkins University found that 60% of those sampled felt that drinking was a problem among college students.

To which value(s) can the label “parameter” be applied?
- [ ] 60% only
- [x] 67% only
- [ ] 60% and 67%
- [ ] 50

Parameter is related to population

##### Question 10
Birth weights of babies born to full-term pregnancies follow roughly a Normal distribution.

At Meadowbrook Hospital, the mean weight of babies born to full-term pregnancies is 7 pounds with a standard deviation of 14 ounces (1 pound = 16 ounces).

Dr. Watts (who works at Meadowbrook Hospital) has four deliveries (all for full-term pregnancies) coming up during the night.

Assume that the birth weights of these four babies can be viewed as a simple random sample

What is the probability that all four babies will weigh more than 7.5 pounds?
- [x] .0065
- [ ] .1265
- [ ] .2839
- [ ] .4858

$$ P(X_1 > 7.5)\cdot P(X_2 > 7.5)\cdot P(X_3 > 7.5)\cdot P(X_4 > 7.5) $$

Probability that 1 baby weighs more than 7.5 lbs
$$ P(z > \frac{7.5-7}{.875}) = P(z < -.5714) = .2843 $$
$$ P = .2843^4 = .0065 $$