[[STATS2141-TutQuestions-Unit5]]
##### Question 1
The proportion of students who own a cell phone on college campuses across the country has increased tremendously over the past few years. It is estimated that approximately 90% of students now own a cell phone. Fifteen students are to be selected at random from a large university. Assume that the proportion of students who own a cell phone at this university is the same as nationwide. Let X = the number of students in the sample of 15 who own a cell phone. What is the standard deviation of the number of students who own a cell phone in a simple random sample of 15 students?
- [x] .077
- [ ] .09
- [x] 1.16
- [ ] 1.35

$$\sigma^2_X = np(1-p)$$
$$ \sigma = \sqrt{15(.9)(.1)} $$
$$ \sigma_X = 1.16 $$

##### Question 2
A population variable has a distribution with a mean of $\mu = 50$ and a variance of $\sigma^2 = 225$. from this population a simple random sample of n observations is to be selected and the mean $\bar x$ of the sample values calculated. How big must the sample size n be so that the standard deviation of the sample mean $\bar x$ is equal to 1.4 - that is, so that $\sigma_x = 1.4$
- [ ] n=11
- [ ] n=161
- [x] n=115
- [ ] n=36
- [ ] n=21

$$ \sigma = 15  $$
$$ \frac{15}{\sqrt n} = 1.4 $$
$$ (\frac{15}{1.4})^2 = n = 114.8 $$
We can do this because the standard deviation of a sample mean is smaller by a factor of $\sqrt n$ when compared to the population mean

##### Question 3
Consider a Poisson distribution with a mean of 4. What is the probability that X < 3?
- [x] .238
- [ ] 0
- [ ] .433
- [ ] None of the Above


$$ P(X = 2) + P(X=1) = \frac{4^2}{2}e^{-4} + 4e^{-4} $$
$$ = .219 $$
##### Question 4
A one-question survey is to be distributed to a random sample of 1500 adults in Ohio. The question asks whether they support an increase in the state sales tax from 5% to 6%, with the additional revenue going to education. Let $\hat p$ denote the proportion of adults in the sample who say they support the increase. Suppose that 40% of all adults in Ohio support the increase. What is the standard deviation, $\sigma_{\hat p}$ of the sampling distribution of $\hat p$
- [ ] .00016
- [x] .0126
- [ ] .24
- [ ] .40

From the Formula Sheet:
$$ \sigma_{\hat p} = \sqrt{\frac{p(1-p)}{n}} $$
$$ = \sqrt{\frac{.4(.6)}{1500}} = .0126 $$
##### Question 5
Suppose X has the B(20, 0.5) distribution. Find the probability P(X < 10).
- [ ] .412
- [ ] .588
- [ ] .127
- [x] None of the Above

From the Formula Sheet:
$\mu_X = np = 20(.5) = 10$
$\sigma_X = \sqrt{np(1-p)} = 20(.5)(.5) = 5$
$$ P(X < 10) = P(z < \frac{10-10}{5}) = P(z<0) = .5 $$
```ad-failure
should be .412
```
##### Question 6
A gasoline tank for a certain car is designed to hold 15 gallons of gas. Suppose that the actual capacity of a randomly selected tank has a distribution that is approximately Normal with a mean of 15.0 gallons and a standard deviation of 0.15 gallon. If four tanks are randomly selected, what is the probability that their average capacity will be between 14.75 and 15.10 gallons?
- [ ] .2397
- [ ] .6808
- [x] .9084
- [ ] .9962

X = # of gallons held
$$ =P(X < 15.10) - P(X < 14.75) $$
$$ =P(z < \frac{15.10-\mu}{\frac{\sigma}{\sqrt{n}}})-P(z < \frac{14.75-\mu}{\frac{\sigma}{\sqrt{n}}}) $$
$$  =P(z < \frac{15.10-15}{\frac{.15}{\sqrt{4}}})-P(z < \frac{14.75-15}{\frac{.15}{\sqrt{4}}})  $$
$$   =P(z < 1.333)-P(z < -3.333) $$
$$ = .9082-.0004 = .9078 $$
##### Question 7
Consider the following strongly skewed distribution of a population.
![[Pasted image 20221110111746.png]]

Which figure below is likely to be a result of sampling the most observations to obtain the distribution of x?
- [ ] ![[Pasted image 20221110112407.png]]
- [ ] ![[Pasted image 20221110112425.png]]
- [x] ![[Pasted image 20221110112439.png]]
- [ ] ![[Pasted image 20221110112449.png]]

##### Question 8
A coin is about to be tossed multiple times. Assume the coin is fair; that is, the probability of heads and the probability of tails are both 0.5. If the coin is tossed six times, what is the probability that fewer than ⅓ of the tosses are heads?
- [ ] .0049
- [x] .094
- [ ] .109
- [ ] .344

$$ \frac{1}{3} \cdot 6  = 2 $$
Strictly Fewer so
$$ P(X = 1) $$
From the Formula Sheet
$$ = \begin{pmatrix}6\\1\end{pmatrix}.5^1(.5^5) = \frac{6!}{1(5!)}.5^1(.5^5) $$
$$ = 6(.5)(.03125) = .09375 = .094 $$
```ad-failure
should be .109
```
##### Question 9
A sample of size n is selected at random from a population that has mean $\mu$ and standard deviation $\sigma$ The sample mean $\bar x$ will be determined from the observations in the sample. Which of the following statements about the sample mean $\bar x$ is true?
- [x] the mean of $\bar x$ is the same as the population mean $\mu$
- [x] The Variance of $\bar x$ is $\frac{\sigma^2}n$ 
- [x] The standard deviation of $\bar x$ decreases as the sample grows
- [x] All of the above statements are true.
- [ ] Only A and B are true.


$$ \sigma_{\bar x} = \sigma/\sqrt n $$
$$  \sigma_{\bar x}^2 = \sigma^2/n  $$
##### Question 10
A small university asked all of its 3000 students, “How much time did you spend studying for your first college exam?” The two histograms below represent the individual distribution and the distribution of the sample means, not necessarily in that order.

Histogram A
![[Pasted image 20221110114333.png]]

Histogram B
![[Pasted image 20221110114316.png]]
What features about a histogram imply that it is the distribution of sample means?
- [x] Distributions of sample means are more symmetric than population distributions.
- [ ] Distributions of sample means are more skewed than population distributions.
- [ ] Distributions of sample means show more variability.
- [ ] Distributions of sample means are always centered at zero.

##### Question 11
Suppose the number of customers at McDonald’s can be modeled as a Poisson distribution where the mean number of customers during any given hour is 95. What is the variance for the distribution of customers at McDonald’s?
- [x] 95
- [ ] 9.747
- [ ] 190
- [ ] None of the Above

##### Question 12
A gasoline tank for a certain car is designed to hold 15 gallons of gas. Suppose that the actual capacity of a randomly selected tank has a distribution that is approximately Normal with a mean of 15.0 gallons and a standard deviation of 0.15 gallon. The manufacturer of this gasoline tank considers the largest 2% of these tanks too large to put on the market. How large does a tank have to be to be considered too large?
- [ ] 15
- [x] 15.31
- [ ] 15.72
- [ ] 16

$$ 2\% = P(X < -?) $$
$$ 2\% = P(z > 2.55) $$
$$ 2.55\cdot\sigma + \mu = 2.55\cdot(.15) + 15 $$
= 15.31

##### Question 13
A gasoline tank for a certain car is designed to hold 15 gallons of gas. Suppose that the actual capacity of a randomly selected tank has a distribution that is approximately Normal with a mean of 15.0 gallons and a standard deviation of 0.15 gallon. What proportion of tanks will hold between 14.75 and 15.10 gallons of gas?
- [ ] .35
- [ ] .6563
- [x] .6997
- [ ] .9833

$$ = P(X < 15.10)-P(X<14.75) $$
$$ = P(z < .6666)-P(z < -1.666) $$
$$ = .7486 - .0475 = .7011 $$
##### Question 14
In a certain game of chance, your chances of winning are 0.2. Assume that outcomes are independent and that you will play the game five times. What is the probability that you win at most once?
- [ ] .0819
- [ ] .2
- [ ] .4096
- [x] .7373

Guesstimate

##### Question 15
The weights of medium oranges packaged by an orchard are Normally distributed with a mean of 14 ounces and a standard deviation of 2 ounces. Ten medium oranges will be randomly selected from a package. What is the sampling distribution of the number of oranges in the sample that weigh more than 14 ounces?
- [ ] N(14,2)
- [ ] N(14,.63)
- [ ] B(14,.2)
- [x] B(10,.5)

$n = 10$
$p = .5$


##### Question 16
In the construction industry, compressive strength of concrete is a crucial characteristic. Suppose that for a particular residential construction job, the concrete tested after 3 days should have a mean compression strength of $\mu = 3000$
with a standard deviation of $\sigma = 50$ . It is known that compressive strength of concrete is Normally distributed. On a construction site, a sample of n = 5 specimens is selected and tested after 3 days. If the concrete has the desired characteristics, what is the probability that the sample mean $\bar x$  will be larger than 3060 psi?
- [ ] .996
- [x] .004
- [ ] .885
- [ ] .115
- [ ] This can’t be determined, because the sample size n = 5 is much too small to rely on the Normal distribution for calculation of the required probability.

$$ P(x > 3060) = P(z > 2.683) = P(z < -2.683) = .0041 $$
$= \frac{3060-3000}{\frac{50}{\sqrt 5}}$