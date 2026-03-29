# Iris Flower Classification 🌸

## 📌 Objective
Classify iris flowers into species using machine learning.

## 🌼 Classes
- Setosa
- Versicolor
- Virginica

## ⚙️ Features
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 🤖 Models Used
- Logistic Regression
- KNN
- Decision Tree

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix

## ▶️ How to Run

1. Install libraries:
pip install pandas numpy scikit-learn matplotlib seaborn joblib

2. Run notebook

## 🔮 Prediction Example

import joblib

model = joblib.load("iris_model.pkl")
prediction = model.predict(sample_data)

print(prediction)
