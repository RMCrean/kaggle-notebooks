# kaggle-notebooks
A collection of any kaggle notebooks I have created.

Please note that the interactive figures I made with Plotly will not show up on GitHub's notebook viewer (they will show up on kaggle's notebook viewer though).

## Notebooks:


### [1. Credit_Card_Fraud_Classification.ipynb](https://github.com/RMCrean/kaggle-notebooks/blob/master/Credit_Card_Fraud_Classification.ipynb)

[Link to Challenge Main Page](https://www.kaggle.com/mlg-ulb/creditcardfraud)

[Link to My Submission on Kaggle](https://www.kaggle.com/rorycrean/credit-fraud-model-roc-auc-on-validation-set-95)

##### Overview: 

This is a binary classification problem with a highly imbalanced dataset (ratio of approx. 1:600) that is about distinguishing fraudulent card transactions from non-fraudulent transactions. The input features are the purchase amount and a set of 29 principal components (PCs) from principal component analysis (PCA). To tackle this challenge I attempted to use (1) both over and under sampling, (2) feature removal, (3) outlier removal (only from the not fraudulent class, because I did not want to lose any examples from the fraudulent class) and (4) various ML models and hyperparameters (with GridSearchCV).

##### The Final Results Were as follows:

Model | ROC AUC for Train/Test Dataset | ROC AUC for Validation Dataset |
--- | --- | --- |
Logistic Regression | 0.983 | 0.947 |
Random Forest | 0.983 | 0.919 |
Support Vector Machine | 0.985 | 0.931 |
Gradient Boosting | 0.984 | 0.931 |
		


