# Bank Personal Loan Prediction

This project aims to develop a machine learning model to predict whether a customer will accept a personal loan offer based on their financial and demographic information.

## Project Overview

- **Goal:** Predict customer acceptance of personal loan offers.
- **Dataset:** `bank_personal_loan.csv` (5,000 customers, no missing values).
- **Target Variable:** `Personal Loan` (1 = accepted, 0 = not accepted).

## Features

- Age, Experience, Income, Family size, Education level, Mortgage, Securities Account, CD Account, Online Banking, Credit Card usage, etc.

## Workflow

1. **Exploratory Data Analysis (EDA):**  
   Understand data distribution, check for duplicates, visualize features.

2. **Feature Engineering:**  
   - Drop irrelevant columns (ID, ZIP Code).
   - Handle skewed features with log transformation.
   - Address class imbalance using SMOTE.
   - Scale numerical features.

3. **Model Development:**  
   - Train and evaluate Random Forest, XGBoost, and Logistic Regression models.
   - Compare performance using accuracy, precision, recall, F1-score, and ROC AUC.

4. **Model Interpretation:**  
   - Analyze feature importance.
   - Provide actionable business insights.

## How to Run

1. Clone the repository:
   ```
   git clone <your-repo-url>
   cd bank-personal-loan
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Open `Finalproject_applied_Xia.ipynb` in Jupyter Notebook or VS Code.

4. Run the notebook cells in order.

## Results

- The best model is selected based on business needs (e.g., recall for positive class).
- Key predictors include income, CD account status, and education level.
- Actionable recommendations are provided for marketing and product strategy.

## License

This project is for educational purposes.