# Boston House Price Prediction 🏡

This project applies machine learning techniques to predict house prices in Boston based on various economic and geographical features. The objective is to build an accurate regression model using the Boston Housing Dataset and evaluate its performance using standard metrics.

---

## 📚 Project Description

The Boston Housing Dataset is a well-known dataset used for regression tasks in the field of machine learning. In this project, we aim to:

- Explore the dataset and understand key features influencing housing prices.
- Apply preprocessing techniques to prepare the data for modeling.
- Train and evaluate multiple regression models.
- Interpret results and analyze model performance using appropriate evaluation metrics.

---

## 🔍 Dataset Information

The dataset includes 506 entries with 13 numerical features and one target variable:

- **Features** include:
  - CRIM: Crime rate by town
  - RM: Average number of rooms per dwelling
  - DIS: Distance to employment centers
  - LSTAT: % lower status of the population
  - TAX: Property tax rate
  - PTRATIO: Pupil-teacher ratio, and more.
  
- **Target Variable**: `PRICE` — Median value of owner-occupied homes (in $1000s)

Dataset is sourced from `sklearn.datasets`.

---

## ⚙️ Technologies Used

- **Language**: Python 3
- **Environment**: Jupyter Notebook
- **Libraries**:
  - `pandas` for data handling
  - `numpy` for numerical operations
  - `matplotlib` & `seaborn` for visualization
  - `scikit-learn` for model building

---

## 🧠 Machine Learning Workflow

1. **Data Loading and Exploration**
2. **Data Cleaning & Correlation Analysis**
3. **Train-Test Split**
4. **Model Building**:
   - Linear Regression (baseline model)
   - Additional models can be added for comparison
5. **Model Evaluation**:
   - R² Score
   - Root Mean Squared Error (RMSE)
   - Visualization of predictions

---

## 📈 Results

- **Model Used**: Linear Regression
- **R² Score**: ~0.74
- **RMSE**: ~4.7
- Performance indicates a reasonably good fit for the dataset.

---

## 🚀 Getting Started

### Prerequisites

Install Python and required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

git clone https://github.com/yourusername/boston-house-price-prediction.git
cd boston-house-price-prediction
