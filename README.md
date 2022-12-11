# trading_spy

Over the last few months in 2022 I have noticed that SPY reacts dramatically to how the Consumer Price Index(CPI) comes out. Consumer Price Index is data point released by the US Goverment that tracks the inlfation rate year over year and month over month in the USA. With the FED trying to lower the inflation by increasing rates, traders have been keeping a keen eye on how CPI comes in. If the CPI comes in low, it implies that FED's policies are working and therefore they may think of lowering the rates or stalling the rate increase or lowering the rate increse, which is good news for $SPY bulls. On the contrary, if the CPI comes in high, it implies that FED's policies are NOT working and therefore they may think of increasing the rates, which is good news for $SPY bears. I have tried to come up with a strategy thats profitable regardless of how the CPI comes in.

1) For this study I gathered $SPY closing price one day before CPI comes out. My strategy would be to buy a $SPY call and put thats the closest integer to the closing price a minute before the trading closes. Example: If SPY closed at 385.57 I would buy a 386 call and a 386 put expiring the next day. In my experience trading SPY options, these contracts would cost me a maximum of $200 each. So, my total capital if buying one contract each should not be more than $400.

2) CPI comes out at 08:30 AM, and the market behaves accoridng to the data. My strategy is also to sell both the contracts in the first minutes of trading.

3) Below I have an excel sheet on how this strategy would have performed in 2022.

<img width="1115" alt="Screen Shot 2022-12-11 at 12 46 10 PM" src="https://user-images.githubusercontent.com/69361645/206919823-87d4c436-e542-4482-86e3-9e78c72f88ac.png">


4) This strategy would have yielded about 50% return in 2022, meaning for each $400 put in, I would have got $600. Additionally, the market became more volatile since June and this strategy would have yielded 100% return since June 2022, meaning for each $400 put in I would have got $800.

5) I have also explored two other strategies: selling at close of CPI day would yield 100% return in 2022 and 195% return since June 2022. This strategy is especially hard to implement beacuse it takes a lot of mental capital to hold a contract that ITM and profitable through the uncertainty of a trading day.

6) Maximum profit could be attained by selling at high/low of the CPI day, yielding 266% return in 2022 and 390% since June 2022. This strategy is obviously hard to implement because its hard to predict high/low of the day.

7) All in all, buying both a call and put option contract to the nearest integer closing price of SPY on the pre-CPI day would yield on average a minimum of 50% return 2022 and 100% reutrn since June 2022. I have to note that this strategy expects the market to be volatile to be profitable.

Take everything with a grain of salt. Not a financial advise.
