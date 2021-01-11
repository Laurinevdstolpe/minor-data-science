# Explanation of terminology, jargon and definitions 

### fundamentals

- **Machine Learning:** A process where a computer uses an algorithm to gain understanding about a set of data, then makes predictions based on its understanding. There are many types of machine learning techniques; most are classified as either supervised or unsupervised techniques.


- **Algorithms:** An algorithm is a set of instructions we give a computer so it can take values and manipulate them into a usable form. This can be as easy as finding and removing every comma in a paragraph, or as complex as building an equation that predicts how many home runs a baseball player will hit in 2018.


- **Database:** As simply as possible, this is a storage space for data. We mostly use databases with a Database Management System (DBMS), like PostgreSQL or MySQL. These are computer applications that allow us to interact with a database to collect and analyze the information inside.


- **Overfitting:** Overfitting happens when a model considers too much information. It’s like asking a person to read a sentence while looking at a page through a microscope. The patterns that enable understanding get lost in the noise.


- **Regression:** Regression is another supervised machine learning problem. It focuses on how a target value changes as other values within a data set change. Regression problems generally deal with continuous variables, like how square footage and location affect the price of a house.


- **Training and Testing:** This is part of the machine learning workflow. When making a predictive model, you first offer it a set of training data so it can build understanding. Then you pass the model a test set, where it applies its understanding and tries to predict a target value.


- **Underfitting:** Underfitting happens when you don’t offer a model enough information. An example of underfitting would be asking someone to graph the change in temperature over a day and only giving them the high and low. Instead of the smooth curve one might expect, you only have enough information to draw a straight line.



### Fields of focus

- **Data Analysis:** This discipline is the little brother of data science. Data analysis is focused more on answering questions about the present and the past. It uses less complex statistics and generally tries to identify patterns that can improve an organization.


- **Data Science:** Given the rapid expansion of the field, the definition of data science can be hard to nail down. Basically, it’s the discipline of using data and advanced statistics to make predictions. Data science is also focused on creating understanding among messy and disparate data. The “what” a scientist is tackling will differ greatly by employer.


- **Data Visualization:** The art of communicating meaningful data visually. This can involve infographics, traditional plots, or even full data dashboards.


### Statistical tools

- **Correlation:** Correlation is the measure of how much one set of values depends on another. If values increase together, they are positively correlated. If one values from one set increase as the other decreases, they are negatively correlated. There is no correlation when a change in one set has nothing to do with a change in the other.


- **Mean (Average, Expected Value):** A calculation that gives us a sense of a “typical” value for a group of numbers. The mean is the sum of a list of values divided by the number of values in that list. It can be deceiving used on its own, and in practice we use the mean with other statistical values to gain intuition about our data.


- **Median:** In a set of values listed in order, the median is whatever value is in the middle. We often use the median along with the mean to judge if there are values that are unusually high or low in the set. This is an early hint to explore outliers.


- **Normalize:** A set of data is said to be normalized when all of the values have been adjusted to fall within a common range. We normalize data sets to make comparisons easier and more meaningful. For instance, taking movie ratings from a bunch of different websites and adjusting them so they all fall on a scale of 0 to 100.


- **Outlier:** An outlier is a data point that is considered extremely far from other points. They are generally the result of exceptional cases or errors in measurement, and should always be investigated early in a data analysis workflow.


- **Standard Deviation:** The standard deviation of a set of values helps us understand how spread out those values are. This statistic is more useful than the variance because it’s expressed in the same units as the values themselves. Mathematically, the standard deviation is the square root of the variance of a set. It’s often represented by the greek symbol sigma, σ.


- **Time Series:** A time series is a set of data that’s ordered by when each data point ocurred. Think of stock market prices over the course of a month, or the temperature throughout a day.


- **Variance:** The variance of a set of values measures how spread out those values are. Mathematically, it is the average difference between individual values and the mean for the set of values. The square root of the variance for a set gives us the standard deviation, which is more intuitively useful.


### Machine Learning Techniques

- **Feature Selection:** The process of identifying what traits of a data set are going to be the most valuable when building a model. It’s especially helpful with large data sets, as using fewer features will decrease the amount of time and complexity involved in training and testing a model. The process begins with measuring how relevant each feature in a data set is for predicting your target variable. You then choose a subset of features that will lead to a high-performance model.


- **Neural Networks:** A machine learning method that’s very loosely based on neural connections in the brain. Neural networks are a system of connected nodes that are segmented into layers — input, output, and hidden layers. The hidden layers (there can be many) are the heavy lifters used to make predictions. Values from one layer are filtered by the connections to the next layer, until the final set of outputs is given and a prediction is made. A nice video explanation can be found here.


[bron](https://www.dataquest.io/blog/data-science-glossary/)








