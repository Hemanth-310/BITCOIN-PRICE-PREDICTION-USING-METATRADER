# 📊 MT5 Trading Dashboard

## 🚀 Overview

This MetaTrader 5 Trading Dashboard is a powerful Streamlit application that provides comprehensive trading analytics, real-time market insights, and machine learning-powered price predictions.

![Dashboard Preview](https://mql5.com/assets/icons/mt5-brand2020.svg)

## ✨ Features

### 1. Market Overview 📈
- Real-time candlestick charts
- Latest price data
- Average True Range (ATR) calculation
- Running and closed trades tracking

### 2. Account Information 💰
- Balance and equity tracking
- Margin details
- Profit/Loss metrics
- Equity curve visualization

### 3. Machine Learning Predictions 🤖
- Neural network-based price prediction
- Model performance metrics
- Trading signal recommendations
- Stop loss and take profit suggestions

## 🛠 Prerequisites

### Required Libraries
- streamlit
- pandas
- numpy
- matplotlib
- mplfinance
- MetaTrader5
- scikit-learn
- tensorflow
- plotly

### Python Version
- Python 3.8+

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mt5-trading-dashboard.git
cd mt5-trading-dashboard
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 🚦 Usage

1. Start the Streamlit application:
```bash
streamlit run mt5_dashboard.py
```

2. In the sidebar, enter your MetaTrader 5 credentials:
- Account Number
- Password
- Server
- Symbol (e.g., BTCUSDm)
- Timeframe
- Number of bars to analyze

3. Click "Connect to MT5"

## 🔬 Machine Learning Model

### Model Architecture
- Input Layer: 128 neurons with ReLU activation
- Batch Normalization
- Dropout (20%)
- Hidden Layers: 64 and 32 neurons with ReLU activation
- Output Layer: Single neuron for price prediction

### Training Process
- Uses Exponential Learning Rate Decay
- Early Stopping
- Reduce Learning Rate on Plateau
- Huber Loss Function
- Mean Absolute Error Metric

## 📊 Performance Metrics

The ML model provides:
- Mean Squared Error (MSE)
- R² Score
- Actual vs. Predicted Price Comparison
- Trading Signals (Buy/Sell)

## 🔒 Security Notes

- Securely handle MT5 credentials
- Implement additional authentication if required
- Use environment variables for sensitive information

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Disclaimer

Trading involves financial risk. This dashboard is for educational and analytical purposes. Always conduct your own research and consult financial advisors before making trading decisions.

## 📞 Support

For issues or questions, please open a GitHub issue or contact the repository maintainer.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

🌟 Star this repository if you find it helpful!
