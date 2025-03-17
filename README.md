# Loan_Status_Prediction-Python-Project

# 📌 Project Overview

This project aims to predict whether a loan applicant will get loan approval based on certain features. The dataset contains information about applicants such as income, loan amount, credit history, and other factors. Various machine learning models are implemented, and the dataset is balanced using oversampling techniques to improve prediction accuracy.

# 🚀 Technologies Used

Python

Google Colab

Pandas, NumPy

Scikit-learn

Imbalanced-learn (for handling class imbalance)

Matplotlib, Seaborn (for visualization)

# 📊 Dataset Information

The dataset includes the following features:

ApplicantIncome: Income of the applicant

CoapplicantIncome: Income of the co-applicant

LoanAmount: Loan amount applied for

Loan_Amount_Term: Term of the loan in months

Credit_History: Credit history of the applicant (1 = Good, 0 = Bad)

Property_Area: Urban, Semi-Urban, or Rural

Loan_Status: Target variable (1 = Approved, 0 = Not Approved)

# 🔍 Data Preprocessing

Handling missing values

Encoding categorical and numerical variables

Feature scaling

Handling Imbalanced Data using RandomOverSampler

Splitting the data


# 🏆 Machine Learning Models Implemented

Several models were trained and evaluated using a classification report:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors (KNN)

# Best Performing Model: Random Forest

After balancing the dataset, Random Forest achieved 88% accuracy, making it the best model for this problem.

# 📌 Key Takeaways

✅ Handling imbalanced data significantly improves model performance.
✅ Decision Tree and Random Forest performed better on balanced data.
✅ Logistic Regression worked better on the original dataset but dropped in performance after balancing.
✅ Random Forest is the most reliable model for loan prediction.
