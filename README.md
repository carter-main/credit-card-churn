# credit-card-churn

In this project, we built a Logistic Regression model to predict the probability that a customer will churn based on 17 different features. We dropped outliers, found the best comnbination of features and hyperparameters for our model, and identified the coefficient for each feature to see how it impacted the model's output. Finally, we loaded in a sample dataset of users without a churned status and used our model to predict the probabilty that they would. The final version of our model had over 90% accuracy when scored on our test set. This can be found in the file named "Credit Card Churn Logistic Regression".

Next, we took a look into the data and tried to identify any features that had a strong positive or negative correlation with churn but found nothing more significant than 0.37. Then, we took a look at how the feature means between a churned and existing customer differed with some great and others negligible. After that we looked at the significance between the difference of each feature for churned and existing customers via chi-square and two-sample t-test. Finally, we observed at which age customers first opened an account and the difference in income level at each card category. This file is titled "Credit Card Churn Deep Dive".

Source Data: https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m
