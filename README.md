# 📊 Loan Approval Prediction using Machine Learning

## 📌 Overview

Loan approvals are a crucial part of banking, allowing individuals to manage education, purchase homes, cars, or other essentials. But manually evaluating applications based on multiple criteria is time-consuming.

This project uses **machine learning algorithms** to assist banks by predicting whether a loan application should be approved based on various features like **Marital Status**, **Education**, **Applicant Income**, **Credit History**, and more.

---

## 📁 Dataset

📥 **[Download Dataset](#)**  
The dataset contains 13 features:

| Feature              | Description                                                        |
|----------------------|--------------------------------------------------------------------|
| `Loan_ID`            | Unique loan identifier (dropped during preprocessing)             |
| `Gender`             | Gender of applicant: Male/Female                                  |
| `Married`            | Marital status: Yes/No                                            |
| `Dependents`         | Number of dependents                                               |
| `Education`          | Graduate/Not Graduate                                             |
| `Self_Employed`      | Employment type: Yes/No                                           |
| `ApplicantIncome`    | Income of applicant                                                |
| `CoapplicantIncome`  | Income of co-applicant                                             |
| `LoanAmount`         | Loan amount in thousands                                           |
| `Loan_Amount_Term`   | Loan term in months                                                |
| `Credit_History`     | Record of credit repayment                                         |
| `Property_Area`      | Area: Rural, Urban, Semi-urban                                     |
| `Loan_Status`        | Target variable: Approved (Y) or Not (N)                           |

---

##📦 Dependencies

Install required libraries using:
pip install pandas numpy matplotlib seaborn scikit-learn


##🧠 Machine Learning Pipeline
📊 Data Preprocessing
Dropped irrelevant features (Loan_ID)

Handled missing values

Visualized categorical features using bar plots

Encoded categorical values using LabelEncoder

Visualized correlations using Heatmap and Catplot


##📌 Conclusion
Random Forest performed the best with ~82.5% accuracy on unseen data.

Logistic Regression gave a good balance between training and testing accuracy.

Credit_History, ApplicantIncome, and LoanAmount were highly influential in predicting outcomes.

