# 🏦 Loan Approval Prediction

This project predicts whether a loan application will be approved or not using machine learning.  
It is based on a classification model trained on a dataset containing applicant and loan-related features.

---

## 📌 Project Overview

Loan approval prediction is an important task for financial institutions to automate and speed up the loan application process.  
This project uses a dataset of past loan applications and builds a classification model to determine approval (`1`) or rejection (`0`) of a loan.

We evaluate the model using **accuracy, precision, recall, and F1-score**, and visualize results using a confusion matrix.

---

## 📊 Dataset

- **File:** `loan_prediction.csv`
- **Features include:**
  - Applicant details (Gender, Married, Education, Self_Employed, Dependents)
  - Financial details (ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History)
  - Loan details (Property_Area, Loan_Status)

---

## 🛠 Tech Stack

- **Python** (Data processing, ML modeling)
- **Libraries Used:**
  - `pandas` – Data loading & preprocessing
  - `numpy` – Numerical computations
  - `matplotlib` & `seaborn` – Data visualization
  - `scikit-learn` – Machine learning modeling & evaluation

---

## ⚙️ Model Building Steps

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. **Model Training**
   - Train-test split
   - Model selection (e.g., Logistic Regression, Decision Tree, Random Forest, etc.)
   - Hyperparameter tuning (if applied)

3. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score, Accuracy)

---

## 📈 Results

Confusion Matrix:

| Actual \ Predicted | 0   | 1   |
|--------------------|-----|-----|
| **0**              | 18  | 25  |
| **1**              | 3   | 77  |

Classification Report:
macro avg 0.81 0.69 0.70 123
weighted avg 0.78 0.77 0.75 123

- **Accuracy:** 77%
- The model predicts class `1` (approved loans) better than class `0` (rejected loans).

---

## 📷 Visualizations

### Confusion Matrix
![Confusion Matrix](Loan%20prediction%20output.png)

---

## 🚀 How to Run the Project

    1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/loan-approval-prediction.git
  
    2.Navigate to the project folder:
    cd loan-approval-prediction

    3.Install dependencies:
    pip install -r requirements.txt

    4.Run the Jupyter Notebook:
    jupyter notebook Loan_prediction.ipynb

📌 Future Improvements

    1.Try other classification algorithms (XGBoost, LightGBM)

    2.Balance the dataset using SMOTE or undersampling

    3.Optimize hyperparameters for better performance

    4.Deploy as a web app using Flask/Streamlit
