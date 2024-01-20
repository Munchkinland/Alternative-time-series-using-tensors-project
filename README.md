# Time Series Analysis with ARIMA Model

This project focuses on time series analysis using the ARIMA (AutoRegressive Integrated Moving Average) model. The dataset used for this analysis is a time series of daily sales.

## Dataset

The dataset is loaded from the following URL:
[Sales Dataset](https://raw.githubusercontent.com/4GeeksAcademy/alternative-time-series-project/main/sales.csv)

## Exploratory Data Analysis

The initial steps include loading the dataset, converting the 'date' column to datetime, and resampling the data to daily frequency. The time series is then visualized and key insights are derived.

# Time Series Decomposition
The time series is decomposed to understand its components, including trend, seasonality, and noise. The Augmented Dickey-Fuller test is used to check for stationarity, and the variability or noise is visualized.

# ARIMA Model Training and Forecasting
An ARIMA model is trained on the data using the auto_arima function from the pmdarima library. The best model parameters are identified, and the model is then used to forecast future sales.

# Model Evaluation
The performance of the ARIMA model is evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). The actual vs. predicted values are visualized along with confidence intervals.

# Save the Model
The trained ARIMA model is saved for future use.

# Installation
To run the code, you need to install the required dependencies. You can do this by running:

pip install -r requirements.txt

# License
This project is licensed under the MIT License.

Feel free to explore and enhance the analysis based on your specific use case.




