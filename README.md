
---

# 🧠 Insurance Cost Prediction using Regression Models

## 📌 Project Overview

This project explores regression algorithms in machine learning and applies them to a real-world dataset to predict medical insurance expenses.

The goal is to understand how regression models work in practice by performing **data exploration, preprocessing, model training, and evaluation**.

Two regression models were implemented and compared to analyze their performance in predicting insurance costs.

---

# 📊 Dataset

The dataset used in this project is the **Medical Cost Personal Dataset**.

It contains demographic and health-related information about individuals along with their medical insurance charges.

### Features

* age
* sex
* bmi
* children
* smoker
* region

### Target Variable

* **expenses** (insurance charges)

The objective of this project is to **predict insurance costs based on these features**.

---

# 🔍 Exploratory Data Analysis (EDA)

Before training the models, the dataset was explored to understand its structure and relationships between variables.

### Steps performed

* Dataset inspection
* Checking data types
* Identifying missing values
* Detecting duplicate rows
* Statistical summary of data

### Visualizations used

* Histograms (feature distributions)
* Count plots for categorical variables
* Scatter plots between features and target
* Correlation heatmap
* Boxplots for categorical feature impact

These visualizations help reveal patterns such as the strong effect of **smoking status on insurance expenses**.

---

# 🧹 Data Preprocessing

Several preprocessing steps were applied to prepare the dataset for modeling.

### Cleaning

* Removed duplicate rows

### Feature Engineering

* Separated **features (X)** and **target (y)**

### Encoding

Categorical variables were encoded using:

* **OneHotEncoder**

### Feature Scaling

Numerical features were standardized using:

* **StandardScaler**

### Train-Test Split

The dataset was split into:

* **80% training data**
* **20% testing data**

---

# 🤖 Models Implemented

Two regression models were implemented using **Scikit-learn Pipelines**.

## 1️⃣ Linear Regression

A baseline model that assumes a linear relationship between the features and the target variable.

The model learns the best-fitting line that minimizes prediction error.

---

## 2️⃣ Polynomial Regression

Polynomial regression extends linear regression by introducing polynomial features.

This allows the model to capture **non-linear relationships** in the dataset.

Polynomial degree used in this project:

```
degree = 2
```

---

# 📏 Model Evaluation

The models were evaluated using multiple regression metrics:

* **MAE** — Mean Absolute Error
* **MSE** — Mean Squared Error
* **RMSE** — Root Mean Squared Error
* **R² Score**

These metrics measure how well the model predictions match the actual insurance expenses.

---

# 📈 Model Comparison

Both models were compared based on their performance metrics.

Visual comparisons were created using:

* Error metrics bar chart
* R² score comparison chart
* Actual vs Predicted scatter plots

This helps visually analyze which model performs better.

---

# 🏆 Best Model Selection

After evaluating the models, the best model was selected based on the **highest R² Score**.

The results show how different regression techniques impact prediction performance.

---

# 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


---

# 🎯 Conclusion

This project demonstrates the full workflow of solving a **machine learning regression problem**, including:

* Data exploration
* Data preprocessing
* Model training
* Performance evaluation
* Model comparison

The results highlight how regression models can effectively predict **insurance costs based on personal and health-related factors**.

---
