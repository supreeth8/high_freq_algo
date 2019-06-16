# Analysis of Different Algo Strategies
[Code link](https://github.com/supreeth8/high_freq_algo/blob/master/Analysis.ipynb)



With given daily prices of exchange-rate, the price movement over the period of 2014 to 2016 is given below.
![Image of Price movements](https://github.com/supreeth8/high_freq_algo/blob/master/img/XAU_USD%20price%20movment.png)

The daily Profit and loss of the price is
![Image of Daily Progit and loss](https://github.com/supreeth8/high_freq_algo/blob/master/img/Daily%20prfit%20and%20loss.png)

## 1)Annualized volatility of daily return



The volatility gives risk factor (extreme return movement) of the trading strategies. According to volatility,

**Top performing strategies** are:

1. 03\_09
2. 03\_12
3. 03\_11
4. 03\_05
5. 03\_06





**Worst performing** are:

1. 01\_03
2. 01\_05
3. 01\_07
4. 01\_08
5. 01\_02



## 2) Information Ratio

This is a measurement that gives comparative returns beyond benchmark return and with respect to volatility of returns. According to Information ratio calculated for the given returns of strategies, top 5 strategies are given in the figure. Since we are not benchmarking to anything benchmark return is zero.

![Alt text](https://github.com/supreeth8/high_freq_algo/blob/master/img/info_ratio.png)


## 3)Sharpe Ratio
This measurement is used to give investors the overall return compared to financing rate (risk-free rate) which is 0.738% as my refinancing rate from T-Bill for that period which I got from historical chart from Wall Street Journal.

 ![Alt text](https://github.com/supreeth8/high_freq_algo/blob/master/img/sharpe_ratio.png)
 
 ## 4) Cumulative Return
 
Cumulative return on an investment is the aggregate amount over the given duration (2014-2016). From the graph we can see the overall cumulative return for top 5 strategies.
![Alt text](https://github.com/supreeth8/high_freq_algo/blob/master/img/Cummulative%20return.png)

Final cumulative return:

![Final Cumulative return](https://github.com/supreeth8/high_freq_algo/blob/master/img/cumlative_return.png)


## 5)Yearly Return

Yearly return gauge the strategies, by one year. This useful to track the compare trading strategies over the years and tweak if its shortfalls expected return or when its not performing as compared previous years.

 ![Yearly_return](https://github.com/supreeth8/high_freq_algo/blob/master/img/Yearly_return.png)

## 7) Maximum Drawdown

A maximum drawdown (MDD) is the maximum loss from a peak to a trough of a portfolio, before a new peak is attained.

**MDD = (Trough – Peak) / Peak.**

> Based on this calculation strategies with largest drawdown are:

![Maximum Drawdown](https://github.com/supreeth8/high_freq_algo/blob/master/img/MaxDD.png)



## 8)Heatmap between differrent strategies and daily Pnl

Here I have used heatmap representation to show the correlation between different strategies and daily Pnl.
![Heat_map](https://github.com/supreeth8/high_freq_algo/blob/master/img/Heatmap.png)

### Note:

### The leftmost color bar indicates correlation between values from 0 to 1 (with 0 = Yellow and 1 = blue)





This heatmap gives the correlation between daily profit and lose (%) and the returns made by the each strategies.
![Daily_pnl_heat map](https://github.com/supreeth8/high_freq_algo/blob/master/img/Dail_pnl%20heatmap.png)

As you can see that strategies:

- 03\_10
- 01\_10
- 01\_11
- 03\_09
- 01\_09

Have negative correlation.





## ConclusioN

Based on the performance metrics I discussed above top 5 trading strategies I will chose are:

1 03\_12
2. 03\_04
3. 01\_12
4. 03\_11
5. 03\_06
