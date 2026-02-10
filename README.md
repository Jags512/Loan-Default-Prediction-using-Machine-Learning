

# Loan Default Prediction using Machine Learning


kaggle link:https://www.kaggle.com/code/jagrutiyuvrajdhangar/loan-prediction/edit/run/296885137
## 📌 Project Overview
This project predicts whether a customer will **default on a loan** using historical loan and customer data.  
It is a **binary classification problem**, where the target variable indicates **Default (1) or No Default (0)**.

The project demonstrates an end-to-end machine learning workflow including:
- Data preprocessing
- Feature selection
- Model training
- Model evaluation
- Cross-validation

---

## 📂 Dataset
The dataset is sourced from **Kaggle**:

🔗 Kaggle Dataset Link:  
https://www.kaggle.com/datasets/XXXXXXXX/loan-default-dataset  
*(Replace this link with your actual Kaggle dataset URL)*

---

## 🧠 Problem Statement
Financial institutions face significant risk due to loan defaults.  
The goal of this project is to build a machine learning model that can **accurately predict loan default**, helping reduce financial loss.

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional for visualization)
- Jupyter Notebook

---

## ⚙️ Machine Learning Models
- Logistic Regression (Primary Model)
- Optional: Decision Tree, Random Forest

---

## 📊 Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- K-Fold / Stratified K-Fold Cross-Validation

---

## 🔁 Cross-Validation
Stratified K-Fold Cross-Validation is used to handle class imbalance and ensure consistent class distribution across folds.

---

## 📈 Results
- Achieved stable performance across folds
- ROC-AUC used as the primary evaluation metric due to class imbalance

---



## 🚀 How to Run the Project
1. Clone the repository  
2. Install required libraries  
   ```bash
   pip install -r requirements.txt

Conclusion

This project shows how machine learning can be applied to real-world financial risk problems.
Logistic Regression provides a strong baseline, and performance can be further improved using ensemble models.
