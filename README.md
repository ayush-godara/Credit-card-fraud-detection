# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques on highly imbalanced data.

## Dataset
- Credit Card Transactions Dataset (European cardholders)
- Fraud transactions account for less than 0.2% of total transactions
- Dataset source: Kaggle

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)

## Approach
- Performed data cleaning and preprocessing
- Handled class imbalance using SMOTE
- Trained models such as Logistic Regression and Random Forest
- Evaluated performance using Confusion Matrix, Precision, Recall, and ROC-AUC

## Results
- Achieved high recall for fraud detection
- Reduced false negatives, which is critical in real-world fraud scenarios

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
## Future Improvements
- Experiment with advanced models such as XGBoost or LightGBM to further improve fraud detection performance.
- Deploy the trained model using a simple Flask-based REST API for real-time transaction evaluation.
