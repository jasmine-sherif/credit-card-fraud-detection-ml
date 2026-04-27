# credit-card-fraud-detection-ml
 Overview:
 
This project builds a machine learning model to detect fraudulent credit card transactions using Python and Scikit-learn. The dataset is highly imbalanced, and special techniques were applied to improve fraud detection performance.

 Techniques Used:
 
Exploratory Data Analysis (EDA)
SMOTE for handling class imbalance
Feature Selection (SelectKBest)
Ensemble Learning (Voting Classifier)
Models: Logistic Regression, Random Forest, XGBoost
Hyperparameter tuning (RandomizedSearchCV)
Cross-validation (StratifiedKFold)

Evaluation Metrics:

Precision
Recall
F1-score
ROC-AUC
Confusion Matrix

Focus was placed on recall due to the importance of detecting fraudulent transactions.

 Model Output:

The final trained model was saved using joblib for future deployment.

 Technologies:

Python, Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, Matplotlib, Seaborn

Disclaimer:

The dataset used in this project is a publicly available credit card fraud detection dataset commonly used for machine learning benchmarking. It is not included in this repository due to size constraints.
