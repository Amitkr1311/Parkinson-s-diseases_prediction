# Parkinson's Disease Prediction Using Machine Learning

## Overview
This project predicts the likelihood of Parkinson's disease in patients based on biomedical voice measurements.  
It leverages Machine Learning techniques to assist in early detection, which is critical for timely treatment.

---

## Dataset
- **Source:** UCI Machine Learning Repository - Parkinson’s Disease Dataset
- Contains biomedical voice measurements from healthy and Parkinson's-affected individuals.
- Features: 22 attributes including vocal fundamental frequency, amplitude variation, and noise-to-harmonics ratio.

---

## Project Workflow
### 1. Exploratory Data Analysis (EDA)
- Visualized data distribution using Matplotlib, Seaborn, and Plotly.
- Identified patterns and correlations between features and disease labels.

### 2. Data Preprocessing
- Handled missing values and outliers.
- Performed feature scaling and normalization.
- Addressed class imbalance using **SMOTE** from imbalanced-learn.

### 3. Model Training & Evaluation
- Applied multiple ML models: Logistic Regression, Random Forest, Gradient Boosting, and Ensemble methods.
- Compared performance using Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics.
- Achieved **92% accuracy** on test data.
