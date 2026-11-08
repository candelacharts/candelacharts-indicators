# CandelaCharts Indicators

A curated suite of institutional-grade technical analysis indicators, macroeconomic liquidity trackers, and cycle valuation models built for [TradingView](https://www.tradingview.com/) in **Pine Script v6**.

Developed and maintained by **CandelaCharts**.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Indicator Catalog](#indicator-catalog)
- [Installation & Usage](#installation--usage)
- [License](#license)

---

## Overview

The **CandelaCharts Indicators** repository provides a comprehensive toolkit for traders, quantitative analysts, and macro investors. Each indicator is crafted with:

- **Mathematical Rigor**: Robust formulations (logarithmic returns, standardized Z-Scores, on-chain cost basis modeling, and macroeconomic aggregations).
- **Modern Pine Script v6**: High-performance, non-repainting scripts adhering to the latest TradingView standards.
- **Adaptive Visuals**: Dynamic color gradients, background heatmaps, automatic chart theme detection (dark/light), and configurable watermark branding.
- **Actionable Signals**: Built-in visual signal hierarchies, threshold alerts, and concise inline metric tables.

---

## Indicator Catalog

| Indicator | Category | Key Metrics & Concepts | Source | Documentation |
| :--- | :--- | :--- | :--- | :--- |
| **ATH Drawdown** | Cycle / Risk | Running ATH % distance, risk bands, capitulation alert (−70% to −80%) | [`ath-drawdown.pine`](src/ath-drawdown/ath-drawdown.pine) | [Docs](src/ath-drawdown/DOCUMENTATION.md) |
| **Bitcoin Dominance Trend** | Trend / Dominance | BTC.D tracking, multi-type MA trend filter, 40%/50%/65% rotation zones | [`bitcoin-dominance-trend.pine`](src/bitcoin-dominance-trend/bitcoin-dominance-trend.pine) | [Docs](src/bitcoin-dominance-trend/DOCUMENTATION.md) |
| **Bitcoin Realized Price Bands** | On-Chain / Valuation | Realized Price multiples, MVRV oscillator, cycle tops & bottoms | [`bitcoin-realized-price-bands.pine`](src/bitcoin-realized-price-bands/bitcoin-realized-price-bands.pine) | [Docs](src/bitcoin-realized-price-bands/DOCUMENTATION.md) |
| **Global M2** | Macro Liquidity | Multi-nation M2 aggregate (19 economies in USD), YoY growth % | [`global-m2.pine`](src/global-m2/global-m2.pine) | [Docs](src/global-m2/DOCUMENTATION.md) |
| **Major Assets** | Cross-Asset / Relative Strength | Rebased performance (Base = 100), equities, bonds, crypto, commodities | [`major-assets.pine`](src/major-assets/major-assets.pine) | [Docs](src/major-assets/DOCUMENTATION.md) |
| **Mayer Multiple Z-Score** | Mean Reversion / Valuation | Normalized Z-Score (−3σ to +3σ) of Mayer Multiple, regime EMA | [`mayer-multiple-z-score.pine`](src/mayer-multiple-z-score/mayer-multiple-z-score.pine) | [Docs](src/mayer-multiple-z-score/DOCUMENTATION.md) |
| **Momentum Pulse** | Trend / Momentum | Log-return momentum, adaptive standard-deviation bands (±k·σ), context MAs | [`momentum-pulse.pine`](src/momentum-pulse/momentum-pulse.pine) | [Docs](src/momentum-pulse/DOCUMENTATION.md) |
| **Monthly Price Momentum** | Momentum / Oscillator | ~30-day Rate of Change (ROC%), EMA smoothing, overheat levels | [`monthly-price-momentum.pine`](src/monthly-price-momentum/monthly-price-momentum.pine) | [Docs](src/monthly-price-momentum/DOCUMENTATION.md) |
| **MVRV Ratio** | On-Chain / Valuation | BTC/ETH on-chain MVRV, cycle top/bottom levels, dynamic ±σ dispersion bands | [`mvrv-ratio.pine`](src/mvrv-ratio/mvrv-ratio.pine) | [Docs](src/mvrv-ratio/DOCUMENTATION.md) |
| **Sequential Exhaustion** | Reversal / Oscillator | DeMark-inspired exhaustion, intra-period margin tests, divergences | [`sequential-exhaustion.pine`](src/sequential-exhaustion/sequential-exhaustion.pine) | [Docs](src/sequential-exhaustion/DOCUMENTATION.md) |

---

## Installation & Usage

### Adding an Indicator to TradingView

1. Navigate to the indicator's folder under [`src/`](src/) (e.g., [`src/ath-drawdown/`](src/ath-drawdown/)).
2. Open the `.pine` file (e.g., `ath-drawdown.pine`) and copy its entire contents.
3. Open [TradingView](https://www.tradingview.com/) and load any chart.
4. Click on the **Pine Editor** tab at the bottom of the screen.
5. Create a new script, paste the copied code, and click **Save**.
6. Click **Add to chart**.

### Customizing Settings

Each indicator includes intuitive input categories accessible via the gear icon (**Settings**) on the chart:
- **General / Brand:** Toggle the CandelaCharts watermark, select typography (UI vs. Monospace), and adjust label sizes.
- **Settings / Inputs:** Adjust calculation periods, smoothing lengths, standard deviation multipliers, and reference thresholds.
- **Alerts:** Add native TradingView alerts using the indicator's alert conditions (e.g., cycle capitulation, divergence triggers, threshold crosses).

---

## License

This source code is licensed under the **Mozilla Public License 2.0 (MPL-2.0)**.  
See individual source file headers for license notices.

© **CandelaCharts**. All rights reserved.
