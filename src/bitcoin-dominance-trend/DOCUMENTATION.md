# BITCOIN DOMINANCE TREND

## 📝 Overview

The **CandelaCharts – Bitcoin Dominance Trend** indicator is a simple but powerful tool to track Bitcoin’s market dominance (BTC.D). It automatically pulls daily BTC dominance data, applies a moving average, and visually highlights important dominance zones.

This makes it easy to see whether Bitcoin is gaining or losing dominance over altcoins — a key factor in spotting shifts between Bitcoin-led rallies and altcoin seasons.

## 📦 Features

- Plots the daily BTC dominance line.
- Customizable moving average (MA) with multiple types (SMA, EMA, RMA, WMA, VWMA).
- Dynamic bullish/bearish line coloring depending on whether BTC.D is above or below its MA.
- Horizontal reference levels at 40%, 50%, and 65%.
- Clean background zones to quickly spot when BTC dominance is extreme (below 40% or above 65%).
- Automatic highlight marker whenever BTC dominance crosses below its moving average.

## ⚙️ Settings

- **Bullish Line Color** — Default green (dominance above MA).
- **Bearish Line Color** — Default red (dominance below MA).
- **MA Length** — Adjustable length for the moving average (5–200).
- **MA Type** — Choose from SMA, EMA, RMA, WMA, or VWMA.
- **MA Line Width** — Control the line thickness (0–5).
- **MA Line Color** — Default is a soft gray.
- **Symbol** — You can replace this with another dominance pair if needed.

## ⚡️ Showcase

https://www.tradingview.com/x/FrcuV1aw/

## 📒 Usage

Here’s how to read and use the indicator effectively:

### Dominance Levels
- **40%** — Often marks strong altcoin dominance.
- **50%** — Neutral midpoint, good for balance reference.
- **65%** — Signals Bitcoin over-dominance.

### Background Zones
- 🔴 **Below 40%** — Red background: altcoin season bias.
- ⚪ **Between 40–65%** — Gray background: neutral range.
- 🟢 **Above 65%** — Green background: Bitcoin leading strongly.

### Moving Average (MA)
- BTC.D is green when above the MA — bullish for Bitcoin dominance.
- BTC.D is red when below the MA — bearish for Bitcoin dominance.
- A circle marker appears when BTC.D crosses below the MA.

## 🔒 Proprietary Architecture & Closed-Source Rationale

This script is published as a public invite-only tool because it incorporates CandelaCharts' proprietary macro crypto capital rotation framework:

- **Non-Repainting Cross-Timeframe Sampling:** Formulated to sample daily market dominance (`CRYPTOCAP:BTC.D`) across any intraday or swing timeframe with strict historical non-repainting guarantees.
- **Capital Rotation Regime Modeling:** Synthesizes structural boundaries (40% altcoin expansion threshold vs. 65% Bitcoin liquidity drainage threshold) with multi-type moving averages (SMA, EMA, RMA, WMA, VWMA).
- **Visual State Filtering:** Dynamic background zone lighting and localized exhaustion markers flag critical macro regime pivots in real time.

## 🚨 Alerts

The indicator includes 4 built-in alert conditions for regime shifts:

- **BTC Dominance Cross Above MA:** Signals momentum favoring Bitcoin outperformance over altcoins.
- **BTC Dominance Cross Below MA:** Signals momentum favoring capital rotation into altcoins.
- **BTC Dominance Entered Extreme High (>65%):** Warns of extended Bitcoin market concentration.
- **BTC Dominance Entered Altseason Zone (<40%):** Signals broad altcoin market dominance.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
