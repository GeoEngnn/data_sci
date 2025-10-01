# data_sci
📈 Stock Price Prediction and Forecasting using Stacked LSTM

This project demonstrates a time series forecasting model built with Stacked LSTM to predict stock prices.
The model uses the last 100 days of closing prices to predict the next day’s price and provides a 10-day forecast.
A Streamlit web application is created to interactively upload stock datasets, visualize trends, and view predictions in real-time.

🔥 Features

Upload your own stock price CSV file.

Visualize the historical stock price trend.

Predict the next day closing price.

Forecast the next 10 days using recursive prediction.

Interactive and easy-to-use web app built with Streamlit.

⚙️ Tech Stack

Python 3.12+

TensorFlow / Keras – for LSTM model

Streamlit – for interactive web app

Pyngrok / Localtunnel – to host the app in Colab

NumPy, Pandas, Matplotlib – for preprocessing and visualization

scikit-learn – MinMaxScaler for normalization
