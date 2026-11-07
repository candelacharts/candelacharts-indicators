# MAYER MULTIPLE Z-SCORE

## 📝 Overview

Markets swing around their long-term mean; this tool quantifies that “distance” so you can read stretch, mean reversion, and risk quickly.

The **CandelaCharts – Mayer Multiple Z-Score** takes the classic Mayer Multiple (price ÷ long-term SMA) and maps it into a standardized **Z-Score**. You set the “undervalue” and “overvalued” thresholds (e.g., 0.5 and 2.0× the SMA), and the script linearly maps them to **−3σ … +3σ**. A smoothed Z-Score EMA helps with regime reads, optional fills highlight extremes, and an optional bar-color gradient conveys heat at a glance.

## 📦 Features

Good signals come from clear math and consistent scaling; here’s what you get.

- **Mayer Multiple → Z-Score**: Transforms price/SMA into a standardized scale (−3 to +3), anchored by your custom “undervalue/overvalued” thresholds.
- **Cumulative-to-rolling SMA**: The SMA grows from the first bar until the full length, then behaves like a classic rolling SMA—no tricks, no repaint.
- **Smoothing layer**: An EMA of the Z-Score (*IT_ZScore*) for cleaner trend/regime detection.
- **Extreme bands**: Optional fills for [+2..+3] and [−3..−2] highlight “stretch” zones visually.
- **Heat gradient**: Optional bar coloring based on Z-Score (blue → neutral → orange).
- **Clean UI controls**: Font family/size and branding toggle to match your chart style.

## ⚙️ Settings

Tune these once to match your asset’s volatility and your horizon.

- **Price SMA Length** (*mmz_psma_length*): Long-term baseline (commonly 200). Uses a cumulative-to-rolling SMA.
- **Z-Score EMA Length** (*mmz_it_len*): Smoothing for the Z-Score (trend clarity).
- **Threshold** (*mmz_overvalued*): The “top band” Mayer Multiple (e.g., 2.0×) mapped to [+3σ].
- **Undervalue** (*mmz_undervalue*): The “bottom band” Multiple (e.g., 0.5×) mapped to [−3σ].
- **Fill Extremities** (*mmz_extremities_bg*): Shade the [+2..+3] and [−3..−2] zones.
- **Bar Color** (*mmz_bar_color*): Color bars by Z-Score gradient for quick heat reading.

## ⚡️ Showcase

**Cycle heat**: BTC on Daily with 200 SMA; orange clusters above +2σ during blow-offs; blue below −2σ near capitulation.  
https://www.tradingview.com/x/5wApOKxD/

## 📒 Usage

Turn standardized stretch into a playbook—measure, don’t guess.

- **Start with defaults**: SMA=200, Undervalue=0.5, Threshold=2.0, Z-Score EMA=14. These map 0.5×→−3σ, 2.0×→+3σ.
- **Interpret bands**:
  - **±1σ**: Normal fluctuation—trend following works best here.
  - **+2..+3σ**: Overheated—consider trims, hedges, or tight risk if momentum wanes.
  - **−3..−2σ**: Deep discount—watch for stabilization/structure before scaling in.
- **Use the EMA as a regime lens**: Trade with the Z-Score EMA side (above 0 = positive stretch bias; below 0 = negative).
- **Tune thresholds to asset class**: Raise “Threshold” for high-vol assets (crypto), lower it for defensives; keep the 6σ span intact for comparability.
- **Avoid chasing edges**: Extremes cluster—wait for a **re-entry** back inside ±2σ or an EMA turn for better timing.

## 🚨 Alerts

Currently, the script does not include built-in alerts.

## ⚠️ Disclaimer

This tool is provided for informational and educational purposes only and does not constitute financial, investment, or trading advice. It is not designed to predict market movements or provide specific trading recommendations.

Trading and investing in financial markets carry substantial risk and can result in the loss of capital. Past performance is not indicative of future results. Any decisions made based on the information, calculations, or signals provided by this tool are solely the user's responsibility. CandelaCharts and its contributors assume no liability for any financial losses or damages resulting from the use of this indicator. Always perform your own research and consult with a licensed financial professional before making financial decisions.
