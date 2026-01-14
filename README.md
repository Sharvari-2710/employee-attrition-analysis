#Employee Attrition Prediction - ML Project

## 📊 Project Overview
This project focuses on analyzing employee data and building a machine learning model to predict Employee Attrition. The goal is to identify key factors
influencing attrition and provide data-driven insights that can support better HR decision-making and retention startegies.

---
## 🎯 Problem Statement
Employee Attrition negatively impacts organizational activity and operational efficiency. The challenge addressed in this project is to predict whether an employee is likely
to leave the organization based on historical employee data. By analyzing attributes such as Job Role, Experience, Job Satisfaction, Working Hours, Salary and Promotions,etc.
this project aims to identify employees at **risk of attrition** and uncover the primary factors contributing to employee turnover.

---
## 🗂️ Dataset
- Structured, tabular HR dataset
- File format : CSV
- Contains employee demographics, job-related and performance attributes
- Target Variable : **Attrition (Yes/No)**
- Problem Type : **Supervised learning - Binary Classification**

---
## 🔍 Data Cleaning & EDA(Exploratory Data Analysis)
- Handled missing values and inconsistent data
- Performed data preprocessing and feature understanding to know data distribution and relationships
- Visualized trends and patterns related to employee attrition
- Identified important features influencing employee turnover

---
## ⚙️ Methodology
- Data preprocessing and feature preparation
- Encoding and scaling of relevant features
- Exploratory Data Analysis to extract insights
- Supervised machine learning model training
- Handling class imbalance using resampling techniques
- Model evaluation using standard classification metrics  

---
## 🧠 Machine Learning Approach
Two modelling approaches were implemented and compared:
## 1️⃣ Without SMOTE
- Built classification models on the original dataset
- Evaluated performance using standard metrics
### 2️⃣ With SMOTE
- Applied SMOTE to address class imbalance
- Trained models on balanced data
- Compared results with non-SMOTE models

---
## 📈 Model Evaluation
Used metrics such as:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
- Compared model performance with and without SMOTE  
- Identified the most effective approach for predicting employee attrition

---
## 📌 Key Insights
- Identified key factors contributing to employee attrition  
- Observed the impact of class imbalance on model performance  
- Demonstrated improvement in prediction results using SMOTE

---
## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Jupyter Notebook

---
## 📂 Project Structure
'''
Employee-Attrition-Analysis/
│
├──Employee_Attrition_Cleaned.csv
├── DataCleaning & EDA.ipynb
├── MLModel(NoSMOTE).ipynb
├── ML_Model(SMOTE).ipynb
├── requirements.txt
│
└── README.md
