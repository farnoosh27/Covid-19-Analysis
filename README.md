# Covid-19-Analysis
## Objective 
In this project we aim to address some of the questions with regard to Covid-19.


## Questions
1) Do old people have a higher mortality rate?
2) Are male more likely to die from Covid-19?


## Methodology 

The t-test is being used in this code to determine whether there is a statistically significant difference in the mean age between individuals who died and those who did not.

The null hypothesis of the t-test is that the mean age of individuals who died is equal to the mean age of those who did not die. The alternative hypothesis is that the mean age of individuals who died is different from the mean age of those who did not die.

By running the t-test with a significance level of 0.05, we are testing whether the observed difference in mean age between the two groups is statistically significant or simply due to chance. The t-test output provides a p-value, which tells us the probability of observing a difference in mean age as extreme as the one we observed, assuming that the null hypothesis is true.

If the p-value is less than the significance level (0.05), we can reject the null hypothesis and conclude that there is a statistically significant difference in the mean age between individuals who died and those who did not. If the p-value is greater than the significance level, we fail to reject the null hypothesis, which means that we do not have enough evidence to conclude that there is a significant difference in mean age between the two groups.

## Libraries 
The Hmisc library is a package in R that provides various functions for data manipulation, analysis, and visualization. Some of the commonly used functions in this library include:

* ggplot2 - a powerful data visualization library that allows you to create a wide range of charts and graphs.

* dplyr - a library for data manipulation and transformation, with functions for filtering, grouping, and summarizing data.

* tidyr - a library for data cleaning and reshaping, with functions for converting data between wide and long formats.

* caret - a library for machine learning, with functions for data preprocessing, model training, and model evaluation.

* stringr - a library for working with strings, with functions for text manipulation and pattern matching.

* lubridate - a library for working with dates and times, with functions for parsing, formatting, and manipulating date-time objects.

* tidymodels - a collection of libraries for machine learning, including dplyr, ggplot2, and caret, with a consistent and unified syntax.

* purrr - a library for functional programming, with functions for applying functions to data, iterating over data structures, and working with lists.

* data.table - a library for data manipulation and aggregation, optimized for large datasets and fast performance.

* magrittr - a library for creating pipelines of data transformations, with functions for chaining operations together and improving code readability.
