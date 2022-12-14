# Power Prediction Forecasting
Time-Series forecasting of power prediction of a single family home in Paris

## Objectives

- Build a time-series prediction model for electricity consumption for a house in Paris, based on historical data from Dec. 2006 till Nov. 2010.
- Compare the ML algorithms Logistic Regression, Decision Tree, XGB Regressor and the DL model LSTM.

## Dataset Description

- Electric power consumption of a house near Paris, France.
- Over 2 million rows of measurements.
- One-minute sampling.
- A period of nearly 4 years (December 2006 – November 2010).
- Nine (9) attributes of date, time, active power, reactive power, voltage, intensity and 3 sub-metering.

## Conclusions

- Machine Learning algorithms can be used to solve time-series. However, the performance will not be satisfactory.
- The choice of engineered features is crucial in improving the predictions of time-series forecast.
- Looking into temporal change is important in engineering useful features.
- Non-linear ML algorithms such as  XGB regression prove to produce results better than pre-determined average(s).
- LSTM produces more representative results than ML algorithms.
- Tuning the LSTM model is needed to improve results.
- Multi-step LSTM is next step as it enables producing several future predictions.
- Main goal in tuning the model is to balance the number of the previous measurements and the future ones, in order to produce results that are close to actual.

#### References
- Dataset:
	https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption
- Deep Learning for Time Series Forecasting, Jason Brownlee
- Code: 
	https://www.kaggle.com/code/winternguyen/predict-household-electric-power-using-lstm/notebook

