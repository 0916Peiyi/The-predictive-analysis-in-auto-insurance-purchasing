# The-predictive-analysis-in-auto-insurance-purchasing
Data mining, as a comprehensive discipline, represents a variety of methods or techniques for different analytical capabilities that meet the various needs of an organization, ask different types of questions, and do it use different levels of input or rules. It is also the process of finding anomalies, patterns, and correlations in large datasets to predict outcomes. We can use this information gained from a wide range of technologies to increase revenue, cut costs, improve customer relationships, reduce risk, and more.   

This project aims to use five machine learning methods to analyze the relationships between the customer insurance costs and A-G products and relevant variables. It includes finding the correlations of variables, building the logistic regression models, decision tree, random forest, LightGBM and XGboost. After these steps, we make the conclusions and provide interpretations and recommendations based on the model results.

## About the dataset
The dataset we choose is about the historical transaction information of car insurance that different types of customer purchase. The data dictionary is shown below. Variables include customer IDs, detailed information about customers (ex. location and risk factors), information about quote policies, and costs. 

![image](https://user-images.githubusercontent.com/102696094/175115595-b7a0ea2c-8409-4d6f-9d56-000af5081625.png)


## Data cleaning and Preprocessing
For the data cleaning:
Use Knn imputation to deal with the missing data
Use SMOTE to deal with imbalanced situation of the target variable.
Use Log1p to transform the important feature into normal distribution.

## For the models:
Use hyperparameters tuning to optimize data. And use grid search in the hyperparameter tuning.

In the whole process, I will show how towith overfitting by using separate and different approaches.
