# SEQUENTIAL EXHAUSTION

📝 [b]Overview[/b]

The Sequential Exhaustion indicator is an oscillator inspired by the technical methodologies of Tom DeMark. It measures market demand by comparing intra-period price extremes to previous levels, helping traders identify overextended trends and potential reversal points.

Unlike many oscillators that rely solely on closing prices, this indicator focuses on price action at the margins (highs and lows), making it highly sensitive to true market exhaustion.

📦 [b]Features[/b]

[list]
[*] [b]High-Precision Divergences[/b]: Implements our advanced high-precision algorithm for identifying market exhaustion.
[*] [b]Visual Signal Hierarchy[/b]: Uses solid lines for extreme (OB/OS) divergences and dashed lines for neutral zone signals.
[*] [b]Triangle Markers[/b]: Clean, minimal triangle markers for immediate signal identification.
[*] [b]Dynamic Overbought/Oversold Zones[/b]: Visual levels at 0.7 and 0.3 with background shading.
[*] [b]Trend Midline[/b]: Includes a 0.5 midline to help gauge the overall market bias.
[*] [b]Momentum Radar[/b]: Dynamic background heat map that intensifies as price moves deeper into exhaustion zones.
[/list]

⚙️ [b]Settings[/b]

[list]
[*] [b]Calculation Period[/b]: The lookback window for the underlying exhaustion calculation (Default: 13).
[*] [b]Smoothing[/b]: Optional moving average to filter out market noise (Default: 1).
[*] [b]Overbought/Oversold Levels[/b]: Thresholds for price exhaustion (Default: 0.7/0.3).
[*] [b]Show Divergences[/b]: Toggle visibility of exhaustion signals.
[*] [b]Pivot Lookback[/b]: Sensitivity for pivot detection (Default: 5).
[*] [b]Colors[/b]: Customizable colors for bullish and bearish signals.
[*] [b]Show[/b]: Toggle the background exhaustion heat map.
[*] [b]OB/OS Depth[/b]: Controls the sensitivity and "depth" required to reach maximum visual intensity.
[/list]

⚡️ [b]Showcase[/b]

[i]Overbought Line at 0.7 and Oversold Line at 0.3[/i]
https://www.tradingview.com/x/5dWFAVNW/

[i]Divergences[/i]
https://www.tradingview.com/x/BkyN5HUp/

[i]Bar Coloring[/i]
https://www.tradingview.com/x/eKtTUydL/

[i]Momentum Radar[/i]
https://www.tradingview.com/x/nPoCl0D8/

📒 [b]Usage[/b]

To get the most out of the Sequential Exhaustion Oscillator, consider the following interpretive techniques:

[list]
[*] [b]Overbought/Oversold Reversals[/b]: When the line enters the [b]0.7 zone[/b], the market is overextended to the upside. Look for the line to cross back [i]below[/i] 0.7 as a potential sell signal. Conversely, when it enters the [b]0.3 zone[/b], it is oversold; a cross back [i]above[/i] 0.3 is a potential buy signal.
[*] [b]Divergence Analysis[/b]: High-probability setups occur when price makes a new high/low that is not confirmed by the oscillator. 
    - [b]Solid Lines[/b] (Extreme Zone): High-conviction signals suggesting imminent reversal.
    - [b]Dashed Lines[/b] (Neutral Zone): Signs of waning momentum, often leading to consolidation or minor pullbacks.
[*] [b]Regime Filter (0.5 Level)[/b]: The midline acts as a trend separator. If the oscillator is consistently holding above 0.5, the bullish momentum is dominant. Below 0.5 suggests a bearish regime.
[*] [b]Momentum Radar (Exhaustion Heat Map)[/b]: The background shading at the extreme top and bottom of the oscillator acts as a visual "heat map." As the oscillator moves further beyond the 0.7 or 0.3 levels, the background color becomes more opaque, signaling a high-conviction exhaustion zone where a reversal is highly probable.
[/list]

🚨 [b]Alerts[/b]

[list]
[*] [b]Bullish Divergence[/b]: Triggered when a new bullish divergence is confirmed.
[*] [b]Bearish Divergence[/b]: Triggered when a new bearish divergence is confirmed.
[*] [b]Cross Below Overbought[/b]: Triggers when the oscillator line crosses back below the 0.7 level.
[*] [b]Cross Above Oversold[/b]: Triggers when the oscillator line crosses back above the 0.3 level.
[/list]

⚠️ [b]Disclaimer[/b]

Trading involves significant risk, and many participants may incur losses. The content on this site is not intended as financial advice and should not be interpreted as such. Decisions to buy, sell, hold, or trade securities, commodities, or other financial instruments carry inherent risks and are best made with guidance from qualified financial professionals. Past performance is not indicative of future results.
