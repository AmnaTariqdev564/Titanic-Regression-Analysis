# Titanic Dataset Regression Analysis 🚢📊

This project performs a predictive regression analysis on the Titanic dataset using machine learning. The focus is on applying preprocessing techniques and building a regression model to predict a continuous variable from the dataset.

---

## 📁 Dataset Used

- Dataset: `test.csv` from the Titanic dataset
- Objective: Predict a numerical target (e.g., `GrLivArea`) using available features

---

## 🧹 Data Preprocessing

- Dropped columns with more than 50% missing values
- Filled missing values:
  - Categorical: Mode
  - Numerical: Mean
- Label Encoded categorical features
- Scaled numerical features using `StandardScaler`

---

## 🤖 Model Building

- Algorithm: `RandomForestRegressor` from `sklearn.ensemble`
- Split: 80% training / 20% testing
- Trained the model on processed features

---

## 📊 Evaluation

- Metric: **Root Mean Squared Error (RMSE)**
- Result: **~59.89**, representing average prediction error

---

## 🧰 Tools & Libraries

- Python (Jupyter Notebook)
- Libraries: `pandas`, `numpy`, `scikit-learn`

---

## 📂 Files Included

- `Analysis.ipynb` – All preprocessing, training, and evaluation code
- `Titanic-Dataset.csv` – Original dataset
- `test.csv` – Processed version
- `logistic_regression_model.pkl` – (Optional, not used in this notebook)
- `predictions.csv` – Final predictions

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/AmnaTariqdev564/Titanic-Regression-Analysis.git
   ```
2. Open `Analysis.ipynb` in **Jupyter Notebook**
3. Run the cells step-by-step to view results

---

> 📝 **Note**: This project demonstrates a regression approach. With minor tweaks, it can be extended to a classification problem (e.g., predicting survival).
