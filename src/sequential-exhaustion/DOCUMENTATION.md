# SEQUENTIAL EXHAUSTION

## 📝 Overview

The Sequential Exhaustion indicator is an oscillator inspired by the technical methodologies of Tom DeMark. It measures market demand by comparing intra-period price extremes to previous levels, helping traders identify overextended trends and potential reversal points.

Unlike many oscillators that rely solely on closing prices, this indicator focuses on price action at the margins (highs and lows), making it highly sensitive to true market exhaustion.

## 📦 Features

- **High-Precision Divergences**: Implements our advanced high-precision algorithm for identifying market exhaustion.
- **Visual Signal Hierarchy**: Uses solid lines for extreme (OB/OS) divergences and dashed lines for neutral zone signals.
- **Triangle Markers**: Clean, minimal triangle markers for immediate signal identification.
- **Dynamic Overbought/Oversold Zones**: Visual levels at 0.7 and 0.3 with background shading.
- **Trend Midline**: Includes a 0.5 midline to help gauge the overall market bias.
- **Momentum Radar**: Dynamic background heat map that intensifies as price moves deeper into exhaustion zones.

## ⚙️ Settings

- **Calculation Period**: The lookback window for the underlying exhaustion calculation (Default: 13).
- **Smoothing**: Optional moving average to filter out market noise (Default: 1).
- **Overbought/Oversold Levels**: Thresholds for price exhaustion (Default: 0.7/0.3).
- **Show Divergences**: Toggle visibility of exhaustion signals.
- **Pivot Lookback**: Sensitivity for pivot detection (Default: 5).
- **Colors**: Customizable colors for bullish and bearish signals.
- **Show**: Toggle the background exhaustion heat map.
- **OB/OS Depth**: Controls the sensitivity and "depth" required to reach maximum visual intensity.

## ⚡️ Showcase

*Overbought Line at 0.7 and Oversold Line at 0.3*  
https://www.tradingview.com/x/5dWFAVNW/

*Divergences*  
https://www.tradingview.com/x/BkyN5HUp/

*Bar Coloring*  
https://www.tradingview.com/x/eKtTUydL/

*Momentum Radar*  
https://www.tradingview.com/x/nPoCl0D8/

## 📒 Usage

To get the most out of the Sequential Exhaustion Oscillator, consider the following interpretive techniques:

- **Overbought/Oversold Reversals**: When the line enters the **0.7 zone**, the market is overextended to the upside. Look for the line to cross back *below* 0.7 as a potential sell signal. Conversely, when it enters the **0.3 zone**, it is oversold; a cross back *above* 0.3 is a potential buy signal.
- **Divergence Analysis**: High-probability setups occur when price makes a new high/low that is not confirmed by the oscillator.
  - **Solid Lines** (Extreme Zone): High-conviction signals suggesting imminent reversal.
  - **Dashed Lines** (Neutral Zone): Signs of waning momentum, often leading to consolidation or minor pullbacks.
- **Regime Filter (0.5 Level)**: The midline acts as a trend separator. If the oscillator is consistently holding above 0.5, the bullish momentum is dominant. Below 0.5 suggests a bearish regime.
- **Momentum Radar (Exhaustion Heat Map)**: The background shading at the extreme top and bottom of the oscillator acts as a visual "heat map." As the oscillator moves further beyond the 0.7 or 0.3 levels, the background color becomes more opaque, signaling a high-conviction exhaustion zone where a reversal is highly probable.

## 🚨 Alerts

- **Bullish Divergence**: Triggered when a new bullish divergence is confirmed.
- **Bearish Divergence**: Triggered when a new bearish divergence is confirmed.
- **Cross Below Overbought**: Triggers when the oscillator line crosses back below the 0.7 level.
- **Cross Above Oversold**: Triggers when the oscillator line crosses back above the 0.3 level.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
