# ML_regression_project-Rossmann_sales_prediction
This project involves daily retail sales prediction for up to six weeks in advance of Rossmann stores. The Rossmann stores are drug stores spread out in 7 European countries and are over 3000 in number. The given dataset of 1115 Rossmann stores contains information about the different Rossmann stores, their types, the kinds of goods they sell, the no. of customers entering a given day, information about promotional offers, holidays, sales, etc for roughly 3 years i.e., from 2013-2015. By using different regression models, the forecasting of sales is done and the results are depicted.
# Problem Statement
Given a dataset containing sales and probable factors affecting sales of Rossmann stores, the business objective is to forecast the next six week's sales of Rossmann stores by analyzing it.
# Conclusions:
Based on the insights gathered from the analysis of the dataset, we can draw the following conclusions:

#### Store Operations:
The store is typically open most of the time, with Sunday being the day it's closed the most.
There are very few school holidays and even fewer state holidays observed in the dataset.
#### Sales Trends:
Sales show a linear relationship with the number of customers, which is expected.
Sales see a significant increase when promotional activities are conducted, with roughly a two-fold increase during promotions.
Sales peak during the months of December and November (due to Christmas), followed by July and March, while sales are lowest in January, May, and October.
The majority of sales (82.1%) are not affected by school holidays, and only a small percentage (3.1%) is impacted by state holidays.
Overall, there isn't a significant difference in sales across the three years covered in the dataset.
#### Correlations:
There is a high correlation (0.89) between sales and the number of customers, which is intuitive.
Moderate correlations are observed between sales and whether the store is open (0.68) and between sales and promotional activities (0.45).
#### Store Types:
Store Type C has the highest number of stores, with more Type A and Type C assortments.
Store Type D has more Type C assortments than Type A assortments.
Store Type B, while having fewer stores, has the highest average number of customers and sales.
#### Promotional Impact:
Promotions (both Promo and Promo2) lead to a significant increase in sales, with Promo being more effective than Promo2.
Sales are consistently higher with promotions, regardless of the year.
#### Weekly Sales Patterns:
Negligible sales are observed on Sundays when the store is closed.
Sales with promotions are highest on Mondays and gradually decrease throughout the week.
Promo activities are typically conducted during the first five days of the week, resulting in higher sales during this period.
#### Competitor Impact:
Stores tend to perform better (in terms of both sales and customers) when competitor stores are located far away.
Sales Patterns: After performing hypothesis testing, it can be seen that sales are significantly higher after the 10th day of each month. Also, stores sell more in the second half of the year and Promo2 affects the sales.
Machine Learning Analysis: Analysis after applying various machine learning models for regression: Catboost regression gives the lowest RMSE while Random Forest gives the lowest MAPE.
