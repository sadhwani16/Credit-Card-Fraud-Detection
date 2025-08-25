# Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using real-world anonymized data. This system helps identify suspicious transactions by analyzing transaction patterns and applying supervised learning algorithms.

## Project Overview

Credit card fraud is a growing problem that costs billions annually. This project aims to build an efficient, accurate fraud detection model by:

- Preprocessing a highly imbalanced dataset.
- Training classification models to distinguish between legitimate and fraudulent transactions.


## Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description**: Contains 284,807 transactions made by European cardholders in September 2013.
- **Features**: 30 anonymized features (V1 to V28), `Time`, `Amount`, and a target variable `Class`:
  - `Class = 1`: Fraud
  - `Class = 0`: Legitimate

> Note: The dataset is highly imbalanced, with only 492 fraudulent transactions.

## Features

- Data preprocessing and scaling
- Handling class imbalance using techniques like **SMOTE** or **undersampling**
- Training multiple classifiers: Logistic Regression, Random Forest, XGBoost

## Tech Stack

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`
  - `xgboost`

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```
