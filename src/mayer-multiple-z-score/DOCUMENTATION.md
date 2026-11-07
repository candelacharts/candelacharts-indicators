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

*These tools are exclusively available on the TradingView platform.*

Our charting tools are intended solely for informational and educational purposes and should not be regarded as financial, investment, or trading advice. They are not designed to predict market movements or offer specific recommendations. Users should be aware that past performance is not indicative of future results and should not rely on these tools for financial decisions. By using these charting tools, the purchaser agrees that the seller and creator hold no responsibility for any decisions made based on information provided by the tools. The purchaser assumes full responsibility and liability for any actions taken and their consequences, including potential financial losses or investment outcomes that may result from the use of these products.

By purchasing, the customer acknowledges and accepts that neither the seller nor the creator is liable for any undesired outcomes stemming from the development, sale, or use of these products. Additionally, the purchaser agrees to indemnify the seller from any liability. If invited through the Friends and Family Program, the purchaser understands that any provided discount code applies only to the initial purchase of Candela's subscription. The purchaser is responsible for canceling or requesting cancellation of their subscription if they choose not to continue at the full retail price. In the event the purchaser no longer wishes to use the products, they must unsubscribe from the membership service, if applicable.

We do not offer reimbursements, refunds, or chargebacks. Once these Terms are accepted at the time of purchase, no reimbursements, refunds, or chargebacks will be issued under any circumstances.

By continuing to use these charting tools, the user confirms their understanding and acceptance of these Terms as outlined in this disclaimer.
