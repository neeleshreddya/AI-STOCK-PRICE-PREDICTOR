AI Stock Price Predictor Using LSTM

This project utilizes a Long Short-Term Memory (LSTM) neural network built with TensorFlow/Keras to predict future stock prices based on historical stock market data. The goal is to help investors and analysts understand stock trends using AI-powered time series forecasting.
Dataset

The model is trained on a stock dataset (ADANIPORTS.csv) that includes daily records of:

    Open Price

    High Price

    Low Price

    Close Price

    Volume

This dataset provides a solid basis for training the model to identify patterns over time.
Project Highlights

    Time-series data preprocessing using MinMaxScaler.

    Sequence generation for LSTM input.

    LSTM model architecture using Keras (TensorFlow backend).

    Model training and prediction on test data.

    Visualization comparing predicted vs actual stock prices.

Dependencies

Install required packages using:

pip install -r requirements.txt

Usage

    Clone the repository.

    Place ADANIPORTS.csv in the root directory.

    Run the Python script (stock_predictor.py or similar).

The script will:

    Load and process the dataset.

    Train an LSTM model on the training set.

    Predict on the test set.

    Plot actual vs predicted prices for visual comparison.

Sample Output

The output includes a line plot:

    🔵 Blue Line: Actual Stock Prices

    🔴 Red Line: Predicted Stock Prices

This plot helps evaluate the model’s performance visually.
Author

Developed using Python, Pandas, NumPy, Scikit-learn, Matplotlib, and TensorFlow/Keras.