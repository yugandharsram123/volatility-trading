EPAT Guided Mini Project - Volatility Trading
===============================================

Completed project:
  mini_project_volatility_trading_completed.ipynb

Runtime files:
  options_data.bz2
  trade_analytics_function.py

The notebook was executed end-to-end against the supplied dataset before delivery.
Reference configuration:
  strike_price_multiple = 5
  num_days_before_expiry = 3
  delta_threshold = 0.5
  annual_rate = 0.02
  broker_lambda = 0.05/100
  kappa = 75.6
  lot_size = 5
  strategy = short straddle
  entry condition = IV_Rank >= 50

Validated final trade-level analytics from the executed notebook:
  Total PnL = 4501.27
  Total Trades = 590
  Number of Winners = 311
  Number of Losers = 279
  Win (%) = 52.71
  Loss (%) = 47.29
  Per Trade PnL of Winners = 134.17
  Per Trade PnL of Losers = 133.43
  Profit Factor = 1.12

Note: The notebook follows the supplied QuantInsti model-solution logic and terminology.
