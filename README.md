# Breast Cancer Classification using Logistic Regression

## Case Study

### Problem
Early and accurate detection of breast cancer is critical for improving patient outcomes and supporting clinical decision-making.

### Context
This project applies supervised machine learning to classify breast tumors as **benign or malignant** using diagnostic features extracted from medical imaging data.

### Impact
- Built a binary classification model achieving **~93% accuracy on unseen test data**
- Demonstrated strong generalization with minimal overfitting
- Enabled fast, data-driven cancer diagnosis support

### Why It Matters
Accurate tumor classification helps clinicians prioritize treatment, reduce diagnostic errors, and improve patient survival rates.

---

## What I Did

- Built an end-to-end **binary classification pipeline**
- Loaded and analyzed a real-world medical dataset from `scikit-learn`
- Performed data validation, statistical analysis, and feature inspection
- Trained and evaluated a **Logistic Regression** model
- Implemented a prediction system for classifying new patient samples

---

## How I Did It (STAR Method)

### Situation
The dataset consisted of **30 numerical diagnostic features** derived from breast tumor images, with a binary target label.

### Task
Develop a reliable and interpretable machine learning model to classify tumors as benign or malignant.

### Action
- Loaded the Breast Cancer Wisconsin Diagnostic dataset
- Converted raw data into a structured Pandas DataFrame
- Performed exploratory data analysis (EDA) and statistical summaries
- Verified class distribution and checked for missing values
- Split data into training and testing sets (80/20)
- Trained a Logistic Regression classifier using scikit-learn
- Evaluated performance using accuracy metrics
- Built a prediction pipeline for individual patient inputs

### Result
- **Training Accuracy:** ~94.7%
- **Test Accuracy:** ~92.9%
- Model generalized well without significant performance drop
- Successfully classified unseen tumor samples

---

## Tech Stack

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Model:** Logistic Regression
- **Evaluation Metric:** Accuracy Score
- **Dataset:** Breast Cancer Wisconsin (Diagnostic)
- **Environment:** Jupyter Notebook

---

## Key Results / Business Impact

- Delivered a high-accuracy medical classification model
- Demonstrated effective use of logistic regression for healthcare data
- Built a reusable pipeline for real-time cancer prediction
- Established a strong baseline for future improvements (scaling, regularization, advanced classifiers)
