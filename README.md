# Creating_Index-Price-Value-Volatility-Equally-Leveraged-
Creating different versions of index [ Price weighted , Value Weighted, Equally Weighted, Volatility Weighted, Leveraged ]


### Project Description: Creating an Index and Leveraged Product

#### Part I: Index Definition
An index was defined comprising five liquid assets with readily accessible market prices and 10 years of daily data. The chosen assets were selected based on their liquidity and relevance in the market, ensuring they provide a robust representation of the desired investment theme.

#### Part II: Building Index Versions
1. **Data Collection:** Daily price data for each asset was downloaded, ensuring at least 10 years of historical data.
2. **Return Calculation:** Daily returns for each asset were calculated, and the index was declared as a total return index.
3. **Index Versions:**
   - **Price-Weighted Index:** Constructed by assigning weights based on the price of each asset.
   - **Value-Weighted Index:** Created by assigning weights based on the market value of each asset.
   - **Equally Weighted Index (Rebalanced Annually):** Equal weights were assigned to each asset, with annual rebalancing.
   - **Volatility-Weighted Index (Rebalanced Quarterly):** Weights were assigned based on the inverse of the asset's volatility, with quarterly rebalancing.
4. **Historical Track Record:** Generated historical performance records for each index version.

#### Part III: Performance Statistics
For each index version, the following performance statistics were calculated:
- **CAGR (Compound Annual Growth Rate)**
- **Volatility**
- **CAGR/Volatility (Sharpe Ratio with r=0%)**
- **Downside Volatility**
- **CAGR/Downside Volatility (Sortino Ratio with r=0%)**
- **Peak-Valley Drawdown**
- **CALMAR Ratio**
- **Alpha**
- **Beta**
Performance graphs were created to visualize the historical performance of all four index versions.

#### Part IV: Leveraged Product
A leveraged product was built based on one of the index versions, with a 2.0x leverage factor. Annual returns for both the leveraged product and the underlying index were calculated and displayed for each year. An analysis of the best and worst years relative to the index was provided, explaining why the performance was an outlier in the sample.

This project involved creating, analyzing, and visualizing multiple versions of a custom index and developing a leveraged product based on the chosen index version.
