# 🎬 Movie Rating Prediction

This project predicts IMDb movie ratings using metadata such as genre, director, and actors. It is part of my CodSoft internship tasks.

## 📁 Files
- `movie.ipynb`: Jupyter notebook containing the full pipeline for data preprocessing, model training, and evaluation.
- `IMDb Movies India.csv`: Dataset used.

## 🔍 Workflow Overview

### ✅ Data Preprocessing
- Selected relevant features: `Genre`, `Director`, `Actor 1`, `Actor 2`, `Actor 3`
- Dropped rows with missing target (`Rating`)
- Handled missing values using `SimpleImputer`
- Encoded categorical features using `OneHotEncoder`

### 🧠 Model Training
- Algorithm: `RandomForestRegressor` with 100 estimators
- Train-test split: 80/20
- Pipeline used for preprocessing and modeling

### 📈 Evaluation
- **R² Score**: 0.21
- **RMSE**: 1.21

### 📌 Technologies Used
- Python, Pandas
- Scikit-learn (Pipeline, ColumnTransformer, RandomForestRegressor)

## ✅ Result
The model provides a baseline for predicting movie ratings based on metadata. Further improvements can be made by including more features or using advanced models.
