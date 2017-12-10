### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Awesome job on this assignment! You're getting used to python and pandas, and you're data analysis skills are definitely there! From here on out, keep digging in to the techniques and pythonic code that we use in class. For example, making different plots, using apply() methods to iterate with your own function, statistical tests, etc.


**Some Notes**

* We haven't covered the specifics quite yet, but we won't be using a linear _regression_ model in this example. We will be using a linear model, but it will be a logistic regression, which is a classification technique. Remember that a regression model _usually_ refers to a model that is learning a continuous variable (income, temperature, whatever!) whereas a classification model refers to predicting classes, like our admission (yes or no!).
* Regarding your hypothesis, I think you mean negatively correlated. The current structure of the data has 1, the low end, being the highest/best prestige of school. As it increases, we have lower prestige schools, therefor the correlation would be negative. A subtle point. Another point is that we are actually going to be modeling the _probability_ of being admitted. Thus, what you may be even more informative and explicit is P(admission | prestige = 1) >> P(admission | prestige = 4).

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html
