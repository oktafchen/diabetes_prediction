# Diabetes Prediction with XGBoost

This project uses health data to predict the likelihood of diabetes using a machine learning model (XGBoost).

## Files

- `diabetes_model.ipynb`: training notebook
- `scaler.pkl`: saved MinMaxScaler
- `xgb_diabetes_model.pkl`: trained model

## Dataset

This project uses the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

## How to use

1. Load the scaler and model from `.pkl` files
2. Prepare input in dictionary format
3. Use `.predict()` and `.predict_proba()` to infer
