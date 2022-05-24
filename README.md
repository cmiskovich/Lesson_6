# Lesson_6
# Primary application file

Produce a Jupyter notebook that contains two financial analysis tools:

A financial planner for emergencies so the memebers can be able to visualize their current savings. Also, the members can determine if they have enough reserves for an emergency fund.

A financial planner for retirement.  This tool will will forcast their retirement porfolio 30 years out using the Monte Carlo simulation.



---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9

---

## General information about analysis.

During the analysis you realize after 30 years stocks and bonds will grow well over time and it is better to have time in the market than timing the market.  In the 10 year analysis you see you can leverage the outcome with stocks but you won't be able to retire even at the high end outcome of stocks in 10 years.

---

## Information about datasets

Amount of crypto held:

btc_coins 

eth_coins

Amount earned each month:

monthly_income

websites for API calls for crypto prices:

btc_url

eth_url

Datasets for API call:

btc_response
eth_response

Prices for crypto held:

btc_price
eth_price

Value of crypto held:

btc_value
eth_value

Total of cypto wallet:

total_crypto_wallet

Shares held in stocks and bonds:

spy_shares 
agg_shares 

API keys:

alpaca_api_key 
alpaca_secret_key 

Alpaca Rest:

alpaca

Tickers for stocks and bonds held:

tickers

Timeframe:

timeframe

Start and Closing date:

start_date 
end_date 

Current closing prices:

portfolio_prices_df

Closing prices:

agg_close_price
spy_close_price

Value of the portfolio based on closing price:

agg_value
spy_value

Total value of stock and bonds:

total_stocks_bonds

Total value of crypto and stock and bonds:

total_portfolio

List of savings data that has two elements crypto wallet and total stock and bonds:

savings_data

Savings Dataframe that displays three paramaters using the list, columns set equal to python list with single value called amount, and index with cytpto and stock/bond:

savings_df

Emergency fund is three times the value of monthly income:

emergency_fund_value


Three years worth or data for 60/40 split:

start_date 
end_date 

API call for 3 years worth of data for spy and agg:

portfolio_prices_df

Configures 60 SPY 40 AGG split for Monte Carlo  30 year simulation:

MC_60_40

30 year Monte Carlo 60 40 split line visulization:

stock_bond_plot

30 year Monte Carlo 60 40 split distribution visulization:

stock_bond_plot_dist

Returns with 95% confidence the intervals the range of possible outcomes of the current stock/bond portfolio over 30 years:

ci_lower_thirty_cumulative_return 
ci_upper_thirty_cumulative_return

Configures 80 SPY 20 AGG split for Monte Carlo 10 year simulation:

MC_80_20

10 year Monte Carlo 80 20 split line visulization:

stock_bond_plot_10_year

10 year Monte Carlo 80 20 split distribution visulization:

stock_bond_dist_10_year

Returns with 95% confidence the intervals the range of possible outcomes of the current stock/bond portfolio over 10 years:

ci_lower_ten_cumulative_return 
ci_upper_ten_cumulative_return



---

## Libraries used in analysis

os

requests

json

pandas

dotenv

alpaca_trade_api

MCForecastTools

MCSimulation

%matplotlib inline


---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)
