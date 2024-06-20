# IS403_O21_9 : Forecasting fuel prices using time series analysis techniques

## Introduction
This repository contains the code and resources for a class project on forecasting cryptocurrency prices using statistical models and machine learning algorithms. The project explores the performance of Linear Regression, ARIMAX, Recurrent Neural Networks (RNN), Gated Recurrent Units (GRU), Long Short-Term Memory (LSTM) networks, Fast Fourier Transform Forecasting Model (FFT), Random Forest (RF), and Dynamic Linear Model DLM in forecasting the prices of Crude Oil, Gasoline Oil, and Heating oil.

## Dataset
The dataset used in this project is collected from (https://www.investing.com), containing daily data for Crude Oil, Gasoline Oil, and Heating oil from 1.1.2019 to 30.6.2024. The dataset includes features such as open price, high price, low price, close price, adjusted close price, and trading volume.

## Feature Engineering
To improve the predictive performance of the models, the project incorporates technical indicators as features. These indicators, such as moving averages and momentum indicators, provide insights into market sentiment and trends, aiding in the prediction of price movements.

## Models
The following models are implemented and evaluated in this project:

- Linear regression
- FCN
- ARIMA
- AddRNN
- RNN
- Fast Fourier Transform Forecasting Model (FFT)
- GRU
- DLM
- LSTM
- Random Forest


## Evaluation
The models are evaluated using various performance metrics, such as Root Mean Squared Error (RMSE), Mean Absolute Percent Error (MAPE), and Symmetric Mean Absolute Percentage Error (SMAPE). Three different train-test split ratios are used for each model: 70:30, 80:20, and 90:10. The results are compared to assess the strengths and weaknesses of each model in accurately predicting cryptocurrency prices.

## Division of Work
| Member | Responsibilities |
| --- | --- |
| Le Thi Thanh Hang | Implemented FFT, RNN. Assisted in model evaluation and result analysis.|
| Ngo Tat To | Implemented GRU, DLM. Assisted in model evaluation and result analysis.|
| Nguyen Nhat Phuong Huy | Implemented LSTM, Random Forest. Contributed to literature review and project documentation.|
| Le Xuan Thach | Implemented Linear regression + FCN. Assisted in model evaluation and result analysis.|
| Ho Quang Dinh | Implemented ARIMA, AddRNN. Contributed to literature review and project documentation.|


## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments
We would like to thank our instructor and the University of Information Technology for providing the resources and support for this class project.
