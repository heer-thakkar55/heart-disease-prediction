# Cardiac Arrest Prediction Using Machine Learning

## Project Overview

Heart disease is one of the leading causes of death worldwide. This project applies machine learning techniques to predict whether a patient is likely to have heart disease based on medical attributes.

The project demonstrates a complete data science pipeline including data preprocessing, exploratory data analysis, feature engineering, model training, and model evaluation.

---

## Dataset

Dataset used: **Heart Disease UCI Dataset**

Total Records: **920**

Features include:

- Age
- Sex
- Chest Pain Type
- Cholesterol
- Resting Blood Pressure
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Thalassemia
- Number of Major Vessels

Target variable: num → presence of heart disease

## Project Workflow

The project follows a standard machine learning pipeline:

1. Data Loading
2. Data Cleaning
3. Handling Missing Values
4. Encoding Categorical Variables
5. Exploratory Data Analysis
6. Feature Scaling
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison

---

## Models Implemented

The following machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy |
|------|------|
| Logistic Regression | 0.80 |
| Decision Tree | 0.79 |
| KNN | 0.81 |
| Random Forest | 0.87 |
| XGBoost | **0.875** |

Random Forest and XGBoost achieved the highest performance.

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Feature Importance

Feature importance analysis revealed that the following attributes play a significant role in predicting heart disease:

- Chest Pain Type
- Maximum Heart Rate
- ST Depression
- Age
- Cholesterol

---

## Key Insights

- Ensemble models significantly outperform simpler models.
- XGBoost achieved the highest accuracy.
- Several medical features strongly influence heart disease risk.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## Project Structure

heart-disease-prediction │ ├── Documentation.pdf ├── Heart_Disease_Prediction.ipynb ├── README.md 

## Conclusion

This project demonstrates how machine learning can assist in predicting heart disease risk using patient medical data. While these models cannot replace clinical diagnosis, they provide valuable insights that can support healthcare professionals in identifying high-risk patients.
