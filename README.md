# 💎 Diamond Price Prediction App

## 📌 Project Overview
This is an end-to-end machine learning project that predicts diamond prices based on various features such as carat, cut, color, clarity, and dimensions.

The model is built using **K-Nearest Neighbors (KNN) Regression** and deployed as a web application using **Streamlit**.

---

## 🎯 Objective
To build a complete ML pipeline including:
- Data preprocessing
- Model training and evaluation
- Deployment using Streamlit

---

## 📊 Dataset
- diamonds.csv  
- description.txt  

The dataset contains features like:
- carat (weight of diamond)
- cut (quality)
- color
- clarity
- depth
- table
- x, y, z (dimensions)
- price (target variable)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## 🤖 Model Details
- Algorithm: KNN Regressor
- Evaluation Metrics:
  - MAE
  - RMSE
  - R² Score

---

## 📈 Model Performance
- MAE: ~291  
- RMSE: ~500  
- R² Score: ~0.96  

The model shows strong performance with high accuracy and good generalization.

---

## 🚀 Deployment
The model is deployed using Streamlit Cloud.

### ▶️ Run Locally
```bash
streamlit run app.py
