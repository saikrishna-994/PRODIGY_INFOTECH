# PRODIGY_ML_TASK_1
# 🏠 House Price Prediction Using Linear Regression
This project uses a **Linear Regression** model to predict house prices based on key structural features of homes. The dataset is derived from the **Kaggle House Prices - Advanced Regression Techniques** dataset, a widely used dataset for regression modeling.
---

## 📌 Project Overview

- 📊 **Goal**: Predict house sale prices accurately using numeric features.
- 🧠 **Model**: Linear Regression (via `scikit-learn`)
- 📁 **Dataset**: `train.csv` (Kaggle House Prices )
- 📈 **Evaluation**: MAE, MSE, R² score, and residual plots

---

## 🔍 Features Used

- `LotArea`: Lot size in square feet
- `GrLivArea`: Above-ground living area (sq ft)
- `BedroomAbvGr`: Number of bedrooms above ground
- `TotRmsAbvGrd`: Total rooms above ground (excluding bathrooms)
- `GarageArea`: Size of garage in square feet

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas & NumPy (data wrangling)
- Seaborn & Matplotlib (visualization)
- scikit-learn (modeling & evaluation)

---

## 🧪 Key Steps

1. **Data Cleaning**  
   - Filled missing values for both categorical and numerical features

2. **Feature Selection**  
   - Selected numeric features with high correlation to sale price

3. **Model Training**  
   - Split data into training and validation sets (80/20)
   - Trained a linear regression model

4. **Evaluation**  
   - Measured error using MAE, MSE, and R² score
   - Visualized actual vs. predicted prices
   - Analyzed residuals for model fit diagnostics

---

## 📊 Sample Output
- Mean Absolute Error (MAE): 31174.25
- Mean Squared Error (MSE): 2381779181.97
- R-squared (R²): 0.6895
-Example Prediction of the house: $35,161.89

 
 Coefficient Summary:

Linear Regression Coefficients:
               Coefficient
LotArea           0.484396
GrLivArea        83.174545
BedroomAbvGr -20500.895527
TotRmsAbvGrd   3781.319309
GarageArea      120.203619

---


