# Credit-Risk-Modelling
Credit card default risk is the chance that companies or individuals will not be able to return the money lent on time.

# Data
![image](https://user-images.githubusercontent.com/75474944/147322785-7c0917e6-3163-42d0-b87a-42ec02b0ae06.png)

# EDA
By analyzing data I found that the customer whose credit score is in 500-700 and >=70% credit used are prone to default.

![image](https://user-images.githubusercontent.com/75474944/147322971-35a5fd17-bb65-45f9-af9e-2419c7726edc.png)
![image](https://user-images.githubusercontent.com/75474944/147322993-bb33282f-d292-49ce-b890-38942347c2a9.png)

# Preprocessing
* Null value imputations for both given train and test data frames.
![image](https://user-images.githubusercontent.com/75474944/147323197-25e7af8b-9cbd-4b31-ad1c-91022c1b3c26.png)

* Class Balancing 50-50%, by taking random samples from class 0. (Random Under Sampling)
* Ordinal Encoding for categorical features, but customer_id and name were dropped.
* Normalizer for all features.
* 0.33 % test size in train test split.

# Modeling
* Random Forest Classifier
* Gradient boosting Classifier
* Xgboost Classifier
* LightGBM Classifier

# Evaluation Metric
`score = 100*(metrics.f1_score(actual, predicted, average= "marco" ))`

A score of final predictions: 92.3709


