# Google Stock Price Forecasting

## Project Overview
This project explores time series forecasting of Google (GOOGL) stock prices using recurrent neural networks and hybrid deep learning architectures.

The main objective is to compare different neural network architectures for predicting stock closing prices over a three-day forecasting horizon.

## Dataset
- **Source:** Yahoo Finance (yfinance)
- **Stock Symbol:** GOOGL
- **Date Range:** January 2019 – December 2024
- **Target Variable:** Closing Price
- **Input Window:** Previous 10 days
- **Forecast Horizon:** Next 3 days

## Models Implemented
The following architectures are implemented and evaluated:

1. Simple RNN
2. LSTM
3. GRU
4. LSTM → GRU
5. GRU → LSTM
6. LSTM → LSTM → GRU

## Methodology
The workflow includes:
- Downloading historical stock market data using Yahoo Finance.
- Preparing and normalizing time series data.
- Creating input sequences using a 10-day look-back window.
- Training recurrent and hybrid neural network models.
- Evaluating predictions using Mean Absolute Error (MAE).
- Visualizing actual and predicted stock prices.

## Technologies & Libraries
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

## Repository Structure
```
google-stock-price-forecasting/
│
├── README.md
└── tamrin1.ipynb
```

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run the cells sequentially.

## Note
This project is an educational implementation focused on exploring and comparing recurrent and hybrid deep learning architectures for time series forecasting. The notebook uses the test period as validation data in model training and evaluation.

---

**Author:** Ayda Pirandakh
