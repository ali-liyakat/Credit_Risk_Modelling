### Overview

A machine learning project to predict the likelihood of loan default using historical customer, loan, and bureau data. The goal is to build a robust and interpretable model for credit risk assessment.

### Tech Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · Optuna · Matplotlib

### Workflow

Data Preprocessing: cleaning, feature selection (IV, VIF, domain knowledge), and Min–Max scaling.

Modeling: Logistic Regression, Random Forest, and XGBoost.

Hyperparameter Tuning: Optuna and RandomizedSearchCV.

Evaluation: AUC, Gini, KS Statistic, and classification metrics.

### Results

Achieved AUC > 0.85, KS > 40.

Consistent performance across validation and test sets.

Interpretable model explaining key risk drivers.
