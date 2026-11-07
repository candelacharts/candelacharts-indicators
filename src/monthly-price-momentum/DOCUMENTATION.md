# MONTHLY PRICE MOMENTUM

## 📝 Overview

Momentum tells you how fast price is traveling, not just where it is.

The **CandelaCharts – Monthly Price Momentum** is a Rate of Change (ROC%) oscillator over ~30 days (configurable), smoothed by EMA and colored with a readable blue→cyan gradient. A dashed **0 line** marks regime (positive/negative), and a solid **Upper Level** (default +30%) flags powerful upside bursts that often require caution.

## 📦 Features

Good momentum tools make speed obvious and decisions simple.

- **Monthly ROC% core**: `(Close − Close[n]) / Close[n] · 100` with `n≈30` days by default.
- **EMA smoothing**: Optional smoothing to tone down noise while preserving thrust.
- **Zero baseline**: Clear separator between positive and negative monthly momentum.
- **Upper threshold line**: User-set level (default +30%) to highlight overheated upside.
- **Adaptive gradient**: Dark blue (weak) → bright cyan (strong) for instant read of acceleration.
- **Polish controls**: Global font, text size, and branding toggle.

## ⚙️ Settings

Set levels that fit your asset, then let the math do the talking.

- **Lookback (days)** — *mpm_len_days*: Window for ROC% (e.g., 30 ≈ one month on Daily).
- **Smoothing** — *smoothLen*: EMA length applied to ROC%.
- **Upper Level** — *mpm_level_up*: Solid reference line for “overheated” reads (default +30%).

## ⚡️ Showcase

**Euphoria tags**: Pushes beyond +30% during blow-offs; annotate pullbacks after first cool-down.  
https://www.tradingview.com/x/elobqekJ/

**Capitulation zones**: Deep negatives (e.g., −20% or worse) near cycle lows.  
https://www.tradingview.com/x/7yzGv7HX/

## 📒 Usage

Think of it as a monthly speedometer: how fast, in which direction, and is it overheating?

### Read the gauges
- **Above 0** → positive momentum (price higher vs. ~30 days ago).
- **Below 0** → negative momentum (price lower vs. ~30 days ago).
- **Crossing 0** often marks the first shift in trend regime.

### Use the thresholds
- **+30% line**: Strong upside thrust; great for confirming breakouts, but also a caution/trim zone if momentum starts to cool.
- **Deep negatives (e.g., ≤ −20%)**: Panic/capitulation areas—watch for stabilization if the higher-timeframe trend is up.

## 🚨 Alerts

Currently, the script does not include built-in alerts.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
