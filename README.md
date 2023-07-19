# Hackathon Project
## Introduction
The dataset contains various factors that contribute to a person's lifestyle. Your task is to build a model that uses these factors to predict whether a person is leading a 'healthy' lifestyle or not. The training set contains 25,920 rows, including whether a person's lifestyle is healthy or not. Use this to train an ML model, then predict whether the 6,480 people in the testing set are leading a healthy or unhealthy lifestyle.
Note: In the target variable, 1 means 'healthy' lifestyle, and 0 means 'unhealthy' lifestyle.

Predicted files are new_model.csv and new_model23.csv and codes are in FINAL_HACKATHON_MAIN.ipynb

Brief report of project-
1) We imported the data from the 'Train_Data' into the jupyter notebook.

2) Then, we handled the missing data by imputing the object column’s by its ‘mode’ and numerical column’s by its ‘mean’.

3) After that we encoded the object columns by using “label encoder”.

4) After encoding we started EDA, first(i.e, univariate analysis) we plotted the distribution plot to check normal distribution and found no skewness.

5) Then we checked for outliers using “boxplot” and then removed outliers in data preprocessing part.

6) We scaled the data after splitting it into x and y using “standard scalar”.

7) Finally, we trained the model using different type of classifiers and evaluation metrics as “accuracy score”.

8) “XGBoost” comes out as the best model and then we predicted values on 'Test_data' and also done the hyperparameter tuning on “XGBoost”.

   
