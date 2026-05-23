# 🏠 House Price Prediction

## 📌 Overview
Predicting house sale prices using Machine Learning regression techniques.

## 📊 Dataset
- **Source:** Kaggle — House Prices: Advanced Regression Techniques
- **Train size:** 1460 rows, 81 columns
- **Test size:** 1459 rows
- **Target:** SalePrice (continuous value)

## 🔧 Steps Performed
1. Exploratory Data Analysis (EDA)
2. Handling Missing Values — Drop high missing columns, fill with median/mode
3. Feature Engineering — TotalSF, TotalBath, HouseAge, RemodAge
4. Label Encoding for categorical columns
5. Model Training — Random Forest Regressor
6. Hyperparameter Tuning — GridSearchCV

## 🤖 Model Used
- Random Forest Regressor
- Best Params: max_depth=None, min_samples_split=2, n_estimators=100

## 📈 Results
| Metric | Score |
|--------|-------|
| R2 Score | 0.892 |
| RMSE | $28,771 |
| Kaggle Public Score | 0.148 (RMSLE) |

## 📦 Libraries Used
```python
pandas, numpy, matplotlib, seaborn
sklearn
```
