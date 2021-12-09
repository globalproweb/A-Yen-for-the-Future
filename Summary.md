# A Yen for the Future
# Summary 


# Disclammer: ARMA Model 

My ARMA model did work  due to NotImplementedError: 
statsmodels.tsa.arima_model.ARMA and statsmodels.tsa.arima_model.ARIMA have been removed in favor of statsmodels.tsa.arima.model.ARIMA (note the .between arima and model) and statsmodels.tsa.SARIMAX.
ImportError: cannot import name 'ARMA' from 'statsmodels.tsa.arima.model' (C:\Users\Jean-Pierre Koudifo\anaconda3\lib\site-packages\statsmodels\tsa\arima\model.py)

# 1. Based on your time series analysis, would you buy the yen now?
 
I would not feel confident buying Yen because the  ARIMA model and having a P value  > 0.05 and the   AIC and BIC score of the ARIMA Model beeing  too high.  

# 2. Is the risk of the yen expected to increase or decrease?

The  GARCH model has forcatsed high  volatility. The final forecast graph shows that volatility will keep increasing thus a very high risk.

# 3. Based on the model evaluation, would you feel confident in using these models for trading?

I would not feel comfortable using these models to trade. ARMA did work for me and  ARIMA model was  not  accurate. The Garch model has shown a better understanding of the yen currenccy high volatility.