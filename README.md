# OU-process 配對交易策略 OU-process Pair Trading Strategy

針對標的過去的價量或其他相關的資料，利用統計方法和 python 來建構配對交易策略和回測架構，其中包括：

- 採用 Cointegration 來選取適合的標的。 *檔案：pair_trading_find_pair_yf.ipynb*
- 使用 OU-process 來優化交易策略，並用歷史資料進行回測。 *檔案：pair_trading_OU_processing_single_pair.ipynb*
