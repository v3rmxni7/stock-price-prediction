# stock-price-prediction
# 📈 Nifty50 Stock Price Prediction (Random Forest)

This notebook predicts the closing prices of Nifty50 stocks (e.g., RELIANCE) using a Random Forest Regressor in Python.

## 📊 Features Used
- Open, High, Low, Volume
- 10-day & 20-day Simple Moving Averages (SMA)
- Daily % Returns

## ⚙️ Model
- Trained Random Forest Regressor from scikit-learn
- Evaluated using MSE and R² Score

## 📈 Output
- Line plot comparing Actual vs Predicted closing prices
- Test R² Score: ~0.998

## 📁 Files
- `nifty50_stock_price_prediction.ipynb`: Full notebook
- `actual_vs_predicted_rf.png`: Output plot

## 📝 Next Steps
- Add more features (RSI, EMA)
- Try LSTM / XGBoost
- Deploy using Streamlit or Flask
