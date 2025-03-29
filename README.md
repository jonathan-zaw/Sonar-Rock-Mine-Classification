# Sonar-Rock-Mine-Classification
A machine learning project using Logistic Regression to classify sonar signals as either rocks or mines.


## 📂 Dataset
- **Source**: Sonar dataset (CSV format)
- **Features**: 60 numerical values representing sonar signals
- **Labels**: 'M' (Mine) and 'R' (Rock)

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib

## 🔍 Exploratory Data Analysis
- Checked dataset structure
- Examined class distribution
- Analyzed feature distributions

## 📊 Model Training & Evaluation
- Used **Logistic Regression**
- Tuned hyperparameters using **GridSearchCV**
- Evaluated model performance with:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## 🚀 Prediction Example
The model predicts whether a sonar signal corresponds to a rock or a mine.

## 📌 Results
| Metric         | Value  |
|---------------|--------|
| Train Accuracy | 88.23% |
| Test Accuracy  | 76.19% |
| Precision (M)  | 75%    |
| Recall (M)     | 82%    |
| F1-score (M)   | 78%    |
