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

## 📊 SMA Crossover Analysis Gallery

Below are the **SMA (Simple Moving Average) line charts** with technical crossover analysis for multiple stocks. Each chart shows the **20-day SMA** overlaid on the **closing price** from December 2025 to May 2026. Crossovers indicate potential buy/sell signals.

| Stock | Chart | Crossover Summary |
|-------|-------|-------------------|
| **AAPL** | ![AAPL](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis.png) | Bullish crossover in Jan 2026; bearish in Apr 2026. |
| **MSFT** | ![MSFT](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%202.png) | Price holds above SMA Jan–Mar, dips below in Apr, recovers sharply in May. |
| **AMZN** | ![AMZN](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%204.png) | Consistent above SMA until Mar, brief dip in Apr, then reversal. |
| **AVGO** | ![AVGO](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%206.png) | Downtrend from Jan to Apr; May close above SMA signals potential reversal. |
| *Other* | ![Chart1](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%201.png) | Sharp rise in Jan, then decline; May close above SMA. |
| *Other* | ![Chart2](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%203.png) | Deep dip in Apr, then strong bounce in May (bullish crossover). |
| *Other* | ![Chart3](images/Average%20%28SMA%29%20Line%20Chart%20with%20Technical%20Crossover%20Analysis%205.png) | High volatility; price recovers above SMA in May after Mar–Apr dip. |

> **Note:** SMA period used is 20 days (SMA20). Crossover signals are for educational purposes only.




