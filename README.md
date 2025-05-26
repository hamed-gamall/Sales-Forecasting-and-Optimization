# 🏬 Walmart Sales Forecasting using Machine Learning

> Final project for the Data Scientist Track – Digital Egypt Pioneers Initiative (DEPI) by MCIT in collaboration with IBM and  Learning.

![Project Banner](https://your-image-link.com/banner.png) 

---

## 📌 Project Summary

This project aims to forecast product demand and future sales for a major retail chain (Walmart) using multiple machine learning and deep learning techniques. With over **420,000+ records**, we built robust models that assist in **inventory planning, demand estimation**, and **data-driven decision-making**.

---

## 🧠 Objective

- Predict weekly sales with high accuracy.
- Enable smarter inventory management and resource allocation.
- Build a real-time interactive tool for predictions using **Streamlit** and **Dash**.

---

## 📂 Dataset

- **Location:** `Data/` folder in this repository 
- **Records:** 420K+
- **Features Include:** Store ID, Department, Weekly Sales, Holiday Flags, Temperature, Fuel Prices, CPI, Unemployment.

---

## 🔧 Workflow

### 🧹 1. Data Preprocessing
- Missing value handling
- Duplicate removal
- Data type fixing and normalization
- Outlier detection and treatment

### 📊 2. Exploratory Data Analysis (EDA)
- Trends across time, stores, departments, and events
- Correlation heatmaps and boxplots
- Visual insights using Seaborn, Plotly & Matplotlib

### 🧬 3. Feature Engineering
- Encoding categorical variables
- Date-based features
- Lag & rolling statistics
- Scaling for time series

### 🤖 4. Modeling
Applied a wide range of models including:
- ✅ XGBoost (Tuned with GridSearchCV)
- ✅ CatBoost
- ✅ Random Forest
- ✅ ElasticNet
- ✅ LSTM
- ✅ WaveNet
- ✅ Prophet
- ✅ ARIMA / SARIMA

📈 **Best Model: XGBoost with R² Score = 0.99**

### 📏 5. Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score
- Explained Variance Score

### 🌐 6. Deployment
- Interactive dashboards using:
  - ✅ Streamlit [👉 Try App](https://your-streamlit-link.app)
  - ✅ Dash [👉 Try App](https://your-dash-link.com)

---

## ⚙️ Techniques Used

- Feature Engineering & Selection
- Hyperparameter Tuning (GridSearchCV, RandomizedSearchCV)
- Time Series Forecasting Techniques
- Ensemble Models & Deep Learning
- Interactive Deployment (Streamlit, Dash)
- Git/GitHub for version control
 

### 👨‍🏫 Supervision & Training

- Instructor: **Baraa Abu Sallout**  
- Training Provider: **AMIT Learning**  
- Initiative: **Digital Egypt Pioneers - MCIT**  
- Global Partner: **IBM**
