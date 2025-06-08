# Online Payment Fraud Detection

This project aims to build a robust machine learning solution to detect fraudulent online payment transactions for Blossom Bank (BB PLC), a multinational financial services group.

## Project Overview

- **Goal:** Predict and flag fraudulent transactions to minimize financial loss and enhance customer trust.
- **Techniques Used:** Data preprocessing, feature engineering, class imbalance handling, and supervised machine learning.
- **Models:** Logistic Regression and Random Forest.

## Dataset

- The dataset contains transaction records with features such as transaction type, amount, balances, and fraud labels.
- [Dataset Link](https://drive.google.com/file/d/1ZIjmAjPccvy16mOk7nrPtWe-_3rRP5zy/view?usp=sharing)

## Workflow

1. **Exploratory Data Analysis (EDA):**
   - Inspected data shape, missing values, and class distribution.
   - Visualized transaction types and fraud distribution.

2. **Data Preprocessing:**
   - Addressed class imbalance using undersampling.
   - Applied one-hot encoding to categorical features.

3. **Feature Selection:**
   - Selected relevant features for model training.
   - Defined `isFraud` as the target variable.

4. **Model Training:**
   - Split data into training and test sets (80/20 split).
   - Trained and evaluated Logistic Regression and Random Forest classifiers.

5. **Evaluation:**
   - Used metrics such as confusion matrix, classification report, and ROC-AUC.
   - Achieved high AUC scores, demonstrating strong fraud detection capability.

## Results

- **Random Forest** delivered the best performance with an AUC score of 0.97, indicating excellent ability to distinguish between fraudulent and legitimate transactions.
- The solution is scalable and can be adapted to evolving fraud patterns.

## Conclusion

This project demonstrates the power of machine learning in combating online payment fraud. By leveraging advanced analytics, Blossom Bank can better safeguard assets, reduce losses, and enhance customer confidence.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## How to Run

1. Clone the repository or download the notebook.
2. Install dependencies:  
   `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Download the dataset and place it in your working directory.
4. Open and run the notebook step-by-step.

