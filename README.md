## Description
In this project, I worked on a predictive model to estimate the salaries for software developers in the US. The analysis was based on the 2023 Stack Overflow Survey, which includes responses from over 89,000 developers. The project aimed to understand the impact of coding skills, software knowledge, and other factors on salaries since multiple platforms such as Salary.com rely solely on conventional variables for salary estimation (i.e., gender, age.)​.
​
## Business Questions
What are some non-conventional factors influencing software developer salaries in the U.S.?
How effectively can these factors be in predicting software developers' salary in the US?​
​
## Methodology
Data Collection: 2023 Stack Overflow Survey data (90K rows, 80+ variables)
Data Cleaning: Kept only US Developers earning between 60K and 400K
EDA: Examined Salary distribution accross different developer roles, education level, coding experience.
Feature Engineering: Merged Education Level and Professional Coding Experience into a novel variable.
Data Pre-processing: Transformed the categorical variables (softwares, industry, job role) using one-hot encoding.
Feature Selection: Selected predictors based on highest correlation to salary.
Modeling: tested OLS, Ridge, Lasso, Elastic Net, and Decision Trees.
Evaluation: Chose best model based on Adjusted R-Squared and MSE
​​​​
## Conclusions
Model achieved Adjusted R-Squared of 39.7%, showing that non-conventional variables such as coding experience and specific software knowledge can contribute to more accurate Salary Predictions. 
Combining Education Level and Professional Coding experience into a novel variable strengths prediction. 
Experience with Python, Objective-C, PostgreSQL, and Snowflake can lead to higher salaries.
