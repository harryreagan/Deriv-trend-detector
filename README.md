# Deriv Trend Detector PRO

A robust and highly accurate TradingView Pine Script indicator built specifically for identifying and trading trends on Deriv synthetics and forex markets, optimized for the 1-hour timeframe.

## Features

- **Multi-Timeframe (MTF) Trend Filtering:** Uses a 4H EMA 50 filter to ensure trades are taken in the direction of the macro trend.
- **Trend Detection:** Based on EMA 20 and EMA 50 crossovers to identify clear bullish and bearish trends.
- **Momentum Filter:** Uses RSI (Relative Strength Index) to avoid entering overbought or oversold conditions prematurely.
- **MACD Triggers:** Precise entry signals based on MACD histogram crossovers.
- **Volatility & Risk Management:** Dynamic Stop Loss (SL) and Take Profit (TP) calculations based on ATR (Average True Range).
- **Signal Filtering:** Noise reduction features to prevent false signals, allowing only the first signal in a trend direction and requiring a minimum gap between signals.
- **Visual Dashboard:** An integrated on-chart table displaying real-time metrics (4H trend, RSI, Volatility, Alert Mode, etc.).
- **Smart Alerts:** 
  - **PRO Signals:** High-probability alerts matching all strict criteria.
  - **Aggressive Alerts:** Early entry MACD crossover alerts for more aggressive traders.

## Settings

- **Trend Settings:** Adjust EMA lengths and toggle the 4H higher timeframe filter.
- **Noise Reduction:** Set minimum bars between signals and toggle aggressive MACD cross alerts.
- **Momentum:** Customize RSI lengths and buy/sell levels.
- **Risk Management:** Adjust ATR periods and multipliers for your Stop Loss and Take Profit levels.
- **Visuals:** Toggle SL/TP lines, background coloring, vertical signal lines, and timeframe warnings.

## Installation

1. Open [TradingView](https://www.tradingview.com/).
2. Go to the **Pine Editor** tab at the bottom of the screen.
3. Open a new blank indicator.
4. Copy and paste the entire code from `deriv_trend_detector.pine` into the editor.
5. Click **Save** and then **Add to Chart**.

## Optimal Usage

- **Recommended Timeframe:** 1 Hour (1H).
- **Markets:** Works exceptionally well on Deriv Synthetic Indices (e.g., Boom, Crash, Step Index, Volatility Indices) and Forex pairs.
- **Alert Setup:** Create an alert on the indicator and select "Any alert() function call" to receive notifications based on your chosen mode (PRO or Aggressive).

## Disclaimer

This indicator is for educational and informational purposes only. It does not constitute financial advice. Always backtest strategies and practice proper risk management before trading with real capital.
