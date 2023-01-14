The Normalno CryptoWhales Futures Index is a futures-weighted index that tracks the performance of crypto assets in the most valuable crypto projects.

Objectives ----

The CryptoWhales Futures Index is reflected both for Market Cap and Futures Open Interest to determine manager’s estimates for optimization using Black–Litterman model.

Terms ----

Futures contract (or Futures) is an agreement to buy or sell the value of the underlying asset at a predetermined price at a specified time in the future.

Open Interest (OI) is a technical indicator using for measuring market activity: decreasing OI indicates money flowing out of the market while increasing OI represents new or additional money coming into the markets.

Black–Litterman model is a mathematical model for portfolio allocation.

Sharpe ratio is a measure of the investment return adjusting for its risk.


Token Inclusion Criteria ----

Assets (tokens) must meet the following criteria:

- Market capitalization must be over $1b, at least 6 months of price and liquidity history,
- Excluding underdeveloped clones/forks, such as Bitcoin Cash or Ethereum classic,
- Excluding meme coins, such as DOGE or SHIB,
- Excluding the stablecoins (USDC, USDT, etc.) due to the lack of the ability to raise the price,
- Rolling 3-month correlation with Bitcoin less than 0.9,
- Must not be considered a security by the corresponding authorities across different jurisdiction.

Index Weight Calculation ----

1. Calculate portfolio manager’s estimation
  - The weight of each token within the index will be as follows: token_futures_open_interest / total_futures_open_interest
  - Max weight: 49%, excess weight for a given token will be redistributed to stablecoins
  - Min weight: 1%, underweight for a given token will be redistributed to stablecoins
2. Set up investment objectives and constrains
  - Optimization strategy: maximize Sharpe ratio
  - Range of assets weight: 1…49%
3. Taking into account the manager’s estimation, investment objectives and constrains, optimize the portfolio using Black-Litterman model.
4. Get assets allocation from optimized model.

Index Maintenance ----

The index is maintained monthly in two phases:

1. Determination Phase:
During the determination phase, the tokens being added and deleted from the index calculation are determined during the last week of the month.

2. Rebalancing Phase:
During the rebalancing phase, the index composition will change to the new weights during the first week of the following month.

NOT FINANCIAL ADVICE. PORTFOLIO IS THE PERSONAL RESEARCH OF OWNER. THE RISK OF INVESTING IN CRYPTOCURRENCIES OR CRYPTO RELATED ASSETS IS SUBSTANTIAL AND CAN RESULT IN A COMPLETE LOSS OF FUNDS. PAST PERFORMANCE IS NOT INDICATIVE OF FUTURE RESULTS.
