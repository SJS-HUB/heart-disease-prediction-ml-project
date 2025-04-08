# 🫀 Heart Disease Prediction – Machine Learning Project

This repository contains an end-to-end supervised machine learning project that predicts the presence of heart disease based on various clinical attributes. The goal is to build a **deployable and interpretable** model that can serve as a foundation for real-world medical risk assessment systems.

---

## 📊 Problem Statement

Cardiovascular diseases are one of the leading causes of death worldwide. Early prediction and detection can significantly improve treatment and prevention. This project aims to develop a **classification model** that predicts whether a patient is likely to develop heart disease based on specific features.

---

## 📁 Dataset Details

- **Source:** [UCI Machine Learning Repository] attached in the repository
- **Type:** Classification
- **Instances:** 303
- **Features Used:**  
  `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure),  
  `chol` (cholesterol), `fbs` (fasting blood sugar), `restecg`,  
  `thalach` (maximum heart rate), `exang` (exercise-induced angina),  
  `oldpeak`, `slope`, `ca` (number of major vessels), `thal` (thalassemia)

---

## 🧠 ML Concepts Applied

| Stage                  | Techniques Used                                               |
|------------------------|---------------------------------------------------------------|
| Data Cleaning          | Handling nulls, formatting, label encoding                    |
| EDA                    | Pairplots, heatmaps, distribution plots using Seaborn         |
| Feature Engineering    | One-Hot Encoding, normalization                               |
| Model Selection        | Logistic Regression                                           |
| Model Evaluation       | Accuracy, Confusion Matrix, Precision, Recall, F1-Score       |
| Deployment Ready       | Streamlit for UI + `joblib` model serialization               |

---

## 🧪 Model Used: Logistic Regression

Logistic Regression was selected for its:
- High interpretability in healthcare
- Good performance on binary classification
- Probabilistic output (helpful for threshold tuning)

---

## 📈 Model Performance

| Metric           | Value |
|------------------|-------|
| Accuracy         | 88%   |


classification Report
              precision    recall  f1-score   support

           0       0.89      0.86      0.88        29
           1       0.88      0.91      0.89        32

    accuracy                           0.89        61
   macro avg       0.89      0.88      0.88        61
weighted avg       0.89      0.89      0.89        61

This project successfully demonstrates the application of machine learning techniques to predict the likelihood of heart disease based on patient attributes. 
This model performed the best with an accuracy of 88%. 
This indicates that the model can assist healthcare professionals in early screening of high-risk individuals, potentially improving patient outcomes through timely interventions. 
