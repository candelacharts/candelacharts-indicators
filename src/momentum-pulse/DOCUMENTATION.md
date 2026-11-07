# MOMENTUM PULSE

 📝 [b]Overview[/b]

Momentum only matters when it’s measurable—this tool turns raw swings into a readable pulse.

The [b]CandelaCharts – Momentum Pulse[/b] computes a log-return–based momentum over a configurable length, colors it with an adaptive gradient (±k·σ), and optionally shows fixed levels (±L1/±L2) with shaded zones and a zero-line for quick regime reads. Two optional MAs (price vs. smoothed source) provide context.

 📦 [b]Features[/b]

Clarity comes from clean inputs, adaptive scaling, and simple visuals.
[list]
[*] [b]Log-momentum core[/b]: mom = ln(src / src[length]) · 100 for robust, scale-free momentum.
[*] [b]Adaptive gradient[/b]: Color range auto-sets to ±(k × stdev(mom,length)) for consistent heat across assets/TFs.
[*] [b]Practical levels[/b]: Toggle ±Level 1 / ±Level 2 and optionally shade inner/outer zones.
[*] [b]Zero baseline[/b]: A persistent 0-line to separate positive/negative momentum regimes.
[*] [b]Context MAs[/b]: “Normal MA” (SMA(close,len)) and “Smoothed MA” (SMA(src,len)) plotted in the same pane.
[/list]

 ⚙️ [b]Settings[/b]
Set these once to fit your volatility profile and reading style.
[list]
[*] [b]Length[/b] ([i]mp_lnt[/i]): Lookback for momentum & context MAs (default 21).
[*] [b]Level 1 (±)[/b] ([i]mp_lvl1[/i]): Inner threshold (e.g., 25).
[*] [b]Level 2 (±)[/b] ([i]mp_lvl2[/i]): Outer threshold (e.g., 50).
[*] [b]Multiplier[/b] ([i]mp_grad_sigma_k[/i]): Gradient span = ±(k × stdev); raise for calmer assets, lower for high-vol.
[*] [b]Show Levels[/b] ([i]mp_show_lvls[/i]): Toggle plotting of ±L1/±L2 lines.
[*] [b]Shade Inner Zone[/b] ([i]mp_shade_inner[/i]): Fill between −L1 and +L1.
[*] [b]Shade Outer Zone[/b] ([i]mp_shade_outer[/i]): Fill between +L1..+L2 and −L2..−L1.
[/list]

 ⚡️ [b]Showcase[/b]

 📒 [b]Usage[/b]

Turn the pulse into a checklist—setup, read, act.
[b]Read the pulse[/b]
[list]
[*] [b]Above 0[/b] = positive momentum regime; [b]below 0[/b] = negative regime.
[*] [b]Inside ±L1[/b] = normal noise; [b]beyond ±L2[/b] = exceptional impulse.
[*] Use gradient strength (deeper colors) to gauge conviction/velocity.
[/list]
[b]Trade ideas[/b]
[list]
[*] [b]Breakout follow[/b]: Enter/add on momentum crossing +L1 after a base; partials near +L2 unless trend is accelerating.
[*] [b]Mean reversion[/b]: Fade back toward 0 when momentum exits extreme zones (+L2→inside or −L2→inside) and price confirms.
[*] [b]Regime filter[/b]: Only take longs while momentum spends most time >0 (and vice versa for shorts).
[/list]
[b]Calibration tips[/b]
[list]
[*] Increase [b]Length[/b] to smooth choppy assets; decrease for faster signals.
[*] Raise [b]k[/b] if the gradient looks “always hot”; lower if too muted.
[*] Tune [b]L1/L2[/b] so that L2 captures true thrusts without firing constantly.
[/list]

 🚨 [b]Alerts[/b]

Currently, the script does not include built-in alerts.

 ⚠️ [b]Disclaimer[/b]

[i]These tools are exclusively available on the TradingView platform.[/i]

Our charting tools are intended solely for informational and educational purposes and should not be regarded as financial, investment, or trading advice. They are not designed to predict market movements or offer specific recommendations. Users should be aware that past performance is not indicative of future results and should not rely on these tools for financial decisions. By using these charting tools, the purchaser agrees that the seller and creator hold no responsibility for any decisions made based on information provided by the tools. The purchaser assumes full responsibility and liability for any actions taken and their consequences, including potential financial losses or investment outcomes that may result from the use of these products.

By purchasing, the customer acknowledges and accepts that neither the seller nor the creator is liable for any undesired outcomes stemming from the development, sale, or use of these products. Additionally, the purchaser agrees to indemnify the seller from any liability. If invited through the Friends and Family Program, the purchaser understands that any provided discount code applies only to the initial purchase of Candela's subscription. The purchaser is responsible for canceling or requesting cancellation of their subscription if they choose not to continue at the full retail price. In the event the purchaser no longer wishes to use the products, they must unsubscribe from the membership service, if applicable.

We do not offer reimbursements, refunds, or chargebacks. Once these Terms are accepted at the time of purchase, no reimbursements, refunds, or chargebacks will be issued under any circumstances.

By continuing to use these charting tools, the user confirms their understanding and acceptance of these Terms as outlined in this disclaimer.
