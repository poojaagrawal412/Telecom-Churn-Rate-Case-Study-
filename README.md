# Telecom-Churn-Rate-Case-Study-
Logistic Regression


Multivariate Logistic Regression - Telecom Churn Example

You will be looking at the telecom churn prediction example. You will use 21 variables related to
 customer behaviour (such as the monthly bill, internet usage etc.) to predict whether a
 particular customer will switch to another telecom provider or not (i.e. churn or not).
 
Problem Statment
You have a telecom firm which has collected data of all its customers. The main types of attributes are:

Demographics (age, gender etc.)
Services availed (internet packs purchased, special offers taken etc.)
Expenses (amount of recharge done per month etc.)
 

Based on all this past information, you want to build a model which will predict whether a particular customer will churn or not,
 i.e. whether they will switch to a different service provider or not. So the variable of interest, i.e. the target variable
 here is ‘Churn’ which will tell us whether or not a particular customer has churned. It is a binary variable - 1 means
 that the customer has churned and 0 means the customer has not churned.
 
 
 Now, as you can clearly see, the first 5 customer IDs are exactly the same for each of these data frames. Hence, using
 the column customer ID, you can collate or merge the data into a single data frame. We'll start with that in the next segment.
 
 Data sets: churn_data.csv,customer_data.csv,internet_data.csv
