
# Unit 10—A Yen for the Future- Conclusions

## TIME SERIES ANALYSIS

### Yen-USD Historical Trend
#### Observation: The Yen has had major swings from 1990-2019. Over this period Yen has devalued against USD. There are ceertainly events around 1992, 1996, 2000 and 2015 with major spikes. Since 2008-2015, there has been consistent weekening that was reversed in 2016 with Yen strengthening against USD. Since 2016, Yen is again weekening against USD until 2019.


### Forecasting the Yen-USD Settle Price using Hodrick-Prescott filter Model
#### Observations: With HP Filter and looking at resulting trends, there are short-term fluctuations. There could be short-term trading opportunities where two color lines in the graph deviates from each oher resulting in Yen undervalued v USD or Yen overvalued against USD resulting in long or short positions respectively.  

### Forecasting the Yen-USD Settle Price using an ARMA model
#### Observations: As the p-value is greater than  0.05, it is concluded that ARMA model used in Yen-USD forecasting is not a good fit.   

### Forecasting the Yen-USD Settle Price using an ARMIA model
#### Observations:As the p-value is greater than  0.05, it is concluded that ARIMA model used in Yen-USD forecasting is not a good fit.   

### Forecasting the Yen-USD Settle Price using GARCH model
#### Observations: As the p-value is is less than  0.05, it is concluded that GARCH model used in Yen-USD forecasting is a good fit and it can be clncluded that volatility (risk) is expected to increase over next five days forecast period.   

### Overall Conslusion
#### Based on the analysis above, I would not enter into long trade for Yen-USD as there is no conclusive analysis that Yen-USD will strengthen. Moreover, as the volatility is expected to increase over forecasting period, its not recomended for long trade.


## REGRESSION ANALYSIS
#### The out-of-sample predictions rmse is 0.415 vs in-sample predictions rmse of 0.596. Based on observed rmse of out-of-sample and in-sample predictions, it can be concluded that regression model predictions are better for test period than for train period. 
