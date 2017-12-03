### ***Project 1 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this first assignment! The goal of this research is clear, but the plan is not quite entirely clear. We haven't quite covered too much of it in class yet, but the purpose of the analysis plan is to lay out each step you would want to take to break down your goal (finding out/modeling factors for increasing likelihood of admission). This can include: laying out the assumptions you have about your data, finding out how you will pull/source your data, finding the distribution of the data, finding and handling outliers, finding and handling missing values, re-shaping or formatting the data, and much more!

**Some Notes**

* *Q.3a* You are right, outliers can skew averages, and we may want to look at a metric like the median. Also, it is good to note that outliers will impact the models that we build and statistical methods we apply. We will discuss this in class, but we usually have to find some way to handle them intelligently via some statistical statement (ie. maybe a data point is an outlier if it is 2 standard deviations from the mean!).
* *Q.4a/b* Colinearity isn't quite that two covariates exhibit same variance, two variables might have totally different variances, but they may *behave* similarly. Colinearity refers to two points with a linear relationship. Meaning they can be fit on a line. We can test for this via a linear estimation of their co-variance w/ a correlation matrix!

**Something to think about**

We touch on this a bit in class, but think about how you can apply statistical tests to your data. There are many handy tests to determine difference of means (very useful), tests to determine assumptions of an underlying distribution, etc. For example, there are specific tests which will estimate how close a given distribution is to a normal distribution.

Also, check out this KDNuggets post for [outlier analysis](https://www.kdnuggets.com/2017/02/removing-outliers-standard-deviation-python.html) in Python! KDNuggets is a great blog for all things Data Science.
