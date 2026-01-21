# EMPLOYEE_ATTRITON


📊 HR Employee Attrition Analysis – End-to-End Machine Learning Project
📌 Project Overview

Employee attrition is one of the most critical challenges faced by organizations, leading to increased hiring costs, loss of skilled talent, and reduced productivity.
This project focuses on performing a complete end-to-end data analysis and machine learning pipeline to understand, analyze, and predict employee attrition using real HR data.

The project combines business understanding, exploratory data analysis (EDA), data preprocessing, visualization, and multiple machine learning models to generate actionable HR insights.

🎯 Problem Statement

Organizations often struggle to:

Identify employees who are likely to leave

Understand key factors driving attrition

Take proactive retention measures

Objective:
Build a data-driven system that:

Analyzes employee behavior and work patterns

Identifies major attrition drivers

Predicts whether an employee is likely to leave the organization

🧠 Objectives

Understand the structure and characteristics of HR employee data

Perform detailed exploratory data analysis (EDA)

Visualize key patterns and relationships affecting attrition

Preprocess numerical and categorical features efficiently

Build and evaluate multiple machine learning models

Provide business-oriented insights and recommendations

📂 Dataset Description

Dataset: HR Employee Attrition Dataset

Target Variable: Attrition (Yes / No)

Features Include:

Demographics (Age, Gender, Education)

Job-related details (Department, JobRole, YearsAtCompany)

Compensation (MonthlyIncome)

Work-life balance & satisfaction

Overtime and performance indicators

🔍 Exploratory Data Analysis (EDA)

The EDA section includes:

Univariate analysis of numerical features

Categorical feature distribution analysis

Attrition vs feature comparison

Correlation heatmap

Advanced visualizations using Matplotlib & Seaborn

📌 Key Insights:

Younger employees show higher attrition rates

Employees working overtime are more likely to leave

Lower monthly income correlates with higher attrition

Job satisfaction plays a major role in retention

⚙️ Data Preprocessing

Missing value and duplicate checks

Feature separation:

Numerical features → StandardScaler

Categorical features → OneHotEncoder

Used Pipeline & ColumnTransformer for clean workflow

Prevented data leakage and ensured reproducibility

🤖 Machine Learning Models Used

Multiple models were implemented and compared:

Logistic Regression (Baseline & interpretable model)

Naive Bayes

K-Nearest Neighbors (KNN)

Random Forest Classifier

Artificial Neural Network (ANN)

📈 Model Evaluation Metrics

Models were evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

ROC Curve & AUC Score

🏆 Model Performance Summary

Logistic Regression provided a strong baseline

Naive Bayes was fast and probabilistic

KNN captured distance-based patterns

Random Forest and ANN delivered the best performance

🧩 Feature Importance

Using Random Forest:

OverTime

MonthlyIncome

JobSatisfaction

YearsAtCompany

These were identified as the most influential factors affecting attrition.

💼 Business Insights & Recommendations

Reduce excessive overtime policies

Improve compensation for lower-income employees

Focus retention strategies on early-career employees

Invest in job satisfaction and work-life balance programs

🚀 Tools & Technologies

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

TensorFlow / Keras (ANN)

Jupyter Notebook

📊 Project Deliverables

✔ Complete Jupyter Notebook (1.5–2 MB detailed analysis)

✔ Professional PowerPoint Presentation (20 slides)

✔ GitHub-ready README documentation

🔮 Future Enhancements

Handle class imbalance using SMOTE

Hyperparameter tuning for models

Deploy model using Streamlit or Flask

Integrate real-time HR data pipelines

👤 Author

Chirag Jangid
Aspiring Data Scientist | Machine Learning Enthusiast

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork or contribute!
