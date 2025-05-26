# titanic-task1
# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This repository contains the code and outputs for **Task 1** of the Elevate Labs AI & ML Internship. The task focuses on **data cleaning and preprocessing** using the famous Titanic dataset.

---

## 📌 Task Objective

> Clean and prepare raw Titanic data for Machine Learning models through data exploration, handling missing values, encoding categorical variables, and feature scaling.

---

## 📂 Files in This Repo

| File                  | Description                                 |
|-----------------------|---------------------------------------------|
| `titanic.csv`         | Raw dataset (downloaded from Kaggle)        |
| `titanic_cleaned.csv` | Cleaned version after preprocessing         |
| `titanic_preprocessing.ipynb` | Jupyter Notebook with full code and outputs |
| `README.md`           | Project overview and explanation            |

---

## 🧪 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 🔍 Step-by-Step Process

### ✅ 1. Data Exploration

- Displayed basic dataset information (`.info()`, `.describe()`)
- Counted missing values

### ✅ 2. Handling Missing Values

- Filled `Age` using **median**
- Filled `Embarked` using **mode**
- Dropped `Cabin` due to too many nulls

### ✅ 3. Encoding Categorical Variables

- Label encoded `Sex`
- One-hot encoded `Embarked`

### ✅ 4. Feature Scaling

- Standardized `Age` and `Fare` using `StandardScaler`

### ✅ 5. Outlier Detection & Removal

- Visualized outliers with **boxplots**
- Removed outliers from `Fare` using the **IQR method**

---

## 📊 Result

- Cleaned dataset with no missing values
- Encoded and scaled features
- Ready for model training

---

## 📎 Dataset Source

- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## ✅ Submission

Submitted GitHub repo as part of **Task 1: Data Cleaning & Preprocessing** for Elevate Labs Internship.

