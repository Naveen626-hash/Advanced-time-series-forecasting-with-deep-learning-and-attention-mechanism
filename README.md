# Advanced-time-series-forecasting-with-deep-learning-and-attention-mechanism
LSTM + Attention Time Series Forecasting Web App: Built a Streamlit application that loads a trained LSTM-Attention model to forecast future time-series values. Integrated data preprocessing, scaling, interactive charts, and user-controlled input windows and horizons for real-time predictions.
Description:
Developed an interactive Streamlit web application that performs time-series forecasting using a custom-trained LSTM + Attention neural network model. The system predicts future values (such as hourly energy demand or similar sequential data) based on historical time-series patterns.

The application loads a pre-trained deep learning model (model.pkl / .h5) along with a scaling transformation (scaler.pkl / .npz) and generates forecasts for user-selected time windows. Users can input forecasting parameters such as input window size and prediction horizon, and the web app visualizes both historical and predicted values through dynamic charts.

Key Features:

Built a deep learning model using LSTM + Attention mechanism for enhanced pattern recognition in sequential data.

Implemented a user-friendly Streamlit interface to allow real-time forecasting.

Automatically loads and processes time-series data (resampling, cleaning, scaling).

Displays interactive line charts showing historical data and future predictions.

Designed a plug-and-play workflow where users can upload or load new datasets and models.

Used TensorFlow/Keras, NumPy, Pandas, Matplotlib, and Streamlit.

Tech Stack:
Python, Streamlit, TensorFlow/Keras, NumPy, Pandas, Matplotlib
