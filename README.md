## 🏠 House Price Prediction Project

This project aims to predict house prices using various machine learning models and advanced feature engineering techniques.

### 📊 Project Steps

- Performed data preprocessing and handled missing values  
- Applied log transformation to reduce skewness in target variable  
- Created new features such as TotalSF, TotalBathrooms, and HouseAge  
- Compared multiple machine learning models:
  - Linear Regression
  - Ridge & Lasso
  - Random Forest
  - XGBoost
  - LightGBM  

### ⚙️ Model Optimization

- Applied GridSearchCV for hyperparameter tuning  
- Evaluated models using Mean Absolute Error (MAE)  
- Compared model performances to select the best one  

### 🏆 Final Model

XGBoost achieved the best performance with the lowest MAE, outperforming other models due to its ability to capture complex non-linear relationships.

### 📌 Key Insights

- Feature engineering significantly improved model performance  
- Scaling was critical for linear models but not required for tree-based models  
- Boosting algorithms provided the best results on this dataset  

### 🚀 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost, LightGBM  
- Matplotlib / Seaborn  

---
