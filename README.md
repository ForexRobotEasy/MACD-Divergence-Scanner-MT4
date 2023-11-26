# MACD Divergence Scanner MT4

This code is a custom indicator for MetaTrader 4 that scans for MACD (Moving Average Convergence Divergence) divergences on multiple symbols and timeframes. It identifies bullish and bearish divergences based on user-defined thresholds.

## Input Parameters

- ScanPeriod: The period for scanning divergences. Default value is 14.
- DivergenceThreshold: The threshold for identifying divergences. Default value is 0.0002.

## How it Works

1. The indicator initializes by enabling the necessary indicators and setting the indicator names and descriptions.
2. Upon calculation, the indicator starts scanning for divergences.
3. It loops through all selected symbols and timeframes.
4. For each symbol and timeframe, it calculates the MACD values using the given parameters.
5. It then loops through all bars and checks for bullish and bearish divergences.
6. If a bullish divergence is detected, the indicator performs the necessary action. (Add your code here)
7. If a bearish divergence is detected, the indicator performs the necessary action. (Add your code here)
8. The scanning is completed, and the indicator is ready for the next calculation.

ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/macd-divergence-scanner-mt4-review-spotting-forex-trend-reversals/).
