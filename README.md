
# Descriptive, Diagnostic & Forecast Analysis of Passenger Flights at Juanda Surabaya Airport Based on Google Trends (2011 – August 2023)

**Proposed Research:**
This study aims to analyze the characteristics of passengers and air operators based on domestic and international flight traffic data at Juanda Surabaya Airport from 2011 to August 2023.


## What is explained?

- Company Profile, Background & Objective
- Literature Study, Data Source & Variable
- Related Works
- Theory and Methodology 
- Descriptive Analysis Highlight: _Traffic share by Destination, Annual Passenger Traffic by Airline, Monthly Passenger Traffic Heatmap, Time Series Decomposition_ 
- Diagnostic Analysis: _Correlation, Time Series Forecasting with ARIMA, LSTM and Prophet_
- Descriptive & Diagnostic Conclusion
- Forecasting Model Conclusion

## What is our **Descriptive & Diagnostic** conclusion?

1. Passengers traffic steadily grows from 2011 through 2018 but from 2019 through 2023 drastically decreases because of covid 19’s effects.
2. In 2023 the number of passengers has not experienced an increasing trend as it did before 2019.
3. Based on international and domestic categories, Juanda Airport is predominantly dominated by domestic flights overall.
4. Lion Air is the most dominant among the seven dominant airlines operators.
5. There are two peak points every year from 2011-2023. The peak points are in July (School Holiday) and December (Christmas and New Year Holiday).
6. The number of passengers has a negative correlation with the price of gold (GC=F) with a coefficient of -0.69.
7. The number of passengers has a great positive correlation with the mobility score with a coefficient of 0.9

## What is our **Forecasting Model** Conclusion?

1. The study aimed to forecast the number of passengers at Juanda Airport from 2011 to 2023.
2. Four different forecasting models were applied and evaluated for their accuracy. Results showed significant differences in forecasting accuracy among the models.
3. The Long Short-Term Memory (LSTM) model emerged as the most accurate, achieving the lowest Root Mean Squared Error (RMSE) and Mean Absolute Percentage Error (MAPE).
4. The Autoregressive Integrated Moving Average (ARIMA) model also provided reasonably accurate predictions, outperforming the Prophet models.
5. The Prophet model, when supplemented with Google Trends data as exogenous variables, improved forecasting accuracy by reducing MAPE from 0.863 to 0.36.
6. Despite the enhancement with exogenous variables, the Prophet model still fell short of the accuracy achieved by the LSTM and ARIMA models.

Collab Notebook:
[https://github.com/user-attachments/assets/715f8283-e497-4c13-a8f7-cf64747120e2](https://drive.google.com/file/d/1ZMrzCP0ZYQ0lfOIMbL4CNgyt5L1pGTXU/view)

