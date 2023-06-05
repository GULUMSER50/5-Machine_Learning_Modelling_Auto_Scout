# 5-Machine_Learning_Modelling_Auto_Scout

![image](https://github.com/GULUMSER50/5-Machine_Learning_Modelling_Auto_Scout/assets/108715553/468752b8-e0b2-4074-94ea-0a4ae0a4978d)

# Summary

The given solution notebook focuses on car price prediction using regression algorithms. The project uses a preprocessed dataset of car features and aims to understand machine learning algorithms. The following tasks are performed in the notebook:

1. Importing modules, loading data, and reviewing the dataset.
2. Data pre-processing, including checking for multicollinearity and outliers, and performing feature engineering and one-hot encoding.
3. Implementing Linear Regression and evaluating the model's performance using various metrics.
4. Implementing Ridge Regression, including scaling the data, and tuning the alpha hyperparameter using cross-validation.
5. Implementing Lasso Regression and evaluating the model's performance.
6. Implementing Elastic-Net Regression and evaluating the model's performance.
7. Visualizing and comparing the performance of the models in a graph.

The notebook also includes additional steps such as checking skewness, performing train-test split, and using visualization techniques like prediction error and residual plots.

The project demonstrates the use of different regression algorithms and provides insights into feature importance and model performance.

Here are the additional model evaluation metrics for the notebook's model:

- Linear Regression (linear_m):
  - R2 Score: 0.901
  - Mean Absolute Error (MAE): 1400.504
  - Root Mean Squared Error (RMSE): 1914.312

- Ridge Regression (ridge_m):
  - R2 Score: 0.901
  - MAE: 1399.757
  - RMSE: 1913.842

- Lasso Regression (lasso_m):
  - R2 Score: 0.901
  - MAE: 1396.803
  - RMSE: 1909.750

- ElasticNet Regression (elastic_m):
  - R2 Score: 0.901
  - MAE: 1396.803
  - RMSE: 1909.750

- Final Model (final_m):
  - R2 Score: 0.877
  - MAE: 1553.998
  - RMSE: 2132.539

These metrics provide insights into the performance of each model. The R2 score indicates the proportion of the variance in the target variable that can be explained by the model, with higher values indicating better performance. The MAE represents the average absolute difference between the predicted and actual values, while the RMSE measures the square root of the average squared difference between the predicted and actual values. Lower values for MAE and RMSE indicate better accuracy and model fit.

Given the purpose of determining the price of a car based on the given features, the overall performance and predictive accuracy of the models should be considered.

Based on the evaluation metrics provided, the Lasso Regression and ElasticNet Regression models seem to perform slightly better than the other models, as they have the lowest MAE and RMSE values. These models have similar R2 scores to the Linear Regression and Ridge Regression models, indicating a good fit to the data.

Considering these factors, either the Lasso Regression or the ElasticNet Regression model would be a good choice for predicting car prices based on the given features. These models have demonstrated good predictive accuracy and can potentially provide reliable price estimates.

However, it's important to note that the final decision should not solely rely on these metrics. Additionally, it could be preferred to further validate the selected model(s) using cross-validation techniques or testing on new datasets to ensure their generalizability and robustness in predicting car prices accurately.
