# MONTHLY PRICE MOMENTUM

 📝 [b]Overview[/b]

Momentum tells you how fast price is traveling, not just where it is.

The [b]CandelaCharts – Monthly Price Momentum[/b] is a Rate of Change (ROC%) oscillator over ~30 days (configurable), smoothed by EMA and colored with a readable blue→cyan gradient. A dashed [b]0 line[/b] marks regime (positive/negative), and a solid [b]Upper Level[/b] (default +30%) flags powerful upside bursts that often require caution.

 📦 [b]Features[/b]

Good momentum tools make speed obvious and decisions simple.
[list]
[*] [b]Monthly ROC% core[/b]: (Close − Close[n]) / Close[n] · 100 with n≈30 days by default.
[*] [b]EMA smoothing[/b]: Optional smoothing to tone down noise while preserving thrust.
[*] [b]Zero baseline[/b]: Clear separator between positive and negative monthly momentum.
[*] [b]Upper threshold line[/b]: User-set level (default +30%) to highlight overheated upside.
[*] [b]Adaptive gradient[/b]: Dark blue (weak) → bright cyan (strong) for instant read of acceleration.
[*] [b]Polish controls[/b]: Global font, text size, and branding toggle.
[/list]

 ⚙️ [b]Settings[/b]

Set levels that fit your asset, then let the math do the talking.
[list]
[*] [b]Lookback (days)[/b] — [i]mpm_len_days[/i]: Window for ROC% (e.g., 30 ≈ one month on Daily).
[*] [b]Smoothing[/b] — [i]smoothLen[/i]: EMA length applied to ROC%.
[*] [b]Upper Level[/b] — [i]mpm_level_up[/i]: Solid reference line for “overheated” reads (default +30%).
[/list]

 ⚡️ [b]Showcase[/b]

[b]Euphoria tags[/b]: Pushes beyond +30% during blow-offs; annotate pullbacks after first cool-down.
https://www.tradingview.com/x/elobqekJ/
[b]Capitulation zones[/b]: Deep negatives (e.g., −20% or worse) near cycle lows.
https://www.tradingview.com/x/7yzGv7HX/

 📒 [b]Usage[/b]

Think of it as a monthly speedometer: how fast, in which direction, and is it overheating?

[b]Read the gauges[/b]
[list]
[*] [b]Above 0[/b] → positive momentum (price higher vs. ~30 days ago).
[*] [b]Below 0[/b] → negative momentum (price lower vs. ~30 days ago).
[*] [b]Crossing 0[/b] often marks the first shift in trend regime.
[/list]
[b]Use the thresholds[/b]
[list]
[*] [b]+30% line[/b]: Strong upside thrust; great for confirming breakouts, but also a caution/trim zone if momentum starts to cool.
[*] [b]Deep negatives (e.g., ≤ −20%)[/b]: Panic/capitulation areas—watch for stabilization if the higher-timeframe trend is up.
[/list]

 🚨 [b]Alerts[/b]

Currently, the script does not include built-in alerts.

 ⚠️ [b]Disclaimer[/b]

[i]These tools are exclusively available on the TradingView platform.[/i]

Our charting tools are intended solely for informational and educational purposes and should not be regarded as financial, investment, or trading advice. They are not designed to predict market movements or offer specific recommendations. Users should be aware that past performance is not indicative of future results and should not rely on these tools for financial decisions. By using these charting tools, the purchaser agrees that the seller and creator hold no responsibility for any decisions made based on information provided by the tools. The purchaser assumes full responsibility and liability for any actions taken and their consequences, including potential financial losses or investment outcomes that may result from the use of these products.

By purchasing, the customer acknowledges and accepts that neither the seller nor the creator is liable for any undesired outcomes stemming from the development, sale, or use of these products. Additionally, the purchaser agrees to indemnify the seller from any liability. If invited through the Friends and Family Program, the purchaser understands that any provided discount code applies only to the initial purchase of Candela's subscription. The purchaser is responsible for canceling or requesting cancellation of their subscription if they choose not to continue at the full retail price. In the event the purchaser no longer wishes to use the products, they must unsubscribe from the membership service, if applicable.

We do not offer reimbursements, refunds, or chargebacks. Once these Terms are accepted at the time of purchase, no reimbursements, refunds, or chargebacks will be issued under any circumstances.

By continuing to use these charting tools, the user confirms their understanding and acceptance of these Terms as outlined in this disclaimer.








<!-- The Monthly Price Momentum indicator is essentially a Rate of Change (ROC%) oscillator calculated over ~30 days (1 month on a daily chart). It measures how fast price is changing relative to where it was one month ago.

So if the value = 20, price is 20% higher than 30 days ago.
If value = -10, price is 10% lower than 30 days ago.

📊 How to interpret

Zero Line (dashed line at 0)
Above 0 → positive momentum (price is rising vs. 30 days ago).
Below 0 → negative momentum (price is falling vs. 30 days ago).

Crossing zero is often the first sign of a trend shift.

Upper Threshold (solid white line at +30%)

Value above +30% → market is in strong upside momentum.
Often marks overheated or euphoric conditions. Historically, price struggles to sustain much higher than this without cooling down.
Can act as a take-profit / caution zone if you’re long.

Deep Negative Momentum (e.g., -20% or worse)

Suggests panic selling or capitulation.
Historically, those regions can align with buying opportunities, especially if the broader trend is bullish.

Gradient Color Line

Darker blue = weaker momentum
Lighter cyan = stronger momentum

Lets you quickly see acceleration or deceleration at a glance.

⚡ Practical Uses

Trend Confirmation → Use it as a filter: only take longs if momentum is above 0, shorts if momentum is below 0.
Overbought/Overheated Signal → Readings above +30 can warn of potential blow-off tops.
Capitulation / Value Zone → Very negative momentum can highlight bargain areas in strong uptrends.
Momentum Divergence → If price makes a new high but momentum doesn’t, it may foreshadow weakness.

👉 Think of it as a monthly speedometer for price:

0 = neutral,
+30 = speeding fast upward,
-20 or lower = slamming brakes. -->
