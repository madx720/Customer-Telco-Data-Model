# Customer-Telco-Data-Model


This project aims to predict customer churn for a telecommunications company using machine learning techniques.
Dataset
The dataset used in this project is "WA_Fn-UseC_-Telco-Customer-Churn.csv". It contains information about:
Customer demographics (gender, senior citizen status, partner, dependents)
Account information (tenure, contract type, payment method)
Services used (phone, internet, online security, tech support, etc.)
Charges (monthly and total)
Churn status
Project Structure
The project is structured as follows:
Data Loading and Understanding
Data Preprocessing
Exploratory Data Analysis
Feature Engineering
Model Building and Evaluation
Hyperparameter Tuning
Model Selection
Addressing Class Imbalance
Final Model Evaluation
Dependencies
numpy
pandas
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
Key Findings
The dataset contains 7,043 customer records with 21 features.
There is a class imbalance in the target variable (Churn).
Random Forest Classifier performed the best among the models tested.
Hyperparameter tuning and addressing class imbalance improved model performance.
Models Evaluated
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Evaluation Metrics
Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Future Work
Try more advanced techniques for handling class imbalance.
Experiment with other machine learning algorithms.
Perform feature importance analysis to identify key factors influencing churn.
Develop a user interface for easy model deployment and predictions.
How to Use
Clone the repository
Install the required dependencies
Run the Jupyter notebook to see the full analysis and model building process
