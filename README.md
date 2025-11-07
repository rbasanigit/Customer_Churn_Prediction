Customer Churn Prediction (Jupyter Notebook)

A machine learning project focused on building robust classification models to identify customers highly likely to discontinue their service (churn).

This notebook provides a complete workflow from data loading and preparation to advanced model training and comparison, aiming to provide actionable insights for customer retention strategies.

🚀 Features

Exploratory Data Analysis (EDA): Initial data profiling, visualization, and identification of key features driving churn.

Data Preprocessing: Handling categorical variables (encoding) and scaling numerical features for model readiness.

Model Implementation: Training and evaluation of two primary classification algorithms:

Logistic Regression (Baseline Model)

Random Forest Classifier (Ensemble Model)

Performance Comparison: Comprehensive analysis of model accuracy to determine the best predictive solution.

🛠 Tech Stack

Python 3.x

Jupyter / Google Colab (Development Environment)

Pandas & NumPy (Data manipulation)

Scikit-learn (Model building, cross-validation, and evaluation)

📚 Key Findings & Model Performance

The project utilized a standard Customer Churn Dataset (often from a telecommunications context) to predict the binary outcome (Churn or No Churn).

The ensemble model significantly outperformed the linear baseline:

Model

Test Accuracy

Logistic Regression

~81.90%

Random Forest Classifier

~92.37%

This comparison confirms that the non-linear capabilities of the Random Forest algorithm are better suited for capturing the complex feature interactions that lead to customer churn.
