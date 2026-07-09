# House Price Prediction

A machine learning regression project that predicts house sale prices using the Kaggle House Prices dataset.

Built to learn regression techniques and model comparison.

## What I did
- Explored and cleaned a dataset with 80 features and 1460 rows
- Handled missing values by dropping high-null columns and imputing the rest
- Applied one-hot encoding to categorical features using pd.get_dummies
- Aligned train and test columns to avoid mismatches after encoding
- Compared three models: Linear Regression, Random Forest, and XGBoost
- Selected XGBoost as the best model (MAE: 16324.18 | RMSE: 26,465 | R2: 0.91)
- Generated final predictions and submitted to Kaggle

## Libraries used
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost

## Dataset
From the [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
