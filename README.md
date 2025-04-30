# 💳 Credit Card Fraud Detection

This project uses machine learning to detect fraudulent credit card transactions using the Kaggle dataset from [mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## 📦 Dataset

The dataset is can be downloaded dynamically using the [`kagglehub`](https://github.com/kagglehub/kagglehub) library.

## 📊 Dataset Description

- Contains **284,807** transactions made by European cardholders in September 2013.
- Only **492 are frauds** (0.172%).
- Features are anonymized via PCA; only `Time`, `Amount`, and `Class` are not transformed.
- `Class` is the target variable (1 = fraud, 0 = normal).

## 🔧 Future Work

- Build a logistic regression and ensemble model pipeline.
- Handle class imbalance using under-sampling/SMOTE.
- Evaluate using precision, recall, F1-score, and ROC-AUC.
- Deploy model via Flask or Streamlit (optional).

## 📘 License

This project is for educational and research purposes only.
