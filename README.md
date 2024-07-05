# Introduction
Heart disease is one of the leading causes of death globally
According to WHO, 19 million people die due to Heart disease worldwide every year 
One-third of all global deaths are due to heart disease
Analyzing a heart disease data can help in understanding its patterns, risk factors and potential preventive measures
# Data source
I have taken the dataset from https://github.com/DataThinkers/Datasets/blob/main/DS/heart.csv
# Problem statement
Heart disease is a leading cause of death due to lack of awareness and early detection. A predictive model can enable early intervention and reduce mortality
# Objective
Develop a machine learning model to predict the likelihood of heart disease in patients based on their various medical attributes
# Exploratory Data Analysis
1.Distribution of target variable
2.Gender distribution according to the target variable
3.Age Distribution in the dataset
4.Checking pain types
5.Chest pain distribution as per the target variable
6.Fasting blood sugar distribution according to target variable
7.Distribution of continuous features
8.Correlation matrix
# Statistical testing
# Chi Square Test to access the relationship between categorical features and the target variable
All the categorical features are strongly associated with the target variable except Fasting Blood Sugar!!
# Predictive models
# Data selection & Preparation
1.Data cleaning (checking for duplicates and dropping them), String formatting (formatted the column names for better consistency)
2.Data Exploration and Visualization
3.Pre-processed the data in order to implement the Machine Learning models 
# Feature Engineering & Selection
Train test split: Setting our target column (Target) and pre-selecting the rest of the features and 
normalized all the values by using the MinMax Scaler.
# Models used for Testing:
# Classification models
1.Logistic Regression
2.K Neighbors Classifier
3.Support Vector Classifier
4.Decision Tree Classifier
# Ensemble approaches
1.Random forest classifier
2.Gradient boosting classifier 
# Metrics used:
1.Accuracy
2.Precision
3.Recall
4.F1-score
 Finally Classification report is also generated.
# Model Optimization
Hyperparameter tuning technique: GridSearchCV
Gradient Boosting Classifier performed good 
The final Metrics: Accuracy    84%
                   Precision   79%
                   Recall      90%
                   F1-score    84%
# Conclusion & Potential business case
    “Prevention is better than cure”
1.Healthcare providers and Health insurance companies can use this predictive model to identify high-risk patients
2.By proactively managing these high-risk individuals, healthcare providers can prioritize care to prevent severe outcomes
3.Insurers can reduce claims costs through early intervention







