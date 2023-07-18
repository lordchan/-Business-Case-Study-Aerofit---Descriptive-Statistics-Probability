# Business Case Study Aerofit: Descriptive Statistics and Probability
## About Aerofit

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.


## Business Problem

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

## Dataset [link](https://github.com/lordchan/-Business-Case-Study-Aerofit---Descriptive-Statistics-Probability/blob/main/Aerofit_dataset.csv)
## Product Portfolio:

The KP281 is an entry-level treadmill that sells for $1,500.
The KP481 is for mid-level runners that sell for $1,750.
The KP781 treadmill is having advanced features that sell for $2,500.

## What and all is involved in the process of solving this case study.
1. Importing the dataset and doing usual data analysis steps like checking the structure & characteristics of the dataset.
2. Detecting Outliers (using boxplot, “describe” method by checking the difference between mean and median)
3. Checking if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
4. Representing the marginal probability like - what percent of customers have purchased KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
5. Checking the correlation among different factors using heat maps or pair plots.
6. With all the above steps we can answer questions like: What is the probability of a male customer buying a KP781 treadmill?
7. Customer Profiling - Categorization of users.
8. Categorization of numerical data based on age:young/old, income:wealthy/middle income, fitness:fit/not fit, usage:regular/casual, education:high/low in order to classify users and use crosstab function in pandas. 
9. Probability- marginal, conditional probability using pandas crosstab. This is used to find the probability of a segment of customer like educated - fit - male or high income-regular using - partnered female etc., of buying a certain product.
10. Some recommendations and actionable insights, based on the inferences.

The jupyter notebook code is [here](https://github.com/lordchan/-Business-Case-Study-Aerofit---Descriptive-Statistics-Probability/blob/main/Aerofit.ipynb)

## Recommendations:
1. We should try to sell the product KP481 to middle class females who want to run more.
2. We should market the product KP281 to Middle class males and females who want to run less.
3. We should recommend KP281 to partnered female and KP481 to single females.
4. We should market the product KP281 to wealthy individuals(both males and females) who want to run more.
5. For fit males who want to use less we should recommend KP481, whereas for fit females who want to use less we should recommend KP281.
6. Overall casual users whether fit or not should be recommended KP281 or KP481.
7. Fit individuals(males/females) who want to use regularly should be recommended KP781.
8. Regular users(males/females) who are not fit should be recommended KP281 and KP481.
9. Middle income unfit individuals should be recommended KP281.
10. KP781 is best suited for Wealthy and fit individuals.
11. Wealthy individuals who are not fit should be recommended KP481.
12. Middle income fit females should be recommended KP481.
