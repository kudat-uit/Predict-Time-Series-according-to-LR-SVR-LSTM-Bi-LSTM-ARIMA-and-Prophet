<h1 align="center">Predict Time-Series according to Deep Learning Algorithms</h1>

This was **my project** for the **Intermediate Statistical Analysis course**. I predicted the **future 30 days** using **historical gold price datasets** from **Kaggle**.

### Project Description
Conducted time-series forecasting of gold prices for an Intermediate Statistical Analysis course, utilizing a dataset from Kaggle. The project involved predicting future gold prices over the next 30 days using various machine learning and deep learning models.

### Methods
- **Linear Regression**: Analyzed trends and relationships in data.
- **SVR** (Support Vector Regression): Applied to non-linear data patterns.
- **ARIMA** (Autoregressive Integrated Moving Average): Used for linear data showing trends.
- **Prophet**: Handled seasonal variations and trends over time.
- **LSTM** (Long Short-Term Memory): Addressed order dependence in sequence prediction.
- **Bi-LSTM** (Bidirectional Long Short-Term Memory): Enhanced LSTM by processing data from both past and future states.

### Evaluation Parameters
Measured effectiveness using RMSE and MAE.

### Result
The Bi-LSTM model exhibited superior performance with the lowest RMSE (397,070) and MAPE (0.73%), suggesting its efficacy in handling the inherent characteristics of the gold price dataset, leading to highly accurate forecasts.
