# Task 1 – Stock Price Prediction (Baladna)

This project is part of an internship task assigned by CodeAlpha. The objective was to predict stock prices using an **LSTM model in Jupyter Notebook**.

## 📈 Project Overview

- **Company Chosen**: Baladna (BLDN), a leading Qatari dairy company
- **Data Source**: [Investing.com](https://www.investing.com/equities/baladna-food-industries-co-historical-data)
- **Tools Used**: Python, Pandas, Matplotlib, Scikit-learn, TensorFlow (Keras)
- **Model**: LSTM Neural Network
- **Metrics**: Mean Absolute Error (MAE), plotted predictions

## 🧠 Key Steps

1. Preprocessed historical stock price data
2. Converted time series to supervised learning format using a windowing approach
3. Scaled features using MinMaxScaler
4. Reshaped inputs to 3D for LSTM compatibility
5. Built and trained an LSTM model
6. Evaluated performance on train/validation/test splits
7. Visualized predictions and analyzed results

## 💡 Learnings

- LSTMs are powerful for modeling sequences and patterns in time series
- Proper time-based data splitting improves model reliability
- Scaling and reshaping are critical steps before feeding data to LSTM

## 🔗 Notebook

You can find the complete notebook here:  
[Hassan_BLDNStockPrediction.ipynb](./Hassan_BLDNStockPrediction.ipynb)
