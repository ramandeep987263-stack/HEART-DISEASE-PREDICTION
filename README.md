❤️ Heart Disease Risk Analytics & Prediction Platform
📌 Project Overview

The Heart Disease Risk Analytics & Prediction Platform is an end-to-end Machine Learning project designed to predict the likelihood of heart disease using patient health records. The project combines data analysis, predictive modeling, model evaluation, and deployment to provide an intelligent healthcare analytics solution.

The objective is to assist healthcare professionals in identifying high-risk patients early, enabling proactive medical intervention and improving patient outcomes.

🎯 Objectives
Analyze patient health data to identify risk factors associated with heart disease.
Build and compare multiple Machine Learning models.
Evaluate model performance using industry-standard metrics.
Interpret model predictions using feature importance analysis.
Deploy the solution through an interactive Streamlit dashboard.
📊 Dataset

The project uses the Heart Disease Dataset containing patient medical information such as:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate Achieved
Exercise-Induced Angina
ST Depression (Oldpeak)
Slope of Peak Exercise ST Segment
Number of Major Vessels
Thalassemia
Target Variable (Heart Disease Presence)
Dataset Statistics
Total Records: 1,025
Features: 13
Target Variable: Heart Disease (0/1)
🛠️ Technologies Used
Programming Language
Python
Data Analysis
Pandas
NumPy
Data Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-Learn
XGBoost
Model Persistence
Joblib
Dashboard Development
Streamlit
Database
SQLite
Explainable AI
SHAP
Version Control
Git & GitHub
📈 Project Workflow
1. Data Collection
Load heart disease dataset.
Validate structure and data quality.
2. Data Preprocessing
Handle missing values.
Check duplicate records.
Feature scaling using StandardScaler.
3. Exploratory Data Analysis (EDA)
Target distribution analysis.
Correlation analysis.
Risk factor identification.
Feature relationship visualization.
4. Machine Learning Model Development

Implemented the following models:

Logistic Regression

Used as a baseline classification model.

Random Forest Classifier

Used to capture non-linear relationships and determine feature importance.

XGBoost Classifier

Used for high-performance predictive modeling.

📊 Model Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Cross Validation
🔍 Feature Importance Analysis

The most influential features identified by the model include:

Chest Pain Type (cp)
Maximum Heart Rate (thalach)
Number of Major Vessels (ca)
ST Depression (oldpeak)
Thalassemia (thal)

These factors contribute significantly to heart disease prediction.

🧠 Explainable AI

SHAP (SHapley Additive Explanations) is used to:

Interpret model predictions.
Understand feature impact.
Increase model transparency.
Support healthcare decision-making.
💾 Model Deployment

The trained model is saved using Joblib and integrated into a Streamlit application.

Features of the Dashboard
Patient Health Input Form
Real-Time Risk Prediction
Risk Probability Score
Risk Category Classification
User-Friendly Interface
🗄️ Database Integration

SQLite is used to store prediction history.

Stored Information:

Prediction Date
Prediction Probability
Risk Level
Predicted Outcome
