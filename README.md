# 🌸 Multi-Class Classification on the Iris Dataset

This project demonstrates a basic multi-class classification problem using the famous Iris dataset. The task is to classify iris flowers into one of three species based on sepal and petal measurements.

---

## 📊 Dataset

The **Iris dataset** consists of 150 samples with 4 features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The target labels are:
- `0`: Setosa
- `1`: Versicolor
- `2`: Virginica

![Iris Feature Dimensions](iris_dim.png)

---

## 🛠️ Tech Stack with Logos

| Tool/Library | Logo |
|--------------|------|
| Python       | ![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| Pandas       | ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) |
| NumPy        | ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) |
| Matplotlib   | ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white) |
| Seaborn      | ![Seaborn](https://img.shields.io/badge/-Seaborn-0D3A4C?style=for-the-badge&logo=python&logoColor=white) |
| Scikit-learn | ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) |

---

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report, accuracy_score
