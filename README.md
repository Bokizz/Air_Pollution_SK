# 🌫 Air Pollution Prediction System

This project implements a machine learning pipeline to predict air pollution levels (PM2.5 and PM10) using historical air quality data. Multiple regression models are trained and evaluated to determine the best-performing approach.

---

## 📌 Features
- Data loading and preprocessing with Pandas and NumPy  
- Time-series based validation using TimeSeriesSplit  
- Training and comparison of multiple regression models  
- Performance evaluation using Mean Absolute Error (MAE)  
- Visualization of model performance  

---

## 🧠 Machine Learning Models
The following models are trained and compared:
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Extra Trees Regressor  
- Decision Tree Regressor  
- XGBoost Regressor  

---

## 🗂 Dataset
The project uses air quality datasets containing pollution measurements such as:
- PM2.5  
- PM10  

The data is cleaned, merged, and prepared before training the models.

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  

---

## 📊 Evaluation
Models are evaluated using:
- Mean Absolute Error (MAE)  
- TimeSeriesSplit cross-validation  

Results are visualized to compare model performance.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Bokizz/Air_Pollution_SK.git
## Install dependencies
- pip install pandas numpy scikit-learn xgboost matplotlib
