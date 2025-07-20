# Data Description

This folder contains the logic used to load and prepare the breast cancer dataset for model development.

## Source

The dataset is sourced directly from Scikit-learn’s built-in datasets module. It includes numerical features related to cell nuclei characteristics, used to classify tumours as either benign or malignant.

## Dataset Loading and Preparation

The following code is used to load and convert the dataset into a Pandas DataFrame:

```python
import pandas as pd
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer()
df = pd.DataFrame(data.data, columns=data.feature_names)
```
