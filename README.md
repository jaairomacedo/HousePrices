# 🏠 HousePrices

Repository created for participation in the Kaggle competition:  
**[House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)**.

The challenge consists of predicting house prices in **Ames, Iowa (USA)**, based on a wide set of structural and locational features.

---

## 📌 [Step 1: First Model]([https://github.com/lucaslealx/HousePrices/blob/main/Etapa1.ipynb](https://github.com/jaairomacedo/HousePrices/blob/main/Coding/Code_1.ipynb))

In this initial step, we developed a simple baseline model to evaluate performance without any advanced data treatment or feature engineering.

### Key steps:

- **Minimal preprocessing**:  
  - Replaced all missing values with `-1`  
  - Dropped all text (categorical) columns

- **Trained three basic algorithms**:  
  - [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)  
  - [Decision Tree Regressor](https://scikit-learn.org/stable/modules/tree.html#regression)  
  - [KNeighborsRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsRegressor)

- **Model evaluation** based on two metrics:  
  - [Mean Absolute Error (MAE)](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)  
  - [Mean Squared Error (MSE)](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html),  
    with a preference for the latter, as it is the official evaluation metric in the competition.

### 🎯 Result:
> **Public score on Kaggle:** `0.25476`
