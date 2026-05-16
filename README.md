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

| Stock | Chart (Click to enlarge) | Crossover Summary & Key Levels |
|-------|--------------------------|--------------------------------|
| **AAPL** | ![AAPL](images/AAPL_SMA20.png) | **Bullish crossover** in Jan 2026 (262 > 275? Wait – price below SMA? Actually Jan: 262 vs 275 – no crossover. Let's re-analyze: Dec: 260 < 280, Jan: 262 < 275, Feb: 254 < 265, Mar: 258 < 270, Apr: 250 < 260, May: 255 < 265. Price always below SMA! So **no crossover** – bearish trend entire period. Summary: *Persistent bearish trend, price remains below SMA20.* |
| **MSFT** | ![MSFT](images/MSFT_SMA20.png) | Price holds above SMA Jan–Mar (315>310, 335>325, 305>300). Dips below in Apr (280<295). **Strong bullish crossover in May** (395 > 360). |
| **AVGO** | ![AVGO](images/AVGO_SMA20.png) | Downtrend from Jan to Apr (440→400, SMA 420→380). Price stays below SMA Feb–Apr. **May close (445) above SMA (390)** – potential bullish reversal. |
| **Unknown A** | ![UnknownA](images/UNKNOWN_A_SMA20.png) | Sharp rise in Jan (405→455, SMA 385→460 – price briefly above). Then decline below SMA Mar–Apr (400<410, 360<370). **May recovery** (445 > 390) – bullish crossover. |
| **Unknown B** | ![UnknownB](images/UNKNOWN_B_SMA20.png) | Price above SMA until Feb (315>310, 335>325). Dips below in Mar–Apr (305<300, 280<295). **Strong bounce in May** (395 > 360) – clear bullish crossover. |
| **Unknown C** | ![UnknownC](images/UNKNOWN_C_SMA20.png) | High volatility. Price above SMA Dec–Feb (590>580, 660>650, 670>640). Dips below Mar–Apr (650<660, 570<610). **May recovery** (620 > 645? Actually 620 < 645 – still below? Wait: May close 620, SMA 645 → still below! So **no crossover** yet, but narrowing gap.) |

> **Note:** SMA period used is 20 days (SMA20). All values based on provided data. Crossovers are for educational purposes only. Always confirm with real-time data before trading.




