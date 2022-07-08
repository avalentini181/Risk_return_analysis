# Risk Return Analysis
---------------------

## About Project:
In this Challenge, I assumed the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

I've been tasked with evaluating four new investment options for inclusion in the client portfolios. Legendary fund and hedge-fund managers run all four selections. I needed to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

## Code Used:
Some of the code i used for this projects dataframe included ploting(.plot), percent change(.pct_change), standard deviation(.std), rolling window(.rolling) and finding the mean(.mean). 

I also used some calculations such as finding the cumulative returns (cumulative_returns = (1 + daily_returns).cumprod() - 1), annualized standard deviation (annualized_standard_deviation = daily_returns.std() * year_trading_days ** (1/2)), average annual return (average_annual_return = daily_returns.mean() * year_trading_days) and lastly sharpe ratios (sharpe_ratios = average_annual_return / annualized_standard_deviation).
