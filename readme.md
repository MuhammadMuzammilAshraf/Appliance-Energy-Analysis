# Time Series Analysis: Comparing LSTM and ARIMA Models

This notebook demonstrates a comprehensive approach to time series forecasting using two popular models: Long Short-Term Memory (LSTM) networks and AutoRegressive Integrated Moving Average (ARIMA). The primary focus is on predicting appliance energy usage from time-stamped data recorded every 10 minutes.

### Key Steps and Techniques:

1. **Exploratory Data Analysis**:
   - The initial phase involves understanding the dataset's structure, identifying missing values, and highlighting the significance of appliance energy usage in energy management and cost savings.
   
2. **Data Preparation**:
   - Feature normalization using MinMaxScaler to prepare the data for LSTM training.
   
3. **LSTM Model**:
   - **Data Structure**: Time series data is reshaped to create a sequence suitable for LSTM, including data preparation for both inputs and forecast sequences.
   - **Model Training**: A Sequential LSTM model is designed and trained with 50 epochs using 'Adam' optimizer.
   - **Evaluation**: The model's performance is assessed using MSE, MAE, and R-squared metrics, and predictions are plotted against actual values.
   
4. **ARIMA Model**:
   - **Data Stationarity**: The stationarity of the data is verified using the ADFuller test to ensure it is suitable for ARIMA modeling.
   - **Model Fitting**: An ARIMA model is fitted, and its residuals are analyzed.
   - **Prediction and Evaluation**: The ARIMA model's forecasts are compared with the actual data, and performance metrics are calculated.
   
5. **Model Comparison**:
   - Both models are evaluated and compared to determine their efficacy in handling time series data in different scenarios.

Each section of the notebook includes detailed steps for data manipulation, model building, and evaluation, making it a valuable resource for anyone looking to understand or apply time series in their projects.
