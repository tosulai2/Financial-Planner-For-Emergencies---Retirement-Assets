# Financial-Planner-For-Emergencies---Retirement-Assets
UC Fintech Bootcamp Challenge 5 Module 5 Challenge assignment for the UC Berkeley Fintech Bootcamp.

In this challenge, I built a tool built a financial planner tool to help credit union members evaluate their financial health by assessing their monthly budgets and visualizing their current savings. As well as forecasting a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds by comparing performance over 10 vs 30 years and different asset weightings. 

I created a Jupyter notebook that contains my code, api calls/response objects, data preparation, analysis, simulations and visualizations, etc.

## Technologies

This project uses Python programming language, Jupyter notebook, the libraries and functions associated, etc.

## Installation Guide

Make sure to install Jupyter notebook (comes with Anaconda), OS, Requests and JSON libraries, as well as the python-dotenv Library and Alpaca SDK

## Usage

The jupyter file contains: 
- Response data/objects containing live/actual financial data of crypto assets from endpoint URLs and free crypto APIs

- Alpaca trade api rest object for calling live financial data

- Dataframes created from the API requested financial data with the trading days as the DateTimeIndex

- Evaluations on the current crypto, stock and bond holdings as well as determinations on if the member has enough emergency savings

- Monte Carlo simualtions of the performance of the portfolio over 10 and 30 years at different asset weightings

- Analyses of the monte carlo simulations forecast of the cumulative returns over those periods and with those weightings using a 95% confidence interval.

General information about my analysis: my analysis/simulations were run on July 20th 2022 and all data points used this date as the end date

Libraries used in analysis: os, requests, json, dotenv, pandas and alpaca_trade_api, matplotlib, MCForecastTools libraries

## Contributors

Name: Taofik Sulaiman | Phone: 2407162877 | Email: taofik.sulaiman@gmail.com | Linkedin: https://linkedin.com/in/taofik-sulaiman | Twitter: https://twitter.com/taofik_smk

## License

OpenSource License, feel free to use as needed but make sure to givce me credit and contact me to let me know the cool ways you used this. I obtained portions of this code via the University of California BerekelY Fintech Bootcamp curated by Trilogy U Edcuation
