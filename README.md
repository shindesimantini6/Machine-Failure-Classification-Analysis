# Machine Failure

Classifying the machine failure. Solving the Kaggle Challenge [here](https://www.kaggle.com/competitions/playground-series-s3e17)

The performance of the classiification has increased steadily by using various models. The submission scores are as follows:

| Model        | Score           | 
| ------------- |:-------------:|
| Logistic Regression      | 0.91 |
| XGBoost with SMOTE balancing | 0.90432 |
| LightGBM with SMOTE balancing | 0.9615 |

The biggest challenge in predicting the failure is the imbalance of the dataset. The failed machines are very low in number compared to the non failed. To resolve this, I tried the following:
1. Balancing the data with SMOTE
2. Added new features which which reflect the relationship of the features.
3. Dropped features which didn't have any corelation to Machine Failure.

Requirements:
Python
scikit-learn
