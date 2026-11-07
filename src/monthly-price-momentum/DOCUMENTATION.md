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

*These tools are exclusively available on the TradingView platform.*

Our charting tools are intended solely for informational and educational purposes and should not be regarded as financial, investment, or trading advice. They are not designed to predict market movements or offer specific recommendations. Users should be aware that past performance is not indicative of future results and should not rely on these tools for financial decisions. By using these charting tools, the purchaser agrees that the seller and creator hold no responsibility for any decisions made based on information provided by the tools. The purchaser assumes full responsibility and liability for any actions taken and their consequences, including potential financial losses or investment outcomes that may result from the use of these products.

By purchasing, the customer acknowledges and accepts that neither the seller nor the creator is liable for any undesired outcomes stemming from the development, sale, or use of these products. Additionally, the purchaser agrees to indemnify the seller from any liability. If invited through the Friends and Family Program, the purchaser understands that any provided discount code applies only to the initial purchase of Candela's subscription. The purchaser is responsible for canceling or requesting cancellation of their subscription if they choose not to continue at the full retail price. In the event the purchaser no longer wishes to use the products, they must unsubscribe from the membership service, if applicable.

We do not offer reimbursements, refunds, or chargebacks. Once these Terms are accepted at the time of purchase, no reimbursements, refunds, or chargebacks will be issued under any circumstances.

By continuing to use these charting tools, the user confirms their understanding and acceptance of these Terms as outlined in this disclaimer.
