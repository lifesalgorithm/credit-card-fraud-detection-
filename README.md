Credit Card Fraud Detection
This project uses machine learning to detect fraudulent credit card transactions. It demonstrates how to handle imbalanced datasets, perform data preprocessing, and apply classification models to real-world fraud detection problems.

Project Overview
Credit card fraud is a significant financial issue worldwide. This project analyzes a dataset of European card transactions to build a predictive model that can classify whether a transaction is fraudulent or not.

Key highlights:
Data preprocessing and exploration
Handling imbalanced data with under-sampling / over-sampling
Training and evaluating classification models (Logistic Regression, Random Forest, etc.)
Performance metrics: accuracy, precision, recall, F1-score, ROC-AUC

Dataset
Source: Kaggle Credit Card Fraud Detection Dataset
Records: 284,807 transactions
Fraudulent transactions: 492 (0.17%)
Note: Due to confidentiality, features are PCA-transformed except for Time and Amount.

Model Performance
The notebook includes:
Confusion matrices
Precision and recall scores
ROC and AUC curves
Insights on how different models perform with imbalanced classes


Results & Future Work
This project highlights the challenges of imbalanced classification and how models like Random Forest can handle them effectively.
Future improvements:
Try SMOTE or other advanced resampling techniques
Experiment with ensemble methods and hyperparameter tuning
Deploy the model as an API for real-time fraud detection

# credit-card-fraud-detection-
