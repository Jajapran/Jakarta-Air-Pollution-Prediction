# Jakarta-Air-Pollution-Prediction
This repository contain the codes and resources for my thesis project, where I develop a model for air pollution levels in DKI Jakarta using machine learning techniques. The primary objective is to predict key air quality indicators such as PM10, SO2, CO, O3, and NO2 using Long-Short Term Memory (LSTM) model, a type of Recurrent Neural Network (RNN) well-suited for time series forecasting.
## Dataset
The dataset used in this project consists of historical air pollution data collected from official sources in Jakarta for 12 years. It includes:
- PM10 (Particulate Matter ≤ 10 micrometers)
- Sulfur Dioxide (SO2)
- Carbon Monoxide (CO)
- Ozone (O3)
- Nitrogen Dioxide (NO2)
## Steps Followed
- Data preparation
- LSTM data preparation
- Model fitting
- Evaluate model
### Data Preparation
- Data cleaning
- Replace missing values
### LSTM Data Preparation
- Handling data outliers
- Transformed data into supervised learning problem
### Model Fitting
- Split data into data training and data testing
- Reshape into 3D
- Define LSTM architecture
### Evaluate Model
- Make prediction
- Invert scaling
- Calculate RMSE (Root Mean Square Error) and MAPE (Mean Absolute Percentage Error)
- Plot the line between actualn vs predicted values

## Results and Performance
The Long-Short Term Memory (LSTM) model, implemented using the Keras Library, showed strong predictive performance in forecasting air pollution levels in DKI Jakarta. The model achieved an average RMSE of 9.5727 across five test runs, with individual RMSE values ranging between 9.55 and 9.61. These results demonstrate that the LSTM model provides a high level of accuracy for predicting air pollution, making it a reliable tool for environmental forecasting in urban areas like Jakarta.
