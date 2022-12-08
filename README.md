# Breast Cancer diagnosis ML classification 
Developed Machine Learning models based on Wisconsin Breast Cancer dataset.

Preprocessed the continuous data using StandardScaler.
Train LogisticRegression, DecisionTree, KNN, SVM, XGBoost ML algorithm to get the best accuracy score.
Cross validation using 10k fold, except for XGBoost. For XGBoost, the dataset is split into train : validation : test = 6 : 2 : 2, and the rest of the models' dataset is split into (train+validation) : test = 8 :2.

The best model algorithm is LogisticRegression, showing 0.9912 accuracy.

Required library versions:
- python=3.10.5
- matplotlib=3.5.2
- pandas=1.4.2
- scikit-learn=1.1.1
- numpy=1.22.4
- xgboost=1.5.1
- shap=0.40.0
- jupyter_client=7.3.1
- jupyter_core=4.10.0
- jupyterlab=3.4.2
- jupyter_server=1.17.0
- jupytext=1.13.8
- rise=5.7.1
- plotly=5.8.0
- ipywidgets=7.7.0
