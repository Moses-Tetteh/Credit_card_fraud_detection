# Credit_card_fraud_detection

# About Dataset
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The data sets contains transactions made by credit cards by cardholders. This dataset we have found 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the frauds account for 0.172% of all transactions. <br></br>
It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA is Time and Amount. Feature Time contains the seconds between each transaction and the first transaction in the dataset. The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise. <br></br>
# Time<br></br>
Number of seconds elapsed between this transaction and the first transaction in the dataset<br></br>
# V1….V28<br></br>
may be result of a PCA Dimensionality reduction to protect user identities and sensitive features(v1-v28)<br></br>
# Amount<br></br>
Transaction amount<br></br>
# Class<br></br>
The value 1 is for fraudulent transactions, value 0 is for nonfraudulent transactions<br></br>
The dataset was taken from kaggle https://www.kaggle.com/datasets/shayannaveed/credit-card-fraud-detection <br></br>
This project was done with 3 different classification model to check the one which is best for the model training, based on precision, accuracy and recall; `RandomForestClassifier`, `XGBClassifier` and `LogisticRegression`
