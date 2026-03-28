# Breast Cancer Diagnostic Classification

## Project Overview
This project focuses on a medical classification task: identifying whether a breast tumor is benign or malignant. I built this to demonstrate how machine learning can assist in clinical diagnostics by analyzing cell features from tumor images.

## The Problem
In healthcare, early and accurate diagnosis is critical. The goal here is to use 30 different measurements—like texture, radius, and area—to categorize tumors into two clear groups:
1. Benign (Non-cancerous)
2. Malignant (Cancerous)

## My Technical Workflow

1. Data Setup: I used the Wisconsin Breast Cancer dataset from Scikit-learn and converted it into a structured format using Pandas for better analysis.
2. Exploratory Analysis: I checked the dataset for missing values and made sure the classes were balanced to avoid biased results.
3. Model Training: I split the data into 80% for training and 20% for testing. I chose Logistic Regression because it is a reliable and fast algorithm for binary classification.
4. Testing: I ran the model on unseen data to see how it performs in a real-world scenario.

## Results and Performance
The model showed strong results and generalized well to new data:
- Training Accuracy: Approximately 94%
- Test Accuracy: Approximately 93%

Because the difference between training and testing accuracy is very small, it proves the model is stable and not overfitting.

## Tools Used
- Programming: Python
- Data Libraries: Pandas and NumPy
- Machine Learning: Scikit-learn
- Analysis Environment: Jupyter Notebook

## Future Goals
To make this system even more accurate for medical use, I plan to:
- Use Feature Scaling to normalize the data.
- Focus on Recall scores to ensure no malignant cases are missed.
- Compare these results with other models like Random Forest or XGBoost.

---
Developed by Mathan Ponraj
CSE Graduate | Data Science and Analytics
[LinkedIn Profile](https://www.linkedin.com)
