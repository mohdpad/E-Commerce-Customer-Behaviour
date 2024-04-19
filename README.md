# E-Commerce Customer Behaviour Dataset Analysis
### Overview
This project explores the E-commerce Customer Behavior Dataset, focusing on understanding the purchasing habits and preferences of e-commerce customers. The analysis includes data cleaning, exploratory data analysis (EDA), hypothesis testing, and model building using R. This document serves as a comprehensive guide to the dataset, the analyses performed, and insights derived from the data.

### Dataset Description
The E-commerce Customer Behavior Dataset comprises 350 observations and 11 attributes, detailing customer demographics, purchase details, and customer satisfaction metrics. Attributes include Customer ID, Gender, Age, City, Membership Type, Total Spend, Items Purchased, Average Rating, Discount Applied, Days Since Last Purchase, and Satisfaction Level.

### Prerequisites
To run the analysis scripts, you will need R installed on your machine along with the following R packages:
* tidyverse 
* MASS
* MLmetrics
* ggplot2

### Data Cleaning and Preparation
Data cleaning steps included converting categorical variables into factors and handling any data inconsistencies.

### Exploratory Data Analysis (EDA)
Various EDA techniques were employed to understand the distribution and relationships among the variables. This includes histograms of customer ages and boxplots to compare total spend by membership type.

### Hypothesis Testing
The analysis includes hypothesis testing to evaluate the impact of customer satisfaction on purchase frequency:

* Null Hypothesis (H0): The average number of days since the last purchase for satisfied and unsatisfied customers is the same.
* Alternative Hypothesis (H1): The average number of days since the last purchase for satisfied customers is different from that of unsatisfied customers.

### Model Building
The project explores linear regression modeling, using both forward and backward stepwise selection methods to identify significant predictors of total spend. The models are validated using the training and testing datasets, with metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE) calculated to assess model performance.

### Insights and Business Implications
The analysis provides valuable insights into customer behavior, such as the relationship between membership type and spending, the impact of customer satisfaction on purchase frequency, and demographic trends. These insights can inform targeted marketing strategies and customer retention efforts.

### Usage
To run the analysis:

1. Clone the repository.
2. Ensure that R and necessary packages are installed.
3. Execute the scripts in the R environment.

### Contributors
This project was developed by Mohammed Padghawala as part of a final project submission.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.
