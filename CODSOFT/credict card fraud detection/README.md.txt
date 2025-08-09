# Credit Card Fraud Detection 🕵️‍♂️💳

This project applies machine learning techniques to detect fraudulent credit card transactions using a real-world dataset. The original dataset is highly imbalanced, so special care has been taken to address class imbalance using SMOTE.

## 🔍 Dataset
The dataset consists of 284,807 transactions, each with 30 features (28 anonymized PCA components, plus `Amount` and `Time`). The `Class` column indicates whether a transaction is fraudulent (`1`) or legitimate (`0`).

## 🧠 Models Used
Two classification models were trained and evaluated:

- **Logistic Regression**
  - Accuracy: 97%
  - F1-score (Fraud Class): 0.11
- **Random Forest Classifier**
  - Accuracy: 100%
  - F1-score (Fraud Class): 0.84

## ⚙️ Workflow
1. Data Preprocessing
   - Normalization of `Time` and `Amount`
   - Feature-target split
   - Handling class imbalance with SMOTE
2. Model Training
   - Logistic Regression
   - Random Forest
3. Evaluation
   - Confusion Matrix
   - Classification Report

## 📊 Results
The Random Forest model outperforms Logistic Regression, especially in detecting fraudulent transactions. With high precision and recall, it provides a reliable solution for fraud detection systems.

## 🚀 Technologies
- Python 🐍
- pandas, numpy
- scikit-learn
- imbalanced-learn
- Google Colab

## 📁 File
- `credit card.ipynb`: The main notebook with data loading, preprocessing, model training, and evaluation.

## 📌 Notes
- Due to class imbalance, evaluating with metrics like recall and F1-score is more important than overall accuracy.
- SMOTE helped in balancing the training set to improve minority class detection.

## 🧮 Author
Athulya – aspiring Data Analyst passionate about statistical modeling and predictive analytics.


