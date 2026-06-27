# Minor-Project-1
# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Project Overview

Loan approval is one of the most important decisions made by banks and financial institutions. Traditionally, evaluating loan applications is a time-consuming process that involves analyzing an applicant's financial and personal information. This project aims to automate the loan approval process using Supervised Machine Learning techniques.

The developed model predicts whether a loan application is likely to be **Approved** or **Rejected** based on applicant information such as income, education, employment status, credit history, and property area.

---

# 🎯 Problem Statement

Develop a supervised machine learning model to predict whether a loan application should be approved based on applicant details. The objective is to help financial institutions make faster and more accurate loan approval decisions.

---

# 📂 Dataset

**Dataset Name:** Loan Prediction Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/ninzaami/loan-predication

### Dataset Information

- Total Records: 614
- Features: 13
- Target Variable: Loan_Status

### Features

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

# 🤖 Machine Learning Algorithms

The following supervised learning algorithms were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

# 🔄 Project Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Feature Importance Analysis
12. Model Saving

---

# 📊 Exploratory Data Analysis

The following visualizations were created:

- Loan Approval Distribution
- Gender vs Loan Status
- Education vs Loan Status
- Married vs Loan Status
- Property Area Distribution
- Credit History vs Loan Status
- Applicant Income Distribution
- Loan Amount Distribution
- Correlation Heatmap
- Feature Importance Plot

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 🏆 Model Comparison

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 0.788618 |
| Random Forest | 0.756098 |
| SVM | 0.788618 |



---



---

# 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Loan-Approval-Prediction.git
```

### Navigate to the Project Folder

```bash
cd Loan-Approval-Prediction
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebook/Loan_Approval_Prediction.ipynb
```

Run all cells sequentially.

---

# 📌 Results

The trained models were compared using multiple evaluation metrics. Among all the implemented algorithms, the best-performing model can be selected based on its Accuracy, Precision, Recall, and F1 Score. Feature importance analysis also helps identify the factors that most influence loan approval decisions.

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- LightGBM Implementation
- Flask/Streamlit Web Application
- Deployment on Cloud Platforms

---

# 👨‍💻 Author

**Rishu Pandey**

B.Tech Computer Science & Engineering

KIET Group of Institutions

---

# 📜 License

This project is developed for academic purposes as part of the Minor Project submission.
