# Task 1 – Stock Price Prediction (Baladna)

This project is part of an internship task assigned by CodeAlpha. The objective was to predict stock prices using machine learning techniques with **Jupyter Notebook only**.

## 📈 Project Overview

- **Company Chosen**: Baladna (BLDN), a leading Qatari dairy company
- **Data Source**: [Investing.com](https://www.investing.com/equities/baladna-food-industries-co-historical-data)
- **Tools Used**: Python, Pandas, Matplotlib, Scikit-learn, TensorFlow (Keras)
- **Model**: Dense Neural Network (used to understand time series before applying LSTM)
- **Metrics**: Mean Absolute Error (MAE), plotted predictions

## 🧠 Key Steps

1. Preprocessed historical stock price data
2. Converted time series to supervised learning format using a windowing approach
3. Scaled features using MinMaxScaler
4. Built and trained a feedforward neural network
5. Evaluated performance on train/validation/test splits
6. Visualized predictions and analyzed results

## 💡 Learnings

- Importance of proper time-based splitting in time series
- Role of scaling in neural network performance
- Gained better understanding of data preparation before LSTM modeling

## 🔗 Notebook

You can find the complete notebook here:  
[Hassan_BLDNStockPrediction.ipynb](./Hassan_BLDNStockPrediction.ipynb)
