# Trader Behavior vs. Market Sentiment Analysis

## Project Overview
This project investigates the relationship between cryptocurrency trader behavior and market sentiment using historical execution data from Hyperliquid and the Bitcoin Fear & Greed Index. The goal is to identify how trading profitability, risk exposure, and capital efficiency vary across different market sentiment regimes (Fear, Greed, and Neutral).

## Repository Structure
The project follows a standardized data science submission format:

```text
ds_report/
├── notebook_1.ipynb       # Data cleaning, merging, and exploratory data analysis
├── csv_files/             # Processed datasets and intermediate outputs
├── outputs/               # Visualizations (PnL, Position Sizing, Efficiency charts)
├── ds_report.pdf          # Final formal analytical report
└── README.md              # Project documentation (this file)
```

## Dataset Descriptions
1.  **Market Sentiment Dataset**: Daily Bitcoin Fear & Greed Index classifications (Fear, Extreme Fear, Neutral, Greed, Extreme Greed).
2.  **Trader Execution Dataset**: Granular trade-level data including `Closed PnL`, `Size USD`, `Timestamp`, and `Side`.

## Key Findings
- **Profitability peaks during Greed**: Absolute profits and capital efficiency (PnL per USD) are significantly higher during Greed phases compared to Fear or Neutral.
- **Contrarian Sizing**: Traders tend to increase their average trade size during Fear phases despite lower profit efficiency, suggesting an accumulation or "averaging down" behavior.
- **Efficiency Gap**: Profit efficiency in Greed regimes is approximately 2.9x higher than in Fear regimes, highlighting the impact of market liquidity and trend strength on execution quality.

## Installation & Usage
1.  Open `notebook_1.ipynb` in **Google Colab**.
2.  Ensure you have the required Python libraries installed: `pandas`, `numpy`, `matplotlib`, `seaborn`.
3.  The notebook is configured to load data directly from the provided Google Drive links.

