# breastcancer
Machine Learning model based on Wisconsin Breast Cancer dataset.

Preprocessed the data using StandardScaler.
Train LogisticRegression, DecisionTree, KNN, SVM, XGBoost ML algorithm to get the best accuracy score.
Cross validation using 10k fold, except for XGBoost. For XGBoost, the dataset is split into train : validation : test = 6 : 2 : 2, and the rest of the models' dataset is split into (train+validation) : test = 8 :2.

The best model algorithm is LogisticRegression, showing 0.9912 accuracy.
