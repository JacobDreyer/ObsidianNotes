# Stats Midterm Review Note
## Charts
#### [[Bar Chart]]
- Categorical Data
- Displays Frequency of Occurence
#### [[Pie Chart]]
- Categorical Data
- Shows Relative Size to the whole (percent)
#### [[Histogram]]
- Quantitative Data
- Show the distribution.
- Frequency/Count on one axis
- Interval on the other. (ex. 1-10 has 3, 11-20, has 5 etc.)
	- Interval of a variable. a var may range from 1-50 so we creat segments 1-10,11-20, etc.
- Frequency Distribution
	- Can be written in a table
	- By Convention Exclude Right End point.
		- ex. 110-120 and 120 to 130 are ranges. 120 would be included in the 120-130 range
	- Relative Frequncy Distribution shows count relative to the others (percent just in decimal form)
	- 
#### [[Stemplot]]
- Quantitative Data
- Similar to Histograms except it shows each data point
- Consists of Stems and Leaves
	- Stem: Refers to all the other numbers except the Last one
	- Leaf: Refers to the very last number
	- Ex. 30, 31, 32, 35, 35 $\to$ 3 | 0 1 2 5 5
	- Stems go down Low to High, Leaves go Right Low to High
- Split Stemplot
	- Called Splitting the stems
	- We do this when there is too many leaves
	- We duplicate the stems so there is 2 values of each
	- The First stem corresponds to leaves 0-4
	- The Second stem corresponds to leaves 5-9
- Trimming the Leaves
	- Occurs when we have to many Stems
	- Remove the Last digit (The existing Leaf)
	- That number now gets split into stem and leaf
	- Ex. 20 | 1 3 $\to$ 2 | 0
- Back-to-Back Stemplot
	- Same but now you have data on left side and right side
	- Left corresponds to data from something
	- Right Corresponds to Other Data
	- Ex. data from cats and data from dogs $\to$  6 5 4 | 1 | 0
#### [[Time Plot]]
- Quantitative Data
- Show variable changes over time

#### [[Scatterplot]]


## 1.3
#### [[Mode]]
- Measure of Centre
- Refers to Data Value most frequently observed
- Resistant to [[Outliers]]
#### [[Median]]
- Measure of Centre
- Value postioned in the middle of an ordered [[Data Set]]
- physical middle point
- Resistant to Outliers
- Location is $\frac{n+1}2$
#### [[Mean]]
- Measure of Centre
- balance point
- Shift in datapoints just Shifts the mean
$$ \bar x = \frac{\sum x_i}{n} $$
$x_i$ = values in data set
$n$ = number of values in data set
#### [[Range]]
- Measure of Spread
- Max - Min
#### [[Standard Deviation]]
- Measure of Spread
- How close the values in the data set are to the mean
- Variance = $s^2 =$ 
- Shift Does not effect SD
$$ s = \sqrt{\frac{\sum(x_i-\bar x)^2}{n-1}} $$
$n$ = number of data points
$x_i$ = values in data set
$\bar x$ = [[Mean]]

#### Transforming Data:
- Measures of Centre
	- Affected by + - * /
	- $C_{new} = (C_{old})(X) + B$
- Measures of Spread
	- Affected by * /
	- $S_{new} = (S_{old})(X)$

#### Outliers
- A data value that is numerically distant from a data set

#### The [[Five Number Summary]]
- Minimum
- 1st Quartile
	- 25% of data values are smaller
	- median of below the median
	- Location is $\frac{n+1}2$
- [[Median]]
	- Location is $\frac{n+1}2$
- 3rd Quartile
	- 25% of data values are larger
	- median of above the median
	- Location is $\frac{n+1}2$
- Maximum

- 

#### Boxplots
- Uses the [[Five Number Summary]]
- Vertical Lines at each number in the five number summary
- Box around the inner 3 (1st Quartile, Median, 3rd Quartile)
	- This is called the Inter-Quartile range
		- = 3rd Quartile - 1st Quartile
	- Is the Inner 50% of the distribution
- Horizontal lines (Whiskers out to the max and min)
- Modified Boxplot excludes [[Outliers]]
	- Whisker extends to new Max (no vertical line there tho)
	- The outlier is represented by a dot

#### [[Outliers]]
- A data point is an outlier if:
$$ dv < Q1-1.5(IQR) $$
or
$$ dv > Q3 + 1.5(IQR) $$
#### [[Percentile]]
- Describes the percentage of data values that fall at or below another data value
- ex. 50th percentile
	- 50% of data points are as small or smaller
	- in this case its the median

#### Symmetry and Skewness
- Skew Direction
	- A distribution is skewed to the left if it has a long tail extending to the left
- Determinging Skewness For a [[BoxPlot]]
	- Unequal boxes:
		- The Larger side is the side the distribution is skewed to
	- Equal Boxes:
		- Look at Whiskers
			- The Longer Whisker Determines the skew
- Mean and Median
	- Symetrical
		- Mean = Median
	- Asymetrical
		- Skewed to the Left:
			- Mean < Median
		- Skewed to the Right:
			- Mean > Median

#### Variables
- Explanatory Variable
	- Explains the outcome of a study
	- Plotted on the x axis
	- ex. Age of tree
- Response Variable
	- Measures the outcome of a study
	- Plotted on the y axis
	- ex. Height of tree

#### [[Correlation]]
- Denoted by $r$
- Tells about the direction and strength of a linear relationship shared between 2 quantitiative variables
- Can be expressed with [[Scatterplot]]s
- Direction:
	- upward slope: r = +
	- downward slope r = -
- Strength:
	- Perfect Straight upward Slope: r = +1
		- "Perfect Positive Correlation"
	- Perfect Straight downward Slope: r = -1
		- "Perfect Negative Correlation"
	- r = 0: no correlation
$$ r = \frac1{(n-1)s_xs_y}\sum(x_i-\bar x)(y_i-\bar y) $$
$s$ = [[Standard Deviation]]
$\bar x,\bar y$ = [[Mean]]

#### Regression and R-Squared
- [[Regression Line]]
	- Also called Line of Least-Squares Regression
	- Predicts change in y when x increases by 1 unit
$$ \hat y = b_0+b_1x $$
$b_0 = \bar y-b_1\bar x$
$b_1 = r\frac{s_y}{s_x}$
$s =$ [[Standard Deviation]]
$\bar x$ = [[Mean]]
- R-squared = $r^2$ where r is [[Correlation]]
	- $r^2$ has values between 0 and 1
	- Is a measure of how close each data point fits to the regression line
	- Closer to 1, closer to regression line
	- Closer to 0, farther from regression line
- Effect of [[Outliers]]
	- Outliers in y-direction minimally affect regression line
	- Outliers in x-direction greatly affect regression line

#### Residual
- How far off the predicted value is from the actual value
- = Actual Y - Predicted Y = $y_i-\hat y$

#### Extrapolation
- predicting y values outside the range of the data
- Should be avoided if possible

#### Causation vs Association
- Correlation does not imply causation

#### [[Density Curves]]
- Essentially drawing a curve around a distribution/histogram to the general distribution
- Total Area = 1 or 100%
- Ignores outliers
- More practical the larger the population is
- Can be used to make approximations
- Important Rules:
	- Must lie on or above horizontal axis
	- Total area under curve = 1

#### [[Normal Distribution]]
- $\mu$ = population mean. is the centre of the normal distribution 
- $\sigma$ = population standard deviation. spread of normal distribution
- Symmetric
- Standard Normal Distribution
	- centred on 0
	- Standard deviation of 1
	- $z = \frac{x-\mu}{\sigma}$
		- z = z score
##### [[The 68-95-99.7 Rule]]
- 68% of values fall in 1 standard deviation of either side of the mean
	- ex $\sigma$ = .5, $\mu$ = 5. 68% is within 5.5 to 4.5
- 95% falls within 2$\sigma$
- 99.7% fall within $3\sigma$

#### [[Z-Score]]
- each value on the x axis is a z score (of a Standard Normal Distribution)
- tells us how many standard deviations an observation is away from the mean
- A z-score table tells us the total area amount of area contained to the left of any value of z