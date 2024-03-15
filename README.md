# Customer-lifetime-value-prediction
Customer Lifetime Value Prediction
PROBLEM STATEMENT
In an attempt to enhance customer retention, an auto insurance company operating in the USA is exploring the use of Customer Lifetime Value (CLV) as a metric to identify loyal customers and promote exclusive promotional offers to them. Customer Lifetime Value represents a customer’s value to a company over a period of time. It’s a competitive market for insurance companies, and the insurance premium isn’t the only determining factor in a customer’s decisions.

CLV is a customer-centric metric, and a powerful base to build upon to retain valuable customers, increase revenue from less valuable customers, and improve the customer experience overall. Using CLV effectively can improve customer acquisition and customer retention, prevent churn, help the company to plan its marketing budget, measure the performance of their ads in more detail, and much more.
PROJECT OVERVIEW
The objective of the problem is to accurately predict the Customer Lifetime Value(CLV) of the customer for an Auto Insurance Company
Performed EDA to understand the relation of target variable CLV with the other features.
Statistical Analysis techniques like OLS for numerical and Mann–Whitney U and also Kruskal Wallis test for the categorical variables were performed to find the significance of the features with respect to the target.
Supervised Regression Models like Linear Regression, Ridge Regression, Lasso Regression, DecisionTree Regression, Random Forest Regression and Adaboost Regression.
Using Optuna with Random Forest Regression gave the best RMSE and R^2 score values
DATA DESCRIPTION
-The dataset represents Customer lifetime value of an Auto Insurance Company in the United States, it includes over 24 features and 9134 records to analyze the lifetime value of Customer. -The dataset was collected from UCI Machine Learning Repository

EXPLORATORY DATA ANALYSIS RESULTS (EDA)
Univariate, Bivariate and Multivariate Analysis were performed to bring out important aspects of data into focus for further analysis

SUPERVISED MACHINE LEARNING MODEL
Model	R^2 Score	RMSE
Adaboost Regression	0.855	0.254
Lasso Regression	0.196	0.599
DecisionTree Regression	0.845	0.263
RandomForest Regression	0.899	0.212
Linear Regression	0.263	0.574
Ridge Regression	0.26	0.575
RandomForest with Optuna	0.903	0.208
EVALUATION METRICS
RMSE and R^2 score were chosen as the metric for the models.
FINAL MODEL
By comparing RMSE and R^2 score results of models and then we choose the best model as the Random Forest with Optuna, having the best evaluation scores.

COMCLUSION
It is observed that No of policies, Monthly Premium auto, Total Claim amount, Months Since Policy Inception, Income, Months Since Last Claim, Number of Open Complaints, Coverage_Extended EmploymentStatus_Employed and Renew Offer Type_Offer2 are the important features in predicting the Customer Lifetime Value (CLV).
The customers having more number of policies with high monthly premium will add more value to company.
The type of vehicle or size does not have an impact on the CLV prediction.
The insurance agents should start increasing their policy advertisement for the customers who have more no. of policies, which is the major feature in predicting the C
