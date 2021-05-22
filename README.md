# Financial Planning #

## Part 1 - Personal Finance Planner ##

This personal finance planner application allows users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.  The following steps were followed to achieve the desired results:

- collect crypto prices using the requests library;
- collect investments data using Alpaca;
- pull all the data together to get to the total emergency fund and match that amount against three times the amount of the member's monhtly income.

## Part 2 - Retirement Planning ##

The retirement planning tool uses the Alpaca API to fetch historical closing prices for a retirement portfolio and then use the MCForecastTools toolkit to create Monte Carlo simulations to project the portfolio performance for varying investment amounts against varying lengths of time to save.

