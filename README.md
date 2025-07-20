
## Project Overview

Breast cancer is one of the most common types of cancer affecting individuals worldwide. Early detection and classification can significantly improve treatment outcomes. This project leverages logistic regression to identify the nature of the tumour based on key features in the dataset.

## Workflow

The workflow is structured as follows:

- **Data Preprocessing**  
  Cleaned and prepared the dataset for modelling by handling missing values and selecting relevant features.

- **Train-Test Split**  
  Divided the dataset into training and testing sets using Scikit-learn's `train_test_split` function to ensure unbiased evaluation.

- **Model Building**  
  Built a logistic regression model using the Scikit-learn library. The model was trained on the training data and tuned for performance.

- **Evaluation**  
  Measured the model's effectiveness using the accuracy score. The final model achieved an accuracy of **94%**, indicating strong predictive performance.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

## Results

The logistic regression model performed well on the test data, accurately classifying most cases. The simplicity and interpretability of logistic regression make it a solid choice for binary classification tasks such as this.

## Conclusion

This project demonstrates the effectiveness of logistic regression in medical classification problems. With a straightforward approach and proper preprocessing, the model delivers high accuracy and can be a helpful baseline for more complex models in future research.
