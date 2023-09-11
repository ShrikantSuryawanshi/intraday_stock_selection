# Intraday Stock Selection
Intraday Stock Selection is a project which suggests a stock for intraday trading. The dataset is consists of the stock prices of Nifty 50 shares which updates regularly. The moving average method is used for the stock selection. 10 DMA, 30 DMA, 60 DMA, 90 DMA, 120 DMA and 200 DMA is calculated for each stock. The rule is that if a particular stock is trading above its 10 DMA, 30 DMA, 60 DMA, 90 DMA, 120 DMA but below 200 DMA and as soon as it crosses the 200 DMA to upward side, the bullish trend is detected and buy signal is generated automatically. 
On the other hand, if a particular stock crosees the 200 DMA downward side, the bearish trend is detected and short signal is generated automatically. 
We just need to update the names of stocks which are trading with highest volume. The rest will be done automatically.
Here is the link of Google sheet ; https://docs.google.com/spreadsheets/d/1CrGxREXP2JgjMA7ABh8XZ9iAnCRVDhCczu9eQqrm47E/edit?usp=sharing
