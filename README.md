# Superstore-Sales
What opportunities exist in the Superstore market to forecast sales for the next 7 days in order to optimize inventory decisions, reduce stockouts and overstocking. 
# Capstone Two: Superstore Sales Forecasting (7-Day Time Series)

## 📌 Objective
To forecast Superstore daily sales for the next 7 days to support inventory optimization, reduce stockouts, and enable regional managers to respond proactively to demand shifts.

## 🛠️ Methods Used
- Data Aggregation and Cleaning
- Time-Based Train/Test Split
- SARIMA Model (Baseline time series forecast)
- Lag-Based Linear Regression Model (Final model)

## 📊 Model Evaluation

| Model | MAE | RMSE |
|-------|-----|------|
| SARIMA | 1761.55 | 2452.65 |
| **Lag-Based Regression** | **1716.42** | 2509.28 |

## 🏆 Final Model
**Lag-Based Linear Regression** was chosen for its lower MAE, simplicity, and effectiveness for short-term inventory planning.

## 📁 Files Included
- `Capstone_Two_Modeling_Final.ipynb` – Full notebook with code and commentary
- `Capstone_Two_Modeling_Final.html` – HTML version of the notebook
- `train 2.csv` – Original dataset

## 🔗 Author
Maria Alejandra Suarez Riaño – [Springboard Data Science Career Track]
