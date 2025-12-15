# Decision Tree Classification – Loan Approval

This project uses a Decision Tree Classifier to predict loan default
based on customer and loan-related features.

## Dataset
- File: Loan_approval_data_2025.csv
- Target variable: loan_status
  - 0 = No Default
  - 1 = Default
- Rows with missing values are removed
- Categorical features are one-hot encoded

## Model
- Algorithm: Decision Tree Classifier
- Max Depth: 5
- Train-Test Split: 80% / 20%
- Stratified split on target variable

## Evaluation
- Accuracy
- Confusion Matrix
- Classification Report
- Feature Importance
- Decision Tree Visualization

## How to Run

1. Open the notebook file
2. Click **Open in Colab**
3. Click **Runtime → Run all**

Ensure `Loan_approval_data_2025.csv` is in the same folder.
