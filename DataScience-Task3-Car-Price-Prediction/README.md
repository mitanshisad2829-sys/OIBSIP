# 🚗 Car Price Prediction using Machine Learning

## 📌 Oasis Infobyte Data Science Internship - Task 3

### 👩‍💻 Submitted by
**Mitanshi Sad**

---

## 📖 Project Overview

The objective of this project is to predict the selling price of a used car using Machine Learning techniques. Various factors such as the present price, manufacturing year, kilometers driven, fuel type, seller type, transmission type, and ownership history are used to estimate the selling price.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Explore the dataset using Exploratory Data Analysis (EDA).
- Build machine learning regression models.
- Compare different regression models.
- Identify the most important features affecting car prices.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

Dataset Used:
**Vehicle Dataset from CarDekho**

Features include:
- Car Name
- Year
- Present Price
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

---

## 📊 Exploratory Data Analysis

The following visualizations were performed:

- Distribution of Selling Price
- Selling Price vs Fuel Type
- Selling Price vs Car Age
- Correlation Heatmap
- Feature Importance Graph

---

## 🤖 Machine Learning Models

### 1. Linear Regression

Performance:

- MAE: **1.47**
- RMSE: **2.52**
- R² Score: **0.75**

---

### 2. Random Forest Regressor

Performance:

- MAE: **1.53**
- RMSE: **3.71**
- R² Score: **0.47**

---

## 📈 Best Model

Based on the evaluation metrics, **Linear Regression** performed better than Random Forest Regressor for this dataset.

---

## ⭐ Feature Importance

The most important feature for predicting the selling price was:

- Present_Price

Other influential features:

- Year
- Car_Age
- Kms_Driven

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be used to estimate used car prices. After preprocessing the data and training multiple regression models, Linear Regression achieved the best performance for this dataset. Feature importance analysis showed that the showroom price (Present_Price) has the greatest impact on the selling price.

---

## 📁 Project Structure

```
Car_Price_Prediction/
│── Car_Price_Prediction.ipynb
│── car_data.csv
│── README.md
│── 
```

---

## 🙏 Acknowledgement

This project was completed as part of the **Oasis Infobyte Data Science Internship Program**.
