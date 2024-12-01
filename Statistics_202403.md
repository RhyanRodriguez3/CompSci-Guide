# Stats
> Gas Station Education: An important concept in data engineering.
- “There are lies, damned lies, and Statistics.” – Author Mark Twain
- GOAL: The purpose of statistics is to develop numeracy and find the truth. Using statistics allow us to take the shape of samples that has some randomness and uncertainty and make a guess about the true distribution value that created that sample of data. Stats is a tool but understand the logic and don’t fall prey to presecutor’s fallacy. Probabilities can be misleading. Are events independent? Stats are intangible evidence and subject to scrutiny in cases.


Statistics Intro and Overview

There are two main data types, 

1.	Qualitative (categorical) data which can’t be described by numbers and used to calculate statistics like proportions, a comparative relation to a whole.
2.	Quantitative (numerical) data: can be described by numbers and used to calculate statistics like the average and range.

Data can be measured in four levels,

1.	Nominal: Qualitative data without any order. Ex: Colors.
2.	Ordinal: Qualitative data that can be ordered, but the precise "distance" between each is not meaningful. Ex: Letter grades from A to F.
3.	Interval: Data that can be ordered and the distance between them is objectively meaningful. For example, temperature measured in Fahrenheit. 
4.	Ratio: Data that can be ordered and there is a consistent and meaningful distance between them. For example, money.

Statistics is the practice of collecting and analyzing data. You collect data, called a sample, from the population you want to know more about. A sample is a part of the whole population. 

A parameter is a number that describes the whole population, while a sample statistic is a number that describes the sample. Sample statistics gives us estimates for parameters. There will always be some uncertainty about how accurate estimates are. Uncertainty is often expressed in confidence intervals, the most probable lowest and highest value for the parameter. Confidence levels, expressed as percentages (95%), measure how willing you are to be wrong, called the margin of error (5%).

Statistical measures are calculations that allow us to analyze data and turn it into useful information. 
There are two types of statistics. What are statistical models and what are statistical tests? What are each used for? F test, T test, P value, Stastitical significance, Anova table, degrees of freedom

1.	Descriptive statistics focuses on summarizing the distribution of the sample data.
a.	Use statistical measures such as Mean, Median, and Mode to find the center of the data, where most values are concentrated, and tell where data is “located” on a number line.
b.	Variation describes how spread out the data is from the center. The larger the range, the more spread out your data is. Standard deviation (σ) measures the distance between data points from the mean (μ) of the sample data. Shows. Measures of variation, such as standard deviation, range, and quartiles are used to quantify distance from the center and show how well the mean or median represents the data. 
c.	The shape of the data refers to data distribution, the frequency of data values to the left and right of the center. When median and mode equal, it shows a symmetrical Normal Distribution, aka a “bell curve,” which means the numbers closer to the mean occur more frequently. A low variance shows a narrow bell curve. A Skewed Distribution occurs when the mean is greater than the median and mode which means there are unusually extreme values on one side of the distribution. Bimodal data, produced from more than one sample, shows “Camel curves.”
 

2.	Inferential Statistics focuses on estimation and hypothesis testing, which rely on probability calculation, known as P-values, and probability distributions.
a.	Probability distributions are functions that calculate the probable outcomes of variables. For example, the expected values of a coin toss is 50%. Meaning the more you toss the coin the closer the probability distribution gets to expected value of 50%. Appy the same logic to multiple variables such as dice. The standard normal distribution is a normal distribution where the mean is 0 and the standard deviation is 1.
b.	Normal Distribution, also known as the "Bell Curve," Normally distributed data can be transformed into a standard normal distribution. Standardizing normally distributed data makes it easier to compare different sets of data and used for Calculating confidence intervals and Hypothesis tests. The standard normal distribution is also called the 'Z-distribution' and the values are called 'Z-values' (or Z-scores). A hypothesis is a claim about a population parameter. Hypothesis testing checks how likely a hypothesis is true is based on the sample data. The null hypothesis and the alternative hypothesis are the claims.
 

Data Visualization is the graphical representation of data and information. Data viz allow us to comprehend numbers by visualizing their shape for comparison and relativity. Fundamental viz below.

1.	Tables (Grids): Displays data in tabular format.
a.	Matrix: Depicts values across a grid of squares in different sizes or colors.
b.	Binning: is the technique of creating a category for a quantitative variable. Ex: “Novice” to “Expert.”
2.	Line Charts: Uses a line to show the value of a metric overt time
a.	Dual axis Line Charts: Uses two axes to illustrate a relationship between two variables.
b.	Stacked Area Chart: Uses the stacked area within a line chart to show the value of a metric over time
c.	Absolute Area Chart: Uses the absolute area within a line chart to show the value of a metric over time
3.	Bar Charts: Presents categorial data with rectangular bars.
a.	Vertical Bar Charts: Uses the height of vertical bars to compare data values across categories.
b.	Horizontal Bar Charts: Uses the length of horizontal bars to compare data values across categories.
c.	Combo Charts: Combines a line and bar chart for comparisons of metrics with different units.
4.	Kye Performance Indicators (KPI): Measurements of performance.
a.	Scorecards: Provides quick performance indications as a single numeric or with an additional trend indicator
b.	Multi-Metric KPI: Provides quick performance indicators for two or more metrics.
c.	Comparison KPI: Indicates the progress toward a goal or objective.
d.	Gauge: Measures key indicators progress to a particular target.
5.	Pie Chart shows the frequency of a total value relative to the whole, a composition. 
a.	Ring Chart: Shows the composition of a total value divided by category using a circle with an empty center.
6.	Histograms: A type of bar charts that shows frequency of values in the data, usually in intervals. Shows how the data is distributed.
7.	Box & Whisker Plot: shows the median as a line in the middle of the "box," and range as the tail ends at the box. The left side of the box is the 1st quartile, which represents the first quarter, or 25% of the data. The right side of the box is the 3rd quartile, or 75% of the data. The distance between the sides of the box is called the inter-quartile range (IQR), which tells us where the “middle half” of the values are.
8.	Cumulative Frequency Plot: Like histograms but instead of the values given on the X-axis, there are customized bins, and the bars add the total values.
9.	Scatter Plot: Identifies linear or nonlinear relationships between two variables. Shows clusters and regression.
10.	Map: Uses map to visualize data geographically
a.	Geospatial Service: Uses map box to visualize data geographically
b.	Maps: Uses ESRI maps to visualize data geographically.
11.	Network: Uses links and notes to show relationships between data.

Data viz is about relaying a message or story with the data, so your viewer can easily read and obtain information. Understand that statistics and data viz are tools for persuasion, and it is more important to consider… 

1.	Who wrote it? 
2.	Who published it? 
3.	Who did the science? 
a.	How did they gather the data (Census, sampling methods, data mining)? 
b.	How did they analyze the data? Is the experiment well documented and results replicable?
4.	Who funded the science? 

# FIRST STAGE END (above)
# SECOND STAGE START (Below)



## Correlation & Causation

After collecting the data, we first attempt to organize it. After the data is organized, we group the data into 2 categories. Then we test to see if there are relationships between variables in the data set. Understanding the relationships between variables helps us predict results based on variable changes.

Bivariate data is the simplest data relationship and is a relationship between two continuous variables.

Regression shows the relationship between the dependent variable (on the vertical y-axis) and the independent variable (on the horizontal x-axis). Correlation Coefficient (r) measures how strong the relationship is between the two variables based on direction and closeness.

For example, divide a scatter plot into four quadrants where a line is drawn between the avg (mean) of both axes. Draw a line from left to right connecting the most data points. You will see…

1.	Positive correlation (r=1): The dependent variable increases based on the independent variable.
2.	Negative Correlation (r=-1): The dependent variable decreases based on the independent variable.
3.	Weak/No Correlation (r=0): The data points in a scatter plot are equal on all quadrants.

CORRELATION DOES NOT EQUAL CAUSATION. Just because two variables are related doesn’t mean that one variable causes the other. When one thing (A) correlates with another (B), there are only four possible reasons. 
1.	A causes B
2.	B causes A
3.	An unknown variable “C”, causes both A and B
4.	There is no relationship at all.


Probability #14

-	We use samples of data to guess what the true mean or standard deviation of the population is,
-	we can use a sample of data to guess what the true probability of an event is.
-	two types of probability (p): empirical, and theoretical.
-	Empirical probability is something we observe in actual data, IRL
-	theoretical probability on the other hand, is more of an ideal or a truth of the whole 
-	the empirical probability can be a good estimation of the theoretical one, 
-	ADDITION RULE of probability. 
-	When observations are mutually exclusive, meaning they can't happen at the same time: Add all the p values of the observation.
-	When obsevations are NOT mutually exclusive, meaning they can happen at the same time: Add all the p values of the observation minus the p(non-mutually exclusive event)
-	MULTIPLICATION RULE of probability is used when two or more events are occurring at the same time
-	Get the p-value of when the desired event occurs
-	Get the p-value of when the desired event occurs
-	Two events are considered independent if the probability of one event occurring is not changed by whether or not the second event occurred.
-	Conditional probabilities tell us the probability of Event 1, given that Event 2 has already happened as P(Event 1 | Event 2). 
-	P(Event 2 | Event 1) =  P(Event 1 & Event 2) / P(Event 1)
-	For example, in Medical Screenings doctors want to know P(Cancer & Positive Test) / P(Positive Test)
-	Probability calculate the likelihood or unlikelyhood of an event occurring. Consider the Probability Line Measured from percentages so 0, impossible, to 1 Certain.
-	P(A|B) means the probability of event A occurring given event B has already occurred 
-	So P(A|B)=P(A&B)/P(B) For example, venn diagram of dice. The narrow space between the two circles are
-	Probability is NOT reciprocal. Meaning P(B|A) <> P(A|B)
-	Probability IRL is your email automatically categorizing received emails as Spam using the Naive Baye's Filters. Naive Baye's Theorem is about updating based on new infomration.
-	When we want to predict or show results, we run two identical simulations. Simulations take rules and create a pretend universe that follows those rules. Simulations usually are based on specificity and 
-	The Law of Large Numbers states that even an outcome which has a tiny chance of occurring becomes almost certain if you give it enough opportunities. Law of Large Numbers tells us that as our samples of data get bigger and bigger, our sample mean will be ‘arbitrarily’ close to the true population mean. The law of large numbers is the evidence we need to feel confident that the mean of the samples we analyze is a pretty good guess for the true population mean. And the bigger our samples are, the better we think the guess is! 
-	The Bayesian framework shows us that every event or data point can and should “update” your beliefs but it doesn’t mean you need to completely change your mind.

The Binomial Distribution: Crash Course Statistics #15

-	Binomial Distribution is the likelihood of observing a certain outcome when performing a series of tests for which there are only two possible outcomes. Bernoulli Distribution. It represents the probability of of getting either a success or a failure.
-	Binomial Distribution is the likelihood of observing a certain outcome when performina a series of tests for which there are only two possible outcomes.
-	Probability is the chance of an event occurring. A probability distribution is a table or an equation that links each outcome of a statistical experiment with its probability of occurrence.


GEOMETRIC PROBABILITY FORMULA
-	Geometric probabilities tell you the probability that your first success will be on your nth try.
-	As k increases, the probability of that being your first success gets incredibly low, mostly because you’ll probably have found the flavor that shall not be named already.
-	Geometric probabilities, and probabilities in general, allow you to guess how long you’ll have to wait for something, so you can decide whether it’s worth it.

Randomness: Crash Course Statistics #17
-	Randomness is tied to the idea of uncertainty.
-	Simulations allow us to explore options that didn’t happen, but could have happened. And when you get right down to it, that’s what statistics is all about.
-	the mean is a type of expectation, it’s called the expected value of the data because it's what we “expect” from our data overall.
-	Variance is also an expectation. tells us how spread out we expect the data to be.
-	Skewness tells us whether there are more extreme values on one side, variance tells us how reliable the mean is, skewness can tell us how reliable the variance is.
-	“The mean of the sum is the sum of the means”. Similarly the variance of the sum of two independent variables is the sum of their variances.

Z-Scores and Percentiles: Crash Course Statistics #18

-	Randomness is tied to the idea of uncertainty.
-	Sometimes we want to compare things that aren’t exactly the same, or aren’t measured in the same way. This is where standardization comes in.
ZScores
-	For example, compare ACT and SAT scores. The first thing we can do To make these scores easier to compare is to center both of the distributions around zero. Things that are close to zero indicate a score that was close to the mean, while those far away from zero indicate scores that were either a lot higher. Now measure the distance away from the mean using units of standard deviation. A re-scaled score, which is called a z-score, of 1 indicates a point that is 1 standard deviation higher than the mean, and a z-score of -1 indicates a point that is 1 standard deviation lower than the mean. This all occurs on a normal distribution scale.
-	Z-scores in general allow us to compare things that are not on the same scale, as long as they’re normally distributed.
-	Percentiles tell you what percentage of the population has a score or value that’s lower. The median, is the 50th percentile; exactly half the data is above and below it. Being in the 95th percentile means that you’re in the top 5 percent of scores since 95% are below you.
-	To turn a z score into a raw score, multiply the z-score by the standard deviation Then we add the mean score to get the final score to beat. You define the extremes beyond what you consider is the mean. What value do I need to bring to be considered a high value man?
-	Z-scores help us make comparisons.

The Normal Distribution: Crash Course Statistics #19
-	One reason we talk so much about normal distributions is because distributions of means are normally distributed, even if populations aren’t.
-	In general, when we ask scientific questions, we’re not comparing individual scores we’re comparing groups--or samples--of them. So we’re often concerned with the distributions of the means, not the population.
-	In order to meaningfully compare whether two means are different, we need to know something about their distribution: the sampling distribution of sample means. Also called the sampling distribution for short.
-	Since scientific questions usually ask us to compare groups rather than individuals, this makes our lives a lot easier, because instead of an infinite amount of different distributions to keep track of, we can just keep track of one: the normal distribution.
-	The reason that sampling distributions are almost always normal is laid out in the Central Limit Theorem. The Central Limit Theorem states that the distribution of sample means for an independent, random variable, will get closer and closer to a normal distribution as the size of the sample gets bigger and bigger, even if the original population distribution isn’t normal itself. LOOKUP Population distribution.
-	Many inferential techniques in statistics rely on the assumption that the distribution of sample means is normal, and the Central Limit Theorem allows us to claim that they usually are.
-	this is always true about sampling distributions: Their mean is always the same as the population they’re derived from. - So with large samples, the sample means will be a pretty good estimate of the true population mean.
-	There are two separate distributions we’re talking about. There is 1. the original population distribution that’s generating each individual die roll, and there is a 2. distribution of sample means that tells you the frequency of all the possible sample means you could get by drawing a sample of a certain size from that original population distribution. Again, population distribution. And sampling distribution of sample means.
-	So while the mean of the distribution of sample means is the same as the population’s it’s standard deviation is not,
-	So Part of the mathematical pleasantness of the normal distribution is that if you know the mean and standard deviation, you know the exact shape of the distribution.
-	So use sampling distributions to compare other parameters like proportions, Regression Coefficients, or standard deviations, which also follow the Central Limit Theorem.
-	So when you look at things on a group level instead of the individual level, all these diverse shapes and the populations that make them converge to one common distribution: the normal distribution. And the simplicity of the normal distribution allows us to make meaningful comparisons between groups.

Confidence Intervals: Crash Course Statistics #20
-	So A “confidence interval” is an estimated range of values that seem reasonable based on what we’ve observed. It’s center is still the sample mean, but we’ve got some room on either side for our uncertainty. Confidence intervals quantify our uncertainty. They also demonstrate the tradeoff of accuracy for precision. We have to sacrifice a little bit of accuracy in order to gain more precision. A 100% confidence interval will always contain the true population mean, but it’s useless. A 99% confidence interval will give us a more useful range since it won’t be infinitely ong..., but It’s now possible that our confidence interval won’t contain the true mean.
-	So 95% of the sample means are in this range of a normal distribution.
-	So The 95% in a 95% confidence interval tells us that if we calculated a confidence interval from 100 different samples, about 95 of them would contain the true population mean. Our “confidence” is in the fact that the procedure of calculating this confidence interval will only exclude the population mean 5% of the time. But the confidence intervals usually contain the true population mean.
-	So A z-score tells us the distance between the mean of a distribution and a data point in standard deviations.
-	So With small sample sizes, the distribution of sample means isn’t always exactly normal, so we often use a t-distribution instead of a z-distribution to find out where the middle 95% of our data is.
-	So The t-distribution, like the z-distribution, is a continuous probability distribution that’s unimodal. It’s a useful way to represent sampling distributions.
-	So Generally, sample sizes that are greater than 30 are considered “large enough” because scientists generally believe that sampling distributions where the sample is 30+ are close enough to normal. the general rule is that your sample size need to be big enough. For similar reasons, most people consider that “close enough”.
-	So Standard error (SE) is a statistic that reveals how accurately sample data represents the whole population. It measures the accuracy with which a sample distribution represents a population by using standard deviation. In statistics, a sample mean deviates from the actual mean of a population; this deviation is the standard error of the mean. Where is standard error in a normal distribution?

How P-Values Help Us Test Hypotheses: Crash Course Statistics #21
-	So statistical inference tells us how we can go from describing data we already have to making inferences about data we don’t have.
-	So And uncertainty is at the core of what Inferential Statistics is about: making decisions about ideas, or hypotheses.
-	So We’ve seen that sample parameters like the mean are just estimates of the mean of the population that they are taken from. For example, when we establish a relationship between variables, that is a trial/sample of the mean. we don’t have sufficient evidence that the population mean of Mozart listeners is higher than those who did their work in silence. We may have gotten an especially high sample mean that isn’t close to the true population mean.
-	So So we need a way to test our hypothesis while taking into account the random variation of sample means. There is the actual mean and the sample mean. Our sample means are theoretical.
-	So one common method of testing ideas is Null Hypothesis Significance Testing (NHST). Null Hypothesis Significance testing is a form of the reductio ad absurdum argument which tries to discredit an idea by assuming the idea is true, and then showing that if you make that assumption, something contradictory happens. For example, "reduction to absurdity" proof by contradiction. 
-	So A p-value answers the question of how “rare” your data is by telling you the probability of getting data that’s as extreme as the data you observed if the null hypothesis was true. If your p-value was 0.10 you could say that your sample is in the top 10% most extreme samples we’d expect to see based on the distribution of sample means.
-	So one-sided p-value only tells us the probability of getting a sample mean that’s higher than 2,400. p-values are often two-sided, meaning that we look at how far away a value is from the mean, regardless of if it’s higher or lower . This allows us to reject the null hypothesis if our value is significantly higher than the mean, or if the value is significantly lower than the mean.a two-sided p-value is a measure of how extreme your sample mean is, because it tells you how often you’ll get a value that’s as or more extreme than the one you got. The smaller your p-value is, the more “rare” it would be to get your sample just by random chance alone if the null is true.
-	So in Null Hypothesis Significance Testing, p-values need a cutoff. We could set a cut of at 0.05 and say that a p-value that is less than 0.05 is sufficient evidence to allow us to “reject” the idea that the null hypothesis is true. When we can reject the null hypothesis, we consider our result to be “statistically significant”, which is basically a phrase that just means “unlikely due to random chance alone”. In general, the cutoff of 0.05 means that we want our sample value to be at least in the top 5% of most extreme values in our distribution before we consider the value evidence against that hypothesis.
So what is null distribution?

P-Value Problems: Crash Course Statistics #22
-	So To recap from last time, P-values tell us how “rare” something is. So far, we’ve been using that information to decide whether or not our hypotheses are reasonable, and using P-values to reject or fail to reject an idea. Remember, to calculate a p-value, we first assume that the null distribution is the true distribution our sample was taken from. Then we calculate how often we’d see a value that is at least as extreme as our observed value.
-	So So in probability terms, the p-value is the probability of getting a sample as or more extreme than ours, given that the null hypothesis is true: So all the values that we see in the sampling distribution are means we could actually get if the null hypothesis was true.
-	So The second, related issue is that a p-value tells you how “extreme” your data would be if you assume the null hypothesis is true. We want to know whether the null is correct, or at least probably correct. But we can’t use these p-values alone to tell us about the probability of the null being true or false, even though it can be tempting to think we can. One common misinterpretation of a p-value is that it can tell you the probability that the null hypothesis is true. For example, if a random sample of tuna has a 10% higher mercury content than a random sample of mahi-mahi, it would be incorrect to say that a p-value of 0.02 in this case means there’s only a 2% chance that the null hypothesis is true.
-	So We want to know the probability of the null hypothesis given that we got this data. But that’s not what we get. From the p-value we get the Probability of the data given the null.
-	So A third issue is that if you reject the null, you still don’t have much information about the alternative. When the data is pretty improbable under the null hypothesis, we reject the null and accept the hypothesis that the data came from another distribution that is not the null distribution. We call this the alternative distribution, and the hypothesis that goes with it, the alternative hypothesis.
-	So if the p value we calculated is lower than our alpha, predetermined cutoff of 0.005, then we reject the null hypothesis, but that only means the alternative hypothesis isn't that mean.
-	So A fourth common issue for p-values is more about how we interpret “non-significant” p-values. If our p-value isn’t lower than our predetermined cutoff, our alpha, we “fail to reject”, NOT ACCEPT the null hypothesis. Null hypothesis testing doesn’t allow us to “accept” or provide evidence that the null is true, instead we’ve only failed to provide evidence that it’s false. The absence of evidence is not the evidence of absence. “failing to reject” the null hypothesis doesn’t mean that there isn’t an effect or relationship, it just means we didn’t get enough evidence to say there definitely is one.
-	So A P value less than a predetermined alpha is considered a statistically significant result. A P value greater than or equal to alpha is not a statistically significant result.

Playing with Power: P-Values Pt 3: Crash Course Statistics #23
-	So We don’t always come up with the right answer, even if it seemed reasonable. We want to limit our errors as much as possible. 
-	So P-values tell us how “rare” or “extreme” our sample data would be if it really did come from the null distribution.
-	So we briefly touched on “rejecting” the null hypothesis. Null means nothing so null hypotheses tend to say that there’s no effect, or nothing’s going on.
-	So When we get low p-values, we “reject” the null hypothesis because we’ve decided that our data would be pretty rare if the null was true since the probability of getting data as or more extreme than ours is below our alpha level. That’s option 1.
-	So Option 2 is that our p-value is not lower than our pre-selected cutoff which means that we “fail to reject” the null hypothesis. This means that there are four possible situations: either you correctly reject the null, mistakenly reject the null, correctly fail to reject the null, or mistakenly fail to reject the null.
 
-	So The first error is called a Type I error, which is rejecting the null, even if it’s true. It can therefore only happen if the null is true. Say we’ve decided that our alpha level is 0.05, so we’ll reject the null if our p-value is smaller than 0.05, which means that our sample is in the 5% most extreme values we can expect to get if the null hypothesis were true.
 
-	So Type I errors are essentially False positives: we think we’ve detected an effect, but there isn't one.
-	So And Type II errors are False negatives: there was an effect, we just didn’t see it.
-	Sometimes For this reason, fire alarms tend to favor having type I errors over type II errors. Sometimes we do make the right decision and there are two ways to be right: either the null hypothesis is true and we fail to reject it, or the null hypothesis is false and we do reject it.
-	So Statistical power tells us our chance of detecting an effect if there is one. This is important because the whole reason that we do experiments is to see whether there’s an effect. Statistical power tells us about our ability to detect these effects if they exist. Visually we see that statistical power is affected by how much the null and alternative hypothesis distributions overlap. The more they overlap, the less statistical power we’ll have, because less of the alternative distribution will be to the right of the cutoff.
-	So The distance between the mean of the two distributions represents something called “effect size”. If effect size is large, the groups are further away from each other, if it’s small, they’re pretty close.
-	So And remember, the null and alternative distributions are just sampling distributions. We’ve seen that as you increase the size of your samples, the distribution of sample means gets thinner. And all other things being the same, they overlap less and we have more power to detect an effect. This shrinking represents the fact that in general, the more data we have, the more information we have.
-	So Across many fields it’s considered sufficient to have 80% statistical power or more.
-	So What is a beta level? The beta level (often simply called beta) is the probability of making a Type II error (accepting the null hypothesis when the null hypothesis is false). It is directly related to power, the probability of rejecting the null hypothesis when the null hypothesis is false. If Beta--the proportion of times we will fail to reject the null even though it’s false--is 10%, then we’ll correctly reject the null 90% of the time. This proportion (1-Beta) is called our statistical power. As the name suggests, statistical power is really important and something that we want.
 
You Know I'm All About that Bayes: Crash Course Statistics #24
-	So Our beliefs are numerous, sometimes complex, and consistently changing. So it can be useful to have a way of doing statistical inference that reflects that. This idea about updating beliefs is core to Bayesian statistics and can be used to test hypotheses. We start with some idea or belief about how something works.
-	So Bayes’ Theorem--or Bayes Rule--tells us the that probability of A given B, is the probability of B given A times the probability of A, all divided by the probability of B. And remember that the numerator in this equation is just another--way of writing the probability of A and B, which is P(B|A)*P(A)
-	So This ratio of the probability of our information under one hypothesis--that he’s a fan--compared to another--that he’s not a fan--is called a Bayes’ Factor. Bayes’ Factor represents the amount of information that we’ve learned about our hypotheses from the data. 
-	So simple example of Bayesian Hypothesis Testing to compare the probabilities of different hypotheses based on data that we observe.
-	So In Bayesian Statistics, these things are called: the Prior--what you believed before you saw any evidence the likelihood--a measure of how much your evidence should change your prior beliefs And the Posterior beliefs --what you believe after you’ve seen the evidence. In a more general form we can say that after we see the data, how likely one hypothesis is compared to the other is equal to the ratio of how likely we thought these hypotheses were before we got any evidence, adjusted by the evidence with which the data provided us.
-	So And this is one criticism that Bayesian statistical inference faces. One of the main uses of statistics is science which is supposed to be relatively “objective” and not influenced by opinion, and yet, here’s a method that includes beliefs in its calculation.
-	So Bayesian hypothesis testing provides a structured way to quantify a logical process that we do every day, incorporating new events into the way that we see the world. It provides an explanation...or at least a hypothesis--about why two people can see the same evidence and reach different conclusions. For example, Or the way that you updated your belief that your best friend is a kind, caring person by continuously incorporating evidence of their kindness. In real life you don’t ignore all previous pieces of evidence you saw as soon as you get a new one, and Bayesian Inference allows for you to take your new updated beliefs and update them again.

Bayes in Science and Everyday Life: Crash Course Statistics #25
-	The ideas behind continuous and discrete Bayesian Inference are exactly the same. We take our prior beliefs--what we believe before we’ve seen new evidence--and update it with the likelihood of our evidence.
-	continuous bayes theorem?
-	Theta in statistics? The Greek small letter "theta" θ is usually used in statistics to denote an unknown parameter of interest. In A/B testing it is usually modeled as a random variable. The true value of θ is denoted θ*, while an estimator of theta, usually the maximum likelihood estimate is denoted with a hat above the letter.
-	The Y axis tells us the relative probability of a theta--in this case theta is the probability of getting tails-- and the x axis shows us all the possible values of theta between 0 and 1. We can see that we took our prior distribution (the dotted line)... and updated it using the likelihood of the data, which told us the probability of getting 1 out of 5 tails for EVERY potential probability of getting tails that a coin could have. Once we updated our prior beliefs, about which probabilities are the most likely, our posterior beliefs are represented like this (the solid yellow line).Anything on the curve that is above the dotted prior line represents a theta that became more likely after we saw the data. And anything on the curve that is below the dotted line is a theta that became less likely. 
-	Thetas that are close to 1 and 0 became less likely, while thetas around 0.1-0.5 became more likely.
 
-	an example of how a business might use Bayesian inference. Will Kurt on countbayesie.com an A/B test in the business world. One way to get more information to make your decision is to randomly simulate a bunch of samples - one at a time. The samples come from each of your two posterior distributions and then you count how often the B group with pictures’ click rate is higher than the A group that didn’t get a picture. That percentage will tell you roughly how likely it is that the group B will have a higher click rate than the group A.  That percentage will tell you roughly how likely it is that the group that got pictures will have a higher click rate than the group who did not. You decide that if in 70% of your simulation samples the group with pictures has a higher click rate to take more pics.
 
-	Using Bayesian methods to analyze this question allowed you to “inject” your own prior beliefs into the analysis, which is important when making business decisions. Businesses often want to make the best decision in the most cost-efficient way, which means taking advantage of all the information you have, not only data, but prior knowledge of the field and expert opinion.
-	Using Null Hypothesis Significance testing, researchers could try to address whether all three groups had the same mean score on the test, but even if they rejected the null hypothesis that all three groups are the same, they wouldn’t be able to say how much more likely it was that all three groups were different. Bayesian methods can tell you that. And a Group of researchers did analyze the data this way and found out that the Bayes Factor for these models was about 4,000! What is the difference between Null Hypothesis Significance testing and Bayesian methods?

Test Statistics: Crash Course Statistics #26
-	Sometimes random variation can make it tricky to tell when there are true differences or if it’s just random. There’s actually one idea, which--with a few tweaks--can help us answer ALL of our “is it random...or is it real” questions. Test statistics allow us to quantify how close things are to our expectations or theories.
-	In previous episodes, z-scores helped us understand the idea that differences are relative. A difference of 1 second is meaningful when you are looking at the differences in Olympic races vs amateur races. The amount of variance in a group is really important in judging a difference. Elite Olympic athletes vary only a little measured in seconds Whereas nonprofessionals have more variation; the fastest swimmers could finish a whole minute before the slower swimmers.
-	That’s why test statistics look at the difference between data and what we’d expect to see if the null hypothesis is true. Test statistic: Observed Data - (What we expect if the Null is True) / Average Variation.
-	And you can z-score any normal distribution--like a population distribution. But also a sampling distribution which is the distribution of all possible group means for a certain sample size.in episode 19.
-	Instead of taking an individual score and subtracting the population mean, we take a group mean and subtract the mean of our sampling distribution under the null hypothesis. Then we divide by the standard error, which is the standard deviation of the sampling distribution. So, the z-score--also called the z-statistic--tells us how many standard errors away from the sampling distribution mean our group mean is. 
-	Z-statistics around 1 or -1 tell us that the sample mean is the typical distance we’d expect a typical sample mean to be from the mean of the null hypothesis.
-	The p-value will tell us how rare or extreme our data is so that we can figure out whether we think there’s an effect.
-	We can use z-tests to do hypothesis tests about means, differences between means, proportions, or even differences between proportions?
-	If our observed difference of 6% is large compared to the standard error--which is the amount of variation we expect by chance--we consider the difference to be “statistically significant”. We’ve found evidence suggesting the null might not be accurate.
-	There’s two main ways of telling whether this z-statistic, represents a statistically significant result. The first way is to calculate a “critical” value. A critical value is a value of our test statistic that marks the limits of our “extreme” values. A test statistic that is more extreme than these critical values (that is it’s towards the tails) causes us to reject the null.
-	But sometimes, a z-test won’t apply. And when that happens, we can use the t-distribution and corresponding t-statistic to conduct a hypothesis test. we use a t-test if we don't know the true population standard deviation.
 
-	Look up what is the difference between z tests and t tests. 
-	What is the null hypothesis. What does it mean when the p-value is lower than the alpha. A p-value needs to be smaller than 0.01 to reject the null hypothesis. 
-	So it might have seemed like the larger repair shop was definitely going to be faster but it’s actually not so clear. And this doesn’t mean that there isn’t a difference, we just couldn’t find any evidence that there was one.
-	we used two methods of deciding whether something was significant: critical values and p-values. These two methods are equivalent. Large test statistics and small p-values both refer to samples that are extreme. A test statistic that’s bigger than our critical value would allow us to reject the null hypothesis.  And any test-statistic that’s larger than the critical value will have a p-value less than 0.05. So, the two methods will lead us to the same conclusion. If you have trouble remembering it, this rhyme may help: “Reject H-Oh if the p is too low” These two methods are equivalent. But we often use p-values instead of critical values. This is because each test-statistic, like the z or t statistics, have different critical values, but a p-value of less than 0.05 means that your sample is in the top 5% of extreme samples no matter if you use a z or t test-statistic.
-	Test statistics form the basis of how we can test if things are actually different or what we seeing is just normal variation.  They help us know how likely it is that our results are normal, or if something interesting is going on.

T-Tests: A Matched Pair Made in Heaven: Crash Course Statistics #27
-	Test statistics are variations of a general formula...in all sorts of situations.
-	Test Statistic = Observed Data = What we expect if the null is true
-	The formula for a two sample t-test follows our general test statistic formula:
 

-	define our null. There’s no difference between the two coffee shops. define alternative hypothesis, that there is a difference.
-	Two sample T-Tests estimate the difference between the two unknown population means. It calculates the T-value. 
-	For this kind of t-test, our measure of average variation is the standard error. For two groups, the standard error is calculated differently because we have to account for the sample variance of two groups.
-	When you perform a t-test, you're usually trying to find evidence of a significant difference between population means (2-sample t) or between the population mean and a hypothesized value (1-sample t). The t-value measures the size of the difference relative to the variation in your sample data. Put another way, T is simply the calculated difference represented in units of standard error. The greater the magnitude of T, the greater the evidence against the null hypothesis. This means there is greater evidence that there is a significant difference. The closer T is to 0, the more likely there isn't a significant difference. Link Below
-	https://blog.minitab.com/en/statistics-and-quality-data-analysis/what-are-t-values-and-p-values-in-statistics
-	The closer the T and P values are to 0, rather than the 5% most extreme values at both ends of a T-distribution, we reject the null.
-	Random assignment adds variation when creating scientific tests. For example, results may vary depending on subjects personal preferences. Paired tests are a great solution to this because it pairs subjects and a significant difference between their results makes it easy to identify variation outliers.
-	T-statistics tell you how many standard errors away from the mean our observed difference is. The standard error is the standard deviation of a sample population. It measures the accuracy with which a sample represents a population.
-	Normal distributions have about 68% of their data within one standard deviation from the mean. And about 95% within 2 standard deviations. 
-	Statistical tests are measures to identify variability, with the goal of reducing unnecessary variability so we can see patterns.
-	HYPOTHESIS TESTING is We’re just comparing what we see, to what we think we should see.
Degrees of Freedom and Effect Sizes: Crash Course Statistics #28
-	Degrees of freedom are the number of independent values that can vary in an analysis without breaking any constraints.
-	Effect size tells us how big the effect we observed was, compared to random variation. Effect size tells you how meaningful the relationship between variables or the difference between groups is. Effect sizes help us figure out whether observed effects are practically significant to us.
-	Degrees of freedom help measure accuracy 
-	P-values tell us whether it’s likely something happened by chance alone.

Chi-Square Tests: Crash Course Statistics #29
-	Statistical tests measure differences between observed data and expected data to consider if it is statistically significant.
-	chi-square model measure categorical variables. Measures and checks how and if those categories interact.
-	A chi-square distribution is a continuous probability distribution. The shape of a chi-square distribution depends on its degrees of freedom, k. 
-	We use Chi-squared tests for three things
o	Goodness of fit test: Tests how well certain proportions fit our sample. For example, We can have many categories, but we’re only looking at one variable.
o	Test of Independence tests two categorical variables. Tests of independence look to see whether being a member of one category is independent of the other.
o	Chi-Square test of Homogeneity. Test of homogeneity are looking at whether it’s likely that different samples come from the same population.
-	To calculate the Chi-Square statistic, we need our observed frequencies (which are given) and our expected frequencies, which we need to calculate using rows and columns results.

P-Hacking: Crash Course Statistics #30
-	We’ve talked a lot about how p-values let us know something significant in our data, but those p-values and the data behind them can be manipulated. P-hacking is when analyses are being chosen based on what makes the p-value significant, not what’s the best analysis plan.
-	P-hacking is manipulating data or analyses to artificially get significant p-values.
-	To recap to calculate a p-value, we look at the Null Hypothesis--which is the idea that there’s no effect (value 0). This is called Null Hypothesis testing. In the NHST framework we either reject, or fail to reject the null. This binary decision process leads us to 4 possible scenarios:
o	The null is true, and we correctly fail to reject it (True negative)
o	The null is true, but we incorrectly reject it. (False negative)
o	The null is false, and we correctly reject it. (True positive) This is the one we want becaue failing to reject the null is a lack of any evidence, not evidence that nothing happened.
o	The null is false, and we incorrectly fail to reject it. (False negative)
-	In science, researchers are incentivized to promote their funders agenda. Much of scientific theory is based on p-values. Many researchers conduct many statistical tests, but only report the significant ones, it’s misleading.
-	To identify p-hacking, do review and question their research methodology, specifically what they were testing, the variables, and correlation vs causation. Are they Transparent?

The Replication Crisis: Crash Course Statistics #31
-	To make sure that an Make sure your test is replicable for others to test and produce similar results. Replication is important because it allows researchers to establish facts.
-	There are many ways to analyze a dataset, so provide documentation.
-	A p-value, or statistical significance, does not measure the size of an effect or the importance of a result. we need to get rid of the idea that one significant test is even great evidence of anything.
-	In stats, we are use statistical models to test whether the result is significant through true positives and false negatives. Sometimes, we can fail to get a significant result from a sample, even if the effect is real.
-	Statistical power is the ability to detect real effects.

Regression: Crash Course Statistics #32
-	There are tons of mathematical equations, but they stem from basic conceptual equations. You just need to know the basic equations and apply them in your data tests.
-	y = mx + b is the equation of a straight line. This formula shows the relationship between two variables in an axis.
-	The General Linear Model (GLM). Concept is [Your data] = Model + Error. THe model is the equation and error is the deviation from that expected model.
-	Statistical tests are used to test either your hypothesis or the null hypothesis. 
-	Before conducting a statistical test consider your multivariable relationships, data types such as , and study types.
-	T-tests are used to predict data using categorical data.
-	Statistical models allows us to make inferences. The concept is that stat models allow us to make inferences. general linear models and regression models allow us to make predicions.
-	Statistical tests is hypothesis testing and siginifance testing.
 
-	Regression is shown through scatter plot. We assume relationship is linear. Regression line shows a line that’s as close as possible to all data points at once.

ANOVA: Crash Course Statistics #33
-	ANOVA is a GLM framework used to test the difference between multiple groups (categorical data). It’s a modified version of regression formula. Shown through tables.
-	Statistical tests show whether something is statistically significant, meaning that the result is significant, but is not evidence that it is usable info, jus tells us more about the population that produced it? Tests show how much of an effect a variable has. Your effect size is subjective. Effect size tells you the magnitude of the effect.
-	Statistical models show us how things connect or interact / cause an effect.
-	ANOVAs allow us to analyze the effect of variables with two or more groups on continuous variables.
-	regressions allow us to analyze two continuous variables.

Fitting Models Is like Tetris: Crash Course Statistics #35
-	General Linear Models explain the data we observe by building a model to predict that data, and then keeping track of how close the prediction is.


Supervised Machine Learning: Crash Course Statistics #36
-	Machine Learning (ML) build models to predict future outcomes. It takes data that already has a correct answer, like images that have been labeled as “cat” or "not a cat" and tries to learn how to predict it. It’s supervised because we can tell the model what it got wrong. The computers learn how to do things from data. Common ML models below. Involves feeding the ML model trained data, data sets our ML can learn from, and the testing set, data that tests the ML model. A classifier predict which group something will be in, and classifies it.
o	logistic regression: regression that predicts what’s called the log odds of an event occuring. Once we calculate log odds, we can turn them into probabilities to predict. 
o	Linear Discriminant Analysis: Separating and scoring the right and wrong data sets.
o	Unsupervised Machine Learning: K Nearest Neighbors: Relies on the idea that data points will be similar to other data points that are near it. Whichever categories are closes to that data point we say are like our data point. The K in KNN is a variable representing the number of neighbors we’ll look at for each point, called a centroid. K means clusters. Groups can have subgroups, so clusters have hierarchical groups.
-	Calculate how well an ML model will accurately predict based on new data. 
-	Reducing the number of variables, we deal with is called dimensionality reduction.

Supervised Machine Learning: Crash Course Statistics #36
-	Big data is about harder to have comprehend. With Big data, the ideas is lets take focus on one thing and there. They found, “Individual traits and attributes can be predicted to a high degree of accuracy based on records of users’ Likes.”

Big Data Problems: Crash Course Statistics #39
-	Just as statisticss is open to bias, so is machine learning and algortithms. These statistical model are used in risk assessment programs

Neural Networks: Crash Course Statistics #41
-	Machine learning created Nueral networks. Nueral networks look at data and try to figure our the functions, or set of calculations, that turn the input (variables) into the output (probability number). It has nodes (inputted variables) and a prediction (output result we predict). 
o	We can add layers in between we create called features, this is called deep learning. In summary, Nueral networks learn by figuring out what they got wrong, recalculating and working backwards to determine what values and connections made the output incorrect.
o	There are many different types of neural networks.
	Recurrent neural networks remember the previous outputs.
	Image recognition ML is based on convolutional neural networks, which looks at pixels.

War: Crash Course Statistics #42
-	Computers known as enigma machines decoded messages for WW2, most advancements were made in war because we had to come up with solutions
-	When we create a model to predict things, we’re trying to use data, math, and statistics in order to approximate how the world works. It will never be perfect, but it can always be pretty close.
-	Prediction is dependent on what the model deems important and how much historical data you can collect. We need good, accurate, unbiased data and lots of it. We also need a good model.
-	To know what you know and not what you know is true knowledge.  
-	The signal and the noise – Nate Silver
-	Quick recap, data viz, chi square metrics, machine learning with k cluster, and Bayesian hypothesis testing. ANOVA is analysis of variance. P value, calculated probability, is the probability of finding the observed or more extreme results when the null hypotheses if a study question is true.
-	Statsitcs does not get rid of uncertainty, but can show our biases then we update our beliefs and come up with new ones. Improabble is not impossible.
Spare Notes
-	We need to know how to use stats and how not to use them. 
-	Measures of central tendency and spread identified where a vast majority of the values lie and how spread out they are and assures confidence,
-	The problem is you may not always know the difference between a point that’s valid-but-rare and one that’s a mistake



<details>
 <summary>🛑Sources</summary>

---
- Adriene Hill, YT: CrashCourse Statistics
- freeCodeCamp YT: A Full University Course on Data Science Basics --> https://www.youtube.com/watch?v=xxpc-HPKN28 Data Science Basics 8hrs
- Domain of Science, YT: The Map of Mathematics https://www.youtube.com/@domainofscience
- W3 guide for anyone to understand the important concepts in statistics --> https://www.w3schools.com/statistics/statistics_t_table.php
---
</details>
