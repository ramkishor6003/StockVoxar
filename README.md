# StockVoxar
StockVoxar: An intelligent stock analysis tool with voice-based recommendations and interactive charts that combines technical indicators, risk metrics (VaR/CVaR), and news sentiment to generate automated BUY/SELL/HOLD signals.

## Key Features

### Voice-Based Analysis
- Text-to-speech (TTS) using`gTTS`
- Speaks out final recommendation with confidence level
- Custom voice alerts for **BUY/SELL/HOLD**

### Interactive Charts
- **Price & Moving Averages** (Candlestick or Line chart)
- **Volume Trend** with OBV overlay
- **Technical Indicators:** Stochastic K, Williams %R
- **Risk Dashboard:** VaR, CVaR, Volatility (Bar/Heatmap)
- Built with `matplotlib`, `plotly` (interactive hover)

### Other Features
- Technical scanner (Stoch K, Williams %R, SMA10/30)
- Risk metrics (VaR, CVaR, Sortino, Calmar, Max DD)
- News sentiment analysis (polarity, buzz)
- Volume trend & OBV momentum
- Automated **BUY/SELL/HOLD** with confidence score
- Supports any stock ticker (TSLA, AVGO, etc.)

## Tech Stack
- **Python** 3.8+
- **Data:** yfinance, pandas, numpy
- **Charts:** matplotlib, plotly, seaborn
- **Voice:** gTTS (online)
- **Sentiment:** TextBlob / FinBERT

Project Live Demo

Project live screen recording:



https://github.com/user-attachments/assets/82e2a787-dca7-4e38-affc-432177fdf535




