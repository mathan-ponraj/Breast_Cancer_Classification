# Breast Cancer Classification using Logistic Regression

## Project Overview
This project is a **learning-focused machine learning classification task** where I used Logistic Regression to classify breast tumors as **benign or malignant** based on diagnostic features.

The goal of the project was to understand the **end-to-end workflow of a supervised learning problem**, including data preparation, model training, and evaluation.

---

## Problem Statement
Given diagnostic measurements extracted from breast tumor images, the task is to build a model that can classify tumors into two categories:
- Benign
- Malignant

---

## What I Worked On

- Loaded and explored a real-world medical dataset from `scikit-learn`
- Converted the data into a Pandas DataFrame for analysis
- Performed basic exploratory data analysis (EDA)
- Checked for missing values and class balance
- Split the dataset into training and testing sets (80/20)
- Trained a **Logistic Regression** model
- Evaluated model performance using accuracy

---

## Dataset Information
- Dataset: Breast Cancer Wisconsin (Diagnostic)
- Features: 30 numerical diagnostic features
- Target: Binary classification (benign / malignant)

---

## Model Performance
- **Training Accuracy:** ~94%
- **Test Accuracy:** ~93%

The results showed that the model generalized reasonably well, with no major performance drop between training and testing data.

---

## Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## Key Learnings
- How to prepare and explore structured datasets
- How Logistic Regression works for binary classification
- Importance of train-test split for model evaluation
- Interpreting accuracy results and model performance
- Building a simple prediction workflow for new inputs

---

## Future Improvements
- Try feature scaling and regularization
- Experiment with other classification algorithms
- Evaluate performance using additional metrics such as precision and recall
