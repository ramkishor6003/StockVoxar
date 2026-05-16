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

| Stock Ticker | SMA Crossover Chart | Crossover Signal |
| :--- | :--- | :--- |

| **AAPL** | ![AAPL Chart] (<img width="1000" height="500" alt="AAPL_SMA20_crossover" src="https://github.com/user-attachments/assets/c3d57211-1632-4a7a-832c-0eb8d2b081bd" />) | Bearish crossover in April |

<img width="1000" height="500" alt="TSLA_SMA20_crossover" src="https://github.com/user-attachments/assets/dca909db-d271-425b-9158-6eef7fe6109e" />


<img width="1000" height="500" alt="AMZN_SMA20_crossover" src="https://github.com/user-attachments/assets/80d35b8c-1e34-4b33-a579-539f1009b112" />

<img width="1000" height="500" alt="MSFT_SMA20_crossover" src="https://github.com/user-attachments/assets/969b8ee4-b201-4abe-adab-e70633602938" />


<img width="1000" height="500" alt="GOOGL_SMA20_crossover" src="https://github.com/user-attachments/assets/6b5f24d5-536a-470d-9022-3c3957674046" />

<img width="1000" height="500" alt="META_SMA20_crossover" src="https://github.com/user-attachments/assets/b3f8c80c-c16a-4bfe-9883-acb428f5e2bb" />


<img width="1000" height="500" alt="AVGO_SMA20_crossover" src="https://github.com/user-attachments/assets/d5ce13cf-4e53-4b32-ab5d-836c99114aa8" />










