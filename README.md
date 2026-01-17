# Task 4: Credit Risk Prediction using Decision Tree

##  Overview
This repository contains the solution for **Task 4: Credit Risk Prediction**, completed as part of an **AI & Data Science Internship**.  
The goal of this task is to build a machine learning model that predicts whether a loan applicant is likely to **pay back a loan or default**, using historical loan application data.

---

##  Objective
The objective of this task is to:
- Predict whether a loan applicant will **pay back the loan (1)** or **default (0)**
- Perform proper **data cleaning, exploratory data analysis (EDA), and model training**
- Evaluate the model using **accuracy, confusion matrix, and classification metrics**

---

##  Dataset Description
- **Dataset Name:** Loan Prediction Dataset  
- **Source:** Kaggle  
- **Number of Records:** ~20,000  
- **Target Variable:** `loan_paid_back`

### Key Features
- **Demographic Information:** gender, marital_status, education_level  
- **Financial Information:** annual_income, monthly_income, credit_score  
- **Loan Details:** loan_amount, interest_rate, loan_term, installment  
- **Credit History:** delinquency_history, public_records

## Target Variable:
- loan_paid_back (0 = default, 1 = paid back)

The dataset includes both **numerical and categorical variables**, with some missing values.

---

##  Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – Data preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Model training and evaluation
- **Google Colab / Jupyter Notebook**

---

##  Approach
The following step-by-step approach was used to complete this task:

1. **Data Loading**  
   - Loaded the loan dataset using Pandas.
   - Inspected data structure, data types, and size.

2. **Dataset Understanding**  
   - Identified numerical and categorical features.
   - Analyzed the target variable (`loan_paid_back`).

3. **Data Cleaning & Preparation**  
   - Handled missing values:
     - Numerical features filled using **mean**
     - Categorical features filled using **mode**
   - Converted categorical variables into numerical format using **one-hot encoding**.

4. **Exploratory Data Analysis (EDA)**  
   - Visualized loan amount distribution.
   - Analyzed relationships between income, education level, and loan repayment.
   - Identified important patterns influencing credit risk.

5. **Model Training**  
   - Selected **Decision Tree Classifier** due to interpretability.
   - Split the dataset into **training (80%)** and **testing (20%)** sets.
   - Trained the model with controlled depth to avoid overfitting.

6. **Model Evaluation**  
   - Evaluated model performance using:
     - Accuracy score
     - Confusion matrix
     - Classification report (Precision, Recall, F1-score)

---

##  Exploratory Data Analysis (EDA)
EDA was performed to understand data behavior and feature relationships:
- Distribution of **loan amounts**
- Relationship between **annual income and loan repayment**
- Impact of **education level** on repayment behavior

---

##  Model Evaluation & Results
- The Decision Tree model achieved **good accuracy**
- Confusion matrix showed balanced predictions for both classes
- Classification report confirmed effective performance

---

##  Key Insights
- Higher **credit scores** significantly increase repayment likelihood
- Applicants with **higher income** are less likely to default
- Education level and employment stability influence credit risk
- Decision Trees are effective and interpretable for credit prediction

---

##  Conclusion
This task successfully demonstrates a complete **credit risk prediction pipeline**, including:
- Data cleaning and preparation
- Exploratory data analysis
- Decision Tree model training
- Performance evaluation using standard classification metrics  

The results show that machine learning can effectively support **credit risk assessment** in financial institutions.

---


