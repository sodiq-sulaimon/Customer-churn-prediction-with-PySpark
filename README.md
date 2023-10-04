# Customer-churn-prediction-with-PySpark

## Scenario
A Telecommunications company has a problem of customer churn in their business. The business owner has provided me with some data to work on. My task is to provide recommendations to the company to effectively solve the problem of customer churn and improve customer retention. 

## My approach
To achieve this, I used PySpark to develop a machine learning model based on a decision tree algorithm that identifies the factors that contribute to customer churn. I then provided actionable insights to the company to reduce customer churn and increase customer retention.

** Below are a brief description of the steps I took:** 

### Exploratory Data Analysis:
I explored the dataset to understand the patterns and the data distribution.

### Preprocess and clean the data
I removed the outlier I detected during the EDA phase and used data imputation technique to fill the missing values with the average of the corresponding columns.

### Prepare the input data for the model
I prepared the data for modeling by subsetting the features into numerical and categorical. I then went on to vectorize and normalize the numerical features and converted the categorical features to unique numerical values to generate columns that could be passed on to the decision tree model.

### Train decision tree
I trained a decision tree using the features prepared in the previous step.

### Evaluate the model
I evaluated the model for prediction accauracy and explored different depth values hyperparameter to determine the optimum model.

### Recommendations
I concluded by providing a recommendation based on the findings from my analysis.

PS: Some of the visualization did not render because the data is located on my Google colab. Please open the notebook with colab to see the more interesting notebook. Thanks!

