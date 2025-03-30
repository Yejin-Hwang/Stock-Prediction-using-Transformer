# Stock Prediction Using Transformer

## Overview

Stock price forecasting remains a challenging task due to the volatility of financial markets and the complex, nonlinear patterns in historical data. This study investigates whether cutting-edge AI models can outperform traditional statistical methods in predicting stock prices, with a focus on **closing price prediction**, a key market indicator.

Using real-world stock data collected from Yahoo Finance for major companies like **Tesla** and **Nvidia**, we compare three models:

- **ARIMA** (traditional statistical model)
- **TimesFM** (Google's Transformer-based model)
- **Chronos-T5** (Amazon's Transformer-based model)

## Evaluation Metrics

The models are evaluated using:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## Key Findings

- Deep learning models, particularly **Chronos-T5**, significantly outperform ARIMA.
- Chronos-T5 captures **long-term dependencies** and **complex market behaviors** better than ARIMA.
- Transformer-based models are more effective in handling stock market volatility.

## Future Work

- Incorporating **sentiment analysis** (e.g., news headlines, tweets)
- Exploring **ensemble methods** to improve robustness and accuracy
- Experimenting with other financial indicators beyond closing prices

---

## 🚀 Suggested Additions for README

You can consider adding these sections:

1. **Project Structure**
   ```markdown
   ## Project Structure
   - `data/`: Raw and preprocessed stock data
   - `models/`: Model training and evaluation scripts
   - `notebooks/`: Jupyter notebooks for EDA and results visualization
   - `results/`: Plots and performance metrics
