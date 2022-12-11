# trading_spy

Over the last few months in 2022 i have noticed that SPY reacts dramatically to how the Consumer Price Index(CPI) comes out. Consumer Price Index is data point released the US Goverment that tracks the inlfation rate year over year and month over month in the USA. With the FED trying to lower the inflation by increasing rate, traders have been keeping a keen eye on how CPI comes in. If the CPI comes in low, it implies that FED's policies are working and therefore they may think of lowering the rates or stalling the rate increase or lowering the rate increse, which is good news for $SPY bulls. On the contrary, if the CPI comes in high, it implies that FED's policies are NOT working and therefore they may think of increasing the rates, which is good news for $SPY bears. I have tried to come up with a strategy thats profitable in either of these scenarios.

1) For this study I gathered $SPY closing price one day before CPI comes out. My strategy would be to buy a $SPY call and put thats the closest integer to the closing price a minute before the trading closes. Example: If SPY closed at 385.57 I would buy a 386 call and a 386 put expiring the next day.

2) CPI comes out at 08:30 AM, and the market behaves accoridng to the data. My strategy is also to sell both the contracts in the first minutes of trading.

3) Below I have an excel sheet on how this strategy would have performed in 2022.

<img width="1116" alt="Screen Shot 2022-12-11 at 12 29 58 PM" src="https://user-images.githubusercontent.com/69361645/206919105-09294855-70ab-4db1-8944-d495c88fef52.png">

4) As you can see this strategy would have yielded about 50% return in 2022. Additionally, the market became more volatile since June and this strategy would have yielded 100% return since June 2022.

5) I have also explored two other strategies: selling at close of CPI day would yield 100% return in 2022 and 195% return since June 2022. This stratgey is especially hard to implement beacuse it takes a lot of mental capital to hold a contract that ITM and profitable through the uncertainty of a trading day.

6) Maximum profit could be attained by selling at high/low of the CPI day, yielding 266% return in 2022 and 390% since June 2022. This strategy is obviously hard to implement because its hard to predict high/low of the day.

7) All in all, buying both a call and put option contract to the nearest integer closing price of SPY on the pre-CPI day would yield on average a minimum of 50% return 2022 and 100% reutrn since June 2022.

Take everything with a grain of salt. Not a financial advise.
