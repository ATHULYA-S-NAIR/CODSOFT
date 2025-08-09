# 🚢 Titanic Survival Prediction

This project is part of my CodSoft internship. It focuses on predicting whether a passenger survived the Titanic disaster using machine learning.

## 📁 Files
- `titanic_survival.ipynb`: Main notebook with code for data cleaning, model training, and evaluation.
- `Titanic-Dataset.csv`: Dataset used (upload separately if needed).

## 🔍 Workflow Overview

### ✅ Data Preprocessing
- Dropped: `PassengerId`, `Name`, `Ticket`, `Cabin`
- Filled missing values in `Age` (median) and `Embarked` (mode)
- Encoded categorical features using `LabelEncoder`

### 📊 Exploratory Analysis
- Visualized survival counts by gender using Seaborn

### 🧠 Model Training
- Algorithm: `RandomForestClassifier` (100 trees)
- Train-test split: 80/20

### 📈 Evaluation
- Accuracy: **82.1%**
- Confusion Matrix:
- Classification Report:
- Precision: 0.83 (non-survivors), 0.81 (survivors)
- Recall: 0.88 (non-survivors), 0.74 (survivors)

### 🌟 Feature Importance
- Most influential: `Sex`, `Fare`, `Age`, `Pclass`

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## ✅ Result
The model achieves strong performance and highlights key survival factors on the Titanic.
