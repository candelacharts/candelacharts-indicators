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

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
