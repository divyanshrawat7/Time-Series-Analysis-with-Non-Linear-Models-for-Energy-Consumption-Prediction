# 📊 **__Time Series Energy Consumption Forecasting__**

Predicting India's hourly electrical load using non-linear ML models.

This project focuses on developing and comparing different forecasting models to predict hourly electricity demand in India.  
The aim is to analyze how various non-linear and deep learning models behave on time-dependent energy data.

---

## 🚀 **__Features__**

- End-to-end time series pipeline  
- Multiple models trained and compared  
- Feature engineering, visualization, and error analysis  
- GPU-accelerated training (tested on Colab T4)

---

## 🧠 **__Models Used__**

- LSTM Model (Deep Learning)  
- XGBoost Model  
- Random Forest Model  
- Linear Regression Model  

Each model is trained, evaluated, and compared to identify the best performer for forecasting.

---

## 📁 **__Repository Structure__**

**Time_series_analysis_for_Energy_Forecasting_Final.ipynb**  
→ Notebook containing preprocessing, model training, and evaluation.

**hourlyLoadDataIndia.xlsx**  
→ Dataset used for training the models.

---

## 📦 **__Requirements__**

Python 3.8+

Install dependencies using:
```bash
pip install pandas numpy scikit-learn xgboost statsmodels matplotlib seaborn tensorflow keras-tuner
```
---

## 🛠️ **__How to Run__**

### **1. Download Dataset**
Download the dataset from Kaggle:  
https://www.kaggle.com/datasets/shubhamvashisht/hourly-load-india-electrical-load-forecasting

### **2. Setup Environment**
- Upload the notebook and dataset to Google Colab  
- Select **GPU (T4)** under:  
  Runtime → Change runtime type → GPU

### **3. Train the Models**
Run the notebook sequentially.  
Each model will train and generate:

- Forecast plots  
- Error metrics (RMSE, MAPE, R²)  
- Model comparison results  

---

## 📈 **__Outputs__**

You will get:

- Visual comparison of all forecasting models  
- Performance evaluation metrics  
- Insights on which model performs best for energy load forecasting
