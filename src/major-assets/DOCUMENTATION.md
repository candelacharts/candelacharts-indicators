# MAJOR ASSETS

## 📝 Overview

A clear way to compare how major assets performed since a common starting point.

The **CandelaCharts – Major Assets** indicator normalizes multiple markets to a base of 100 from a chosen date, so you can see relative performance at a glance. It supports equities (QQQ, SPY, ACWI), bonds (TLT, HYG, T-Bills), commodities (Gold, Oil), currencies (DXY), crypto (BTC, ETH), and US M2.

## 📦 Features

Built to reveal relative strength without clutter.

- **Indexed comparison**: All selected assets are rebased to 100 from your *From* date for clean, apples-to-apples performance.
- **Flexible universe**: Quick toggles for QQQ, SPY, ACWI, TLT, T-Bills (SGOV/BIL/SHV), HYG, GLD, USO, DXY, BTC, ETH, and US M2.
- **Base line**: Optional “Base = 100” reference to anchor crossovers and breakouts.
- **Smart labels**: Persistent end-of-series labels show latest index values (one label per enabled asset).
- **Custom styling**: Per-asset color pickers, global font and text sizing, optional brand mark.
- **Robust data handling**: Graceful behavior for symbols without full history (`ignore_invalid_symbol=true`).
- **Macro overlay**: US M2 included (monthly series will step on lower timeframes).

## ⚙️ Settings

- **From**: Start date used to set **Base = 100** for all enabled assets.
- **Show Base**: Toggle the horizontal “100” baseline.
- **Assets**:
  - QQQ (NASDAQ:QQQ) — NASDAQ-100
  - S&P 500 (AMEX:SPY) — US large caps
  - ACWI (NASDAQ:ACWI) — Global equities
  - TLT (NASDAQ:TLT) — US long Treasuries
  - T-Bills / Cash (AMEX:SGOV or BIL/SHV)
  - HYG (AMEX:HYG) — High yield bonds
  - GLD (AMEX:GLD) — Gold
  - USO (AMEX:USO) — Oil
  - DXY (TVC:DXY) — US Dollar Index
  - BTC (CME:BTC1!) — Bitcoin futures
  - ETH (CME:ETH1!) — Ethereum futures
  - US M2 (ECONOMICS:USM2) — Money supply (monthly)

## ⚡️ Showcase

Use these layouts as image examples to demonstrate what the tool reveals.

https://www.tradingview.com/x/O9dklC7E/

## 📒 Usage

Read the slope, watch the spreads, and let the base line organize the story.

- **Pick a regime start**: Set *From* to a cycle low/high or policy inflection to compare paths since that point.
- **Spot leadership**: The highest index line shows the current leader; widening gaps = stronger relative trend.
- **Use Base=100 crossovers**: Crosses back above 100 can mark regime change or post-drawdown recovery.
- **Mind M2 stepping**: M2 updates monthly; expect steps on lower TFs—use it as macro context, not a trading signal.
- **Style for clarity**: Assign contrasting colors and keep the universe small (3–6 lines) for readability.

## 🚨 Alerts

Currently, the script does not include built-in alerts.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
