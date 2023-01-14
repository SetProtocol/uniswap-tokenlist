The Normalno L1xL2 Dominance Index is a weighted index that tracks the transactions activity and addresses growth inside Layer-1, Layer-2 networks and sidechains.

Objectives ----

The Normalno L1xL2 Dominance Index is reflected both for transactions activity and addresses growth inside concrete network to determine its dominance. That dominance represents manager’s estimates for optimization using Black–Litterman model.

Terms ----

Layer One network is blockchains that validate and finalize transactions without the need for another network.

Layer Two network is blockchains that rely on Layer-1 for security and/or consensus.
A sidechain is a separate blockchain that runs independent of main network (e.g. Ethereum) and is connected to mainnet by a two-way bridge.

Black–Litterman model is a mathematical model for portfolio allocation.

Sharpe ratio is a measure of the investment return adjusting for its risk.

Token Inclusion Criteria ----

Assets (tokens) must meet the following criteria:

- Market capitalization must be over $100m, at least 6 months of price and liquidity history,
- Excluding underdeveloped clones/fork,
- Rolling 3-month correlation with Ethereum less than 0.8,
- Must not be consider 
- Must not be considered a security by the corresponding authorities across different jurisdiction.

Index Weight Calculation ----

1. Calculate portfolio manager’s estimation
   - The weight of each token within the index will be as follows: network_transactions_count / total_transactions_count
   - Max weight: 49%, excess weight for a given token will be redistributed to stablecoins
   - Min weight: 1%, underweight for a given token will be redistributed to stablecoins
2. Set up investment objectives and constrains
   - Optimization strategy: maximize Sharpe ratio
  - Range of assets weight: 1…49%
2. Taking into account the manager’s estimation, investment objectives and constrains, optimize the portfolio using Black-Litterman model.
3. Get assets allocation from optimized model.

Index Maintenance ----

The index is maintained monthly in two phases:

1. Determination Phase:
During the determination phase, the tokens being added and deleted from the index calculation are determined during the last week of the month.

2. Rebalancing Phase:
During the rebalancing phase, the index composition will change to the new weights during the first week of the following month.


NOT FINANCIAL ADVICE. PORTFOLIO IS THE PERSONAL RESEARCH OF OWNER. THE RISK OF INVESTING IN CRYPTOCURRENCIES OR CRYPTO RELATED ASSETS IS SUBSTANTIAL AND CAN RESULT IN A COMPLETE LOSS OF FUNDS. PAST PERFORMANCE IS NOT INDICATIVE OF FUTURE RESULTS.
