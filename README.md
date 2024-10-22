# Credit-Card-Scoring Model
Overview
This project aims to develop a credit scoring model that predicts the creditworthiness of individuals based on historical financial data. By utilizing various machine learning classification algorithms, the model assesses the likelihood of individuals defaulting on loans, helping financial institutions make better lending decisions.

Key Features
Data Preprocessing: The dataset was cleaned and preprocessed to handle missing values, impute necessary fields, and perform feature engineering. Categorical variables were encoded using label encoding and ordinal encoding methods.

Class Imbalance Handling: The dataset was imbalanced, with more non-default cases than default ones. To address this, we applied the SMOTE technique to balance the classes.

Model Training: Several machine learning models were trained, including:

Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
Support Vector Machine (SVM)
Hyperparameter Tuning: RandomizedSearchCV was used to perform hyperparameter tuning, particularly for the Random Forest model, optimizing it for better performance.

Model Evaluation: The models were evaluated using key metrics such as Accuracy, Precision, Recall, F1-score, and Confusion Matrix. These metrics provide insights into the performance and robustness of each model.

Feature Importance Analysis: After training the best model, feature importance analysis was conducted to identify which features contribute the most to the predictions.

Dataset
The dataset consists of various financial attributes such as:

person_age, person_income, person_home_ownership, person_emp_length
loan_amnt, loan_int_rate, loan_status (target variable)
And other features representing the individual's financial background.
Models and Performance
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	0.7334	0.4426	0.8613	0.5847
Confusion Matrix:
 [[2835 1228]
  [ 157  975]]
  
How to Use
Clone the repository:
git clone https://github.com/AyaSaadawi/Credit-Card-Scoring.git
cd Credit-Card-Scoring
Install the required dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook to train the models and evaluate their performance.

Future Work
Explore deep learning models to further improve prediction accuracy.
Integrate additional features for better credit risk assessment.
Deploy the model into a real-world application for financial institutions.
