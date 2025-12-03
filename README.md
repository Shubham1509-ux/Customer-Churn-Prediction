📊 Customer Churn Prediction (Telco Dataset)

This project builds an end-to-end Customer Churn Prediction system using the popular Telco Customer Churn dataset. It includes data cleaning, exploratory data analysis, feature engineering, handling class imbalance, and building a machine learning model to predict whether a customer is likely to churn.

🔍 Key Features

Exploratory Data Analysis (EDA)

Distribution analysis of churn vs non-churn customers

Visual insights using Matplotlib & Seaborn

Identification of key churn-driving factors

Data Preprocessing

Handling missing values

Encoding categorical features

Standardization and transformation

Removal of anomalies

Class Imbalance Handling

Applied SMOTEENN (oversampling + undersampling) to balance minority/majority classes

Model Building

Built a RandomForestClassifier for churn prediction

Tuned parameters like number of trees, depth, & leaf nodes

Model evaluation using accuracy, confusion matrix, and classification report

Model Exporting

Trained model saved using pickle for deployment

Load & score functionality included

🧰 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Imbalanced-learn (SMOTEENN)

Pickle

📁 Dataset

This project uses the official WA_Fn-UseC_-Telco-Customer-Churn.csv dataset containing customer demographics, usage patterns, and account details.
