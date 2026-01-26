# EMPLOYEE_ATTRITON

---
# 🚀 Employee Attrition Prediction
---
*End-to-End Machine Learning Project using Artificial Neural Networks (ANN)*
---
# 📌 Project Overview
---
*Employee attrition (employees leaving an organization) is a critical business problem that directly impacts productivity, hiring costs, and organizational stability.*
---
*This project builds an end-to-end Machine Learning system to predict employee attrition using an Artificial Neural Network (ANN).
By analyzing employee demographic, professional, and behavioral data, the model helps HR teams identify high-risk employees early and take data-driven retention actions.*
---
# 🎯 Project Objectives

> *Understand key factors influencing employee attrition*
> *Perform Exploratory Data Analysis (EDA)*
> *Apply data preprocessing and feature engineering*
> *Build and train an Artificial Neural Network (ANN)*
> *Evaluate model performance using standard metrics*
> *Predict attrition for new/unseen employee data*
---
# 🧠 Why Employee Attrition Prediction Matters

> *High attrition increases recruitment and training costs*
> *Loss of skilled employees reduces team efficiency*
> *Early prediction enables preventive HR strategies*
> *Data-driven decisions outperform intuition-based decisions*
---
# 📊 Dataset Information

> *Source: Kaggle (publicly available HR analytics dataset)*
> *Type: Structured tabular dataset*
> *Domain: Human Resource Analytics*
> *This dataset contains employee demographic details, job roles, compensation, work behavior, and satisfaction-related attributes used to predict employee attrition.*
---
##### 📌 The dataset used in this project was sourced from Kaggle for educational and learning purposes.
---
# 📊 Dataset Description
**Key Columns Explanation** : 
> *Feature	Description*
> *Age - Age of the employee*
> *Department -	Department where employee works*
> *JobRole	- Employee’s role in the company*
> *MonthlyIncome- Monthly salary*
> *JobSatisfaction- Satisfaction level (1–4)*
> *YearsAtCompany - Total years in the company*
> *OverTime	Whether - employee works overtime (Yes/No)*
> *WorkLifeBalance - Work-life balance rating*
> *PerformanceRating - Employee performance score*
> *Attrition - Target variable (Yes / No)*

##### **🎯 Target Variable: Attrition**
---
# 🔄 Project Workflow (End-to-End)

> **Data Loading**

> **Exploratory Data Analysis (EDA)**

> **Data Preprocessing**

> **Train-Test Split**

> **ANN Model Building**

> **Model Training**

> **Model Evaluation**

> **Prediction**
---
# 🧠 Machine Learning Model
*Artificial Neural Network (ANN)*

##### **Why ANN?**

> *Captures complex non-linear relationships*

> *Works well with structured HR datasets*

> *High predictive power for binary classification*

model.compile(
    optimizer=Adam(learning_rate=0.001),
    loss='binary_crossentropy',
    metrics=['accuracy']
)
---
# 📈 Model Evaluation Metrics

> *Accuracy*

> *Precision*

> *Recall*

> *F1-Score*

> *ROC-AUC Curve*
---
# 🔮 Sample Prediction
sample = X.iloc[[0]]
sample_processed = preprocessor.transform(sample)

prediction = model.predict(sample_processed)

print("Attrition Risk:", "Yes" if prediction > 0.5 else "No")
---
# 📌 Key Insights

> *Overtime significantly increases attrition risk*

> *Job satisfaction strongly impacts employee retention*

> *Salary and experience play a major role in attrition decisions*

> *ANN effectively captures complex employee behavior patterns*
---
# ✅ Conclusion

> *The ANN model predicts employee attrition with strong performance*

> *The system supports proactive HR decision-making*

> *Helps organizations reduce attrition using predictive analytics*

> *Demonstrates a complete end-to-end ML pipeline*
---
# 🛠️ Tech Stack

> *Python*

> *Pandas, NumPy*

> *Matplotlib, Seaborn*

> *Scikit-learn*

> *TensorFlow / Keras*
---
# 🙏 Acknowledgement

**I would like to express my sincere gratitude to my guardian and mentor, Mr. Siddarth Sir,
whose guidance, continuous support, and mentorship played a crucial role in helping me
understand machine learning concepts and successfully complete this project.**

**I have learned the core concepts, practical implementation, and end-to-end project development
from Future Vision Institution, Surat, Gujarat, which provided me with strong foundational
knowledge and hands-on learning experience in Machine Learning and Data Analytics.**
---
# 👤 Author

*Chirag Jangid*
*Machine Learning Enthusiast | Data Analytics*
*🚀 Passionate about solving real-world business problems using ML*
---
