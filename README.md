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

      1) Data Loading and Understanding
      
      2) Data Preprocessing
      
      3) Exploratory Data Analysis
      
      4) Feature Engineering
      
      5) Model Building and Evaluation
      
      6) Hyperparameter Tuning
      
      7) Model Selection
      
      8) Addressing Class Imbalance
      
      9) Final Model Evaluation



Following dependencies are needed to be installed:

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

How to Use

1) Clone the repository

2) Install the required dependencies

3) Run the Jupyter notebook to see the full analysis and model building process
