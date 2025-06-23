# Titanic Dataset - Data Cleaning & Preprocessing

## 🎯 Objective
The goal is to clean and preprocess the Titanic dataset for use in machine learning models.

## 📊 Dataset
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

## 🧪 Steps Performed
1. Loaded the dataset and explored it using Pandas.
2. Handled missing values:
   - Imputed 'Age' with median
   - Filled 'Embarked' with mode
   - Dropped 'Cabin' due to excessive nulls
3. Encoded categorical variables:
   - Label encoded 'Sex'
   - One-hot encoded 'Embarked'
4. Normalized 'Age' and 'Fare' using StandardScaler
5. Detected and removed outliers in 'Fare' and 'Age' using IQR
6. Saved cleaned dataset as `titanic_cleaned.csv`

## 🧰 Tools Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Files
- `titanic_data_cleaning.ipynb` – Notebook containing all code
- `titanic_cleaned.csv` – Output cleaned dataset
- `README.md` – This file
- `requirements.txt` – List of dependencies

## ✅ Submission
This repository was submitted as part of Internship Task 1.
