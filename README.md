# Machine Failure

Classifying the machine failure. Solving the Kaggle Challenge [here](https://www.kaggle.com/competitions/playground-series-s3e17)

The performance of the classiification has increased steadily by using various models. The submission scores are as follows:

| Model        | Score           | 
| ------------- |:-------------:|
| Logistic Regression      | 0.91542 |
| XGBoost      | 0.91618      |
| XGBoost with SMOTE balancing | 0.95512 |

The biggest challenge in predicting the failure is the imbalance of the dataset. The failed machines are very low in number compared to the non failed. To resolve this, I tried to implement data balancing with SMOTE. 

![Alt text](image.png)