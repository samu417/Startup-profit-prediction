# Startup-profit-prediction

A Machine Learning project that predicts the profit of a startup based on its **R&D Spend**, **Administration Cost**, **Marketing Spend**, and **Region** using **Multiple Linear Regression**.

---

## 📌 Project Overview

Startup companies invest heavily in research, administration, and marketing. This project uses historical startup data to build a machine learning model that predicts the expected profit based on these investments.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, prediction, and performance evaluation.

---

## 🎯 Problem Statement

Develop a machine learning model that accurately predicts startup profit using financial investment data.

---

## 📂 Dataset Information

**Dataset:** 50 Startup Profit Dataset

### Features

| Feature | Description |
|---------|-------------|
| Region | Startup location |
| R&D Spend | Investment in Research & Development |
| Administration | Administrative expenses |
| Marketing Spend | Marketing expenses |
| Profit | Target variable |

**Number of Records:** 50

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. One-Hot Encoding of Region
5. Train-Test Split
6. Multiple Linear Regression Model
7. Prediction
8. Model Evaluation

---

## 📁 Project Structure

```
Startup-Profit-Prediction/
│
├── README.md
├── requirements.txt
├── Startup_Profit_Prediction.ipynb
├── 50StartupProfit.csv
│
└── images/
    ├── Flow Diagram.png
    ├── Startup Profit Trend Based on R&D Investment.png
    └── actual_vs_predicted profit.png
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/arpitaa1412/Startup-Profit-Prediction.git
```

Move into the project directory

```bash
cd Startup-Profit-Prediction
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook Startup_Profit_Prediction.ipynb
```

---

## 📈 Results

**Algorithm Used:** Multiple Linear Regression

**Model Performance**

- **R² Score:** **0.89**

The model explains approximately **89%** of the variation in startup profit, indicating strong predictive performance.

---

## 📷 Project Screenshots

### Workflow

![Workflow](images/Flow%20Diagram.png)

### Profit Trend

![Profit Trend](images/Startup%20Profit%20Trend%20Based%20on%20R%26D%20Investment.png)

### Actual vs Predicted Profit

![Actual vs Predicted Profit](images/actual_vs_predicted%20profit.png)

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
```

---

## 🚀 Future Improvements

- Increase dataset size for better generalization.
- Apply feature engineering techniques.
- Compare with advanced regression algorithms such as:
  - Random Forest Regressor
  - XGBoost Regressor
  - Decision Tree Regressor
- Deploy the model using Streamlit or Flask.
- Add an interactive user interface for predictions.

---

