# Student Academic Performance Predictor

A machine learning project designed to identify students who may need early academic advising and intervention by predicting their performance risk factors based on structured educational data.

## 📊 Project Overview

In educational institutions, early identification of struggling students is critical for retention and academic success. This project utilizes a structured dataset to train classification models that accurately predict student performance and uncover the primary drivers behind academic risk.
- **Dataset Scale:** 2,393 rows, 15 columns, and 35,895 total data points.
- **Core Objective:** Early risk detection and automated identification of key behavioral/academic predictors.
- **Dataset Source:** [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset)

## 🛠️ Tech Stack & Libraries

- **Language:** Python
- **Data Processing & ML:** Scikit-Learn, Pandas, NumPy
- **Data Balancing:** SMOTE (Synthetic Minority Over-sampling Technique)
- **Model Evaluation:** Random Forest Classifier, F1-Score, Accuracy Metrics

## 📈 Key Methodology & Results

- **Data Preprocessing & Balancing:** Addressed severe class imbalance within the educational dataset using SMOTE combined with rigorous feature preprocessing in Python (Scikit-Learn) to ensure robust training.
- **Model Training:** Trained and evaluated a Random Forest classifier, achieving a high performance of 91.4% accuracy and a 0.94 F1-score.
- **Feature Importance (Explainable AI):** Extracted granular feature importances from the model to pinpoint exact risk drivers:
  - **Absences:** Accounted for 67% of the predictive risk weight (the top predictor of academic struggle).
  - **Study Hours:** Accounted for 8% of the predictive weight.

## 🚀 How to Run the Code

Clone the repository:
```bash
git clone [https://github.com/Mohammed-Filfil/Student-Academic-Performance-Predictor](https://github.com/Mohammed-Filfil/Student-Academic-Performance-Predictor)
