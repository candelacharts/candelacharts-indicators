# MVRV RATIO

## 📝 Overview

Valuation gets clearer when price is compared to what the market actually paid.

The **CandelaCharts – MVRV Ratio** plots on-chain **MVRV** (Market Value / Realized Value) for **BTC** or **ETH** using curated feeds, adds classic reference lines (3.5, 2.5, 1.0, 0.8), optional **σ bands** for context, and highlight zones to quickly spot historical euphoria and stress.

## 📦 Features

The goal is a readable, cycle-aware valuation gauge with minimal clutter.

- **Asset toggle**: Switch between **BTC** and **ETH** MVRV series.
- **Key references**: Lines at **3.5** (potential cycle tops), **2.5** (overvalued), **1.0** (fair value), **0.8** (potential bottoms).
- **Common zone shading**: Optional fill between **2.5 ↔ 1.0** to frame typical bull-market overvaluation.
- **Extreme zone highlights**: Background tint above **3.5** and below **0.8**.
- **σ Bands**: Dynamic **mean + 1σ** and **mean + 2σ** bands (adaptive to history length).
- **Cycle colors**: Automatic line coloring (blue above fair value, orange below).

## ⚙️ Settings

- **Assets**: Choose **BTC** or **ETH**.
- **σ Bands**: Show/Hide dynamic bands.
- **Bands Lookback**: Sample length for mean/stdev (default 200).
- **Show Extreme Zones**: Background highlight above 3.5 / below 0.8.
- **Show Common Zone**: Shading between 2.5 and 1.0.

## ⚡️ Showcase

**Cycle tops**: Annotate clusters above 3.5 with subsequent drawdowns.  
https://www.tradingview.com/x/Zp0pwtBr/

**Fair-value recapture**: Mark recoveries back through 1.0 after deep bear markets.  
https://www.tradingview.com/x/WCZwWi10/

## 📒 Usage

Treat MVRV as a cycle thermometer—confirm with price/structure before acting.

- **> 2.5**: Elevated risk of overheated conditions—tighten risk or stagger exits on weakness.
- **~ 1.0**: “Fair value” area—often a battleground during transitions.
- **< 0.8**: Historically stressed—scan for stabilization, higher lows, or breadth turns.
- **σ bands**: Use **mean+1σ/2σ** as adaptive context; a tag above 2σ amid weakening momentum often precedes cool-downs.
- **BTC vs. ETH**: ETH tends to show higher beta; interpret levels relative to its own history, not BTC’s.

## 🔒 Proprietary Architecture & Closed-Source Rationale

This script is published as a public invite-only tool because it incorporates CandelaCharts' proprietary on-chain data extrapolation architecture:

- **Real-Time Intraday Extrapolation:** On-chain metric feeds publish once daily upon blockchain settlement. CandelaCharts uses a real-time price scaling formula `MVRV_live = MVRV_baseline * (Price_live / Price_baseline)` to provide fluid, tick-by-tick valuation updates throughout intraday sessions.
- **Non-Repainting Multi-Timeframe Alignment:** Historical values strictly sample confirmed on-chain closes without lookahead bias, preventing artificial backtest distortion.
- **Adaptive σ Dispersion Bands:** Plots rolling standard deviation bands around on-chain mean valuation to account for structural cycle volatility shifts across halving regimes.

## ℹ️ Data Feed Requirements & Limitations

- **Supported Assets:** Supported for Bitcoin (BTC) and Ethereum (ETH) utilizing IntoTheBlock on-chain datasets.
- **Extrapolation Baseline:** Live intraday extrapolation leverages spot price feeds from Binance (`BTCUSDT` / `ETHUSDT`) with fallback to current chart close.
- **Data Settlement:** On-chain baseline updates reflect daily provider settlements; intraday fluctuations mirror spot asset movement relative to the most recent on-chain snapshot.

## 🚨 Alerts

Currently, the script does not include built-in alerts.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
