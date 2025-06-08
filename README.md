# 🏡 House Price Prediction using Linear and Polynomial Regression

This project explores predicting house prices based on synthetic real estate data using **Linear Regression** and **Polynomial Regression** models. The dataset simulates real-world features like property size, number of rooms, and location score to train and evaluate regression models.

---

## 📊 Project Overview

- **Objective**: Predict house prices using multiple regression techniques.
- **Data**: Synthetic dataset with 120 samples and 3 features:
  - `Size` (in m²)
  - `Num_Rooms` (1 to 7)
  - `Location_Score` (0 to 10)
- **Target Variable**: `House_Price`

---

## 🔧 Technologies & Libraries

- Python 3.x
- `pandas`, `numpy` for data manipulation
- `matplotlib` for visualizations
- `scikit-learn` for modeling and evaluation

---

## 🔁 Workflow

### 1. Data Generation
- A synthetic dataset is generated using known mathematical relationships and added noise for realism.

### 2. Exploratory Data Analysis
- Data preview and statistical summaries
- Correlation matrix inspection
- Scatter plots for each feature vs house price

### 3. Linear Regression
- Fit and train a linear model
- Evaluate using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Visualizations:
  - Residual plot
  - Predicted vs Actual values

### 4. Polynomial Regression
- Train polynomial models with varying degrees (`degree=2` to `6`)
- Evaluate model performance using MSE, RMSE, and R² Score
- Compare performance with linear model

---

## 📈 Sample Results

| Model Type | Degree | RMSE (Test) | R² Score |
|------------|--------|-------------|----------|
| Linear     | 1      | ~3932       | ~0.94    |
| Polynomial | 2      | Lower RMSE  | Higher R²|
| Polynomial | 3–6    | Tuning phase: Evaluate for overfitting/underfitting |

> 📌 Higher-degree polynomials may improve accuracy but risk overfitting.

---

## 📷 Visualizations

- Residual Plots
- Actual vs Predicted Price Plots
- Feature vs Target Scatter Plots

---

## 🧠 Key Insights

- **Size**, **Number of Rooms**, and **Location Score** all influence house prices.
- **Polynomial regression** captures nonlinear relationships and improves accuracy over simple linear regression.
- Overfitting risk increases with high-degree polynomials.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RandikaSilva/House-Price-Prediction-using-Linear-and-Polynomial-Regression
   cd House-Price-Prediction-using-Linear-and-Polynomial-Regression
