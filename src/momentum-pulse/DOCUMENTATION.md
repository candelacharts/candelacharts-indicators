# MOMENTUM PULSE

## 📝 Overview

Momentum only matters when it’s measurable—this tool turns raw swings into a readable pulse.

The **CandelaCharts – Momentum Pulse** computes a log-return–based momentum over a configurable length, colors it with an adaptive gradient (±k·σ), and optionally shows fixed levels (±L1/±L2) with shaded zones and a zero-line for quick regime reads. Two optional MAs (price vs. smoothed source) provide context.

## 📦 Features

Clarity comes from clean inputs, adaptive scaling, and simple visuals.

- **Log-momentum core**: `mom = ln(src / src[length]) · 100` for robust, scale-free momentum.
- **Adaptive gradient**: Color range auto-sets to ±(k × stdev(mom,length)) for consistent heat across assets/TFs.
- **Practical levels**: Toggle ±Level 1 / ±Level 2 and optionally shade inner/outer zones.
- **Zero baseline**: A persistent 0-line to separate positive/negative momentum regimes.
- **Context MAs**: “Normal MA” (`SMA(close,len)`) and “Smoothed MA” (`SMA(src,len)`) plotted in the same pane.

## ⚙️ Settings

Set these once to fit your volatility profile and reading style.

- **Length** (*mp_lnt*): Lookback for momentum & context MAs (default 21).
- **Level 1 (±)** (*mp_lvl1*): Inner threshold (e.g., 25).
- **Level 2 (±)** (*mp_lvl2*): Outer threshold (e.g., 50).
- **Multiplier** (*mp_grad_sigma_k*): Gradient span = ±(k × stdev); raise for calmer assets, lower for high-vol.
- **Show Levels** (*mp_show_lvls*): Toggle plotting of ±L1/±L2 lines.
- **Shade Inner Zone** (*mp_shade_inner*): Fill between −L1 and +L1.
- **Shade Outer Zone** (*mp_shade_outer*): Fill between +L1..+L2 and −L2..−L1.

## ⚡️ Showcase

## 📒 Usage

Turn the pulse into a checklist—setup, read, act.

### Read the pulse
- **Above 0** = positive momentum regime; **below 0** = negative regime.
- **Inside ±L1** = normal noise; **beyond ±L2** = exceptional impulse.
- Use gradient strength (deeper colors) to gauge conviction/velocity.

### Trade ideas
- **Breakout follow**: Enter/add on momentum crossing +L1 after a base; partials near +L2 unless trend is accelerating.
- **Mean reversion**: Fade back toward 0 when momentum exits extreme zones (+L2→inside or −L2→inside) and price confirms.
- **Regime filter**: Only take longs while momentum spends most time >0 (and vice versa for shorts).

### Calibration tips
- Increase **Length** to smooth choppy assets; decrease for faster signals.
- Raise **k** if the gradient looks “always hot”; lower if too muted.
- Tune **L1/L2** so that L2 captures true thrusts without firing constantly.

## 🚨 Alerts

Currently, the script does not include built-in alerts.

## ⚠️ Disclaimer

*These tools are exclusively available on the TradingView platform.*

Our charting tools are intended solely for informational and educational purposes and should not be regarded as financial, investment, or trading advice. They are not designed to predict market movements or offer specific recommendations. Users should be aware that past performance is not indicative of future results and should not rely on these tools for financial decisions. By using these charting tools, the purchaser agrees that the seller and creator hold no responsibility for any decisions made based on information provided by the tools. The purchaser assumes full responsibility and liability for any actions taken and their consequences, including potential financial losses or investment outcomes that may result from the use of these products.

By purchasing, the customer acknowledges and accepts that neither the seller nor the creator is liable for any undesired outcomes stemming from the development, sale, or use of these products. Additionally, the purchaser agrees to indemnify the seller from any liability. If invited through the Friends and Family Program, the purchaser understands that any provided discount code applies only to the initial purchase of Candela's subscription. The purchaser is responsible for canceling or requesting cancellation of their subscription if they choose not to continue at the full retail price. In the event the purchaser no longer wishes to use the products, they must unsubscribe from the membership service, if applicable.

We do not offer reimbursements, refunds, or chargebacks. Once these Terms are accepted at the time of purchase, no reimbursements, refunds, or chargebacks will be issued under any circumstances.

By continuing to use these charting tools, the user confirms their understanding and acceptance of these Terms as outlined in this disclaimer.
