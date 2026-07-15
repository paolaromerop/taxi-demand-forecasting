![Taxi Forecasting Results](taxi_forecasting_result.png)

# 🚕 Taxi Demand Forecasting

Time series forecasting project developed to predict hourly taxi demand and support fleet planning during peak periods.

---

## 📌 Project Summary

This project focuses on forecasting the number of taxi orders required for the following hour.

The objective was to build a regression model capable of predicting short-term demand using historical order data, temporal patterns and lag-based features.

The final solution improved significantly over the baseline model and achieved the required performance target.

---

## 🏆 Key Results

- **Best Model:** Random Forest Regressor
- **Test RMSE:** **43.10**
- **Baseline RMSE:** **58.88**
- Required target: **RMSE ≤ 48**
- Final model successfully exceeded the project performance requirement

---

## 💼 Business Problem

Taxi demand varies significantly depending on the hour, day and recent order patterns.

Accurate short-term forecasting helps the company:

- Allocate drivers more efficiently
- Reduce customer waiting times
- Prepare for peak-demand periods
- Improve operational planning

The goal was to predict the number of taxi orders required during the next hour.

---

## 📂 Dataset

The dataset contains historical taxi-order records indexed by date and time.

The project included:

- Time-series resampling
- Trend and seasonality analysis
- Temporal feature creation
- Lag-variable engineering
- Model training and evaluation

---

## ⚙️ Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Scikit-learn
- Time Series Analysis
- Feature Engineering

---

## 🔬 Project Workflow

- Data Inspection
- Time-Series Resampling
- Exploratory Data Analysis
- Trend and Seasonality Analysis
- Feature Engineering
- Lag Variable Creation
- Model Training
- Baseline Comparison
- Performance Evaluation

---

## 🤖 Models Evaluated

The project compared multiple regression approaches, including:

- Baseline Prediction
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

The models were evaluated using **Root Mean Squared Error (RMSE)**.

---

## 📈 Model Selection

The baseline model produced an RMSE of **58.88**.

After creating temporal variables and lag-based features, the final Random Forest model achieved a test RMSE of **43.10**.

This result met the required project threshold of RMSE ≤ 48 and demonstrated a meaningful improvement over the baseline.

---

## 💡 Business Impact

The forecasting model can help the taxi company anticipate hourly demand and improve fleet allocation.

Potential benefits include:

- Better driver availability
- Reduced passenger waiting times
- More efficient operational scheduling
- Improved response during high-demand periods

---

## 📁 Repository Structure

```text
taxi-demand-forecasting
│
├── taxi_demand_forecasting.ipynb
└── README.md
```

---

## 👩‍💻 Author

**Paola Romero**

Data Analyst | Business Intelligence | Data Science

📁 Portfolio  
https://paolaromerop.github.io/paola-portafolio/

💼 LinkedIn  
https://www.linkedin.com/in/paolaromeroperez/

---

Developed as part of the TripleTen Data Science Bootcamp, applying time-series forecasting and feature engineering techniques to a real-world operational problem.
