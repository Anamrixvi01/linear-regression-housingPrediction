# linear-regression-housingPrediction
# Housing Price Prediction with Linear Regression

This project uses a simple linear regression model to predict housing prices based on features from `housing.csv`. It's a beginner-friendly example of applying machine learning to real-world data.

## 📂 Dataset
- Source: `housing.csv`
- Features used: Avg. Area Income	Avg. Area House Age	Avg. Area Number of Rooms	Avg. Area Number of Bedrooms	Area Population	Address
- Target: `Price`

## ⚙️ Model
- Algorithm: Linear Regression
- No feature engineering applied
- Evaluation metrics:
 MAE: 82288.22251914954
 MSE: 10460958907.2095
 RMSE: 102278.82922291152

## 🚀 How to Run
```python
# Train the model
model.fit(X_train, y_train)

# Predict
predictions = model.predict(X_test)
