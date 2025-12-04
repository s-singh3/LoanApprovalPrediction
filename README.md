# Loan Approval Prediction

A machine learning project to predict loan approval status using multiple classification algorithms.

## Overview

This project builds and compares ML models to automate loan approval decisions based on applicant demographics, financial information, and credit history.

## Dataset

The dataset includes features like Gender, Marital Status, Income, Loan Amount, Credit History, and Property Area, with Loan_Status as the target variable.

## Technologies

- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook LoanApprovalPrediction.ipynb
```

Run all cells to load data, preprocess, train models (Random Forest, KNN, SVC, Logistic Regression), and evaluate performance.

## Key Findings

- Credit History is the strongest predictor of loan approval
- All models achieved competitive accuracy with good generalization
- 60-40 train-test split was used for evaluation

## Future Improvements

- Feature engineering (debt-to-income ratio)
- Hyperparameter tuning and cross-validation
- Handle class imbalance with SMOTE

## Author

Your Name - [GitHub](https://github.com/s-singh3)

---

*Educational project - real-world systems require additional compliance and fairness considerations.*
