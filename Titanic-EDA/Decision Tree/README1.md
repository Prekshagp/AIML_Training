# Task 5: Decision Trees and Random Forests - Heart Disease Prediction

## 🔍 Objective
The objective of this project is to explore and apply tree-based classification models such as Decision Tree and Random Forest to predict heart disease.

## 🧠 What You’ll Learn
- Decision Tree classifier training and visualization
- Random Forest ensemble modeling
- Overfitting analysis using tree depth
- Feature importance interpretation
- Evaluation with accuracy and cross-validation

## 📂 Dataset
**Heart Disease Dataset**
- Source: [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Features include age, cholesterol, blood pressure, etc.
- Target: `0` (No heart disease) / `1` (Heart disease)

## 🛠️ Tools Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, Matplotlib, Seaborn
- Graphviz (for tree visualization)

## 📊 Results
| Model             | Accuracy |
|------------------|----------|
| Decision Tree     | ~82%     |
| Random Forest     | ~89%     |
| Cross-Val (RF)    | ~84%     |

## 📁 Folder Structure
```
decision_tree_random_forest/
├── decision_tree_random_forest.ipynb
├── README.md
├── requirements.txt
├── interview_questions.pdf
└── dataset/
    └── heart.csv
```

## ✅ How to Run
1. Install dependencies using `pip install -r requirements.txt`
2. Launch `Jupyter Notebook` and open `decision_tree_random_forest.ipynb`
3. Run all cells step-by-step
