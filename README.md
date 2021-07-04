# Financial_Planner
This notebook contains two financial tools to help customers budget. 1) To determine the customers required emergency fund amount and if their current portfolio is sufficient to cover an emergency 2) Running a Monte Carlo simulation on the customers investment portfolio to forecast the upper and lower 95% probability of their portfolio in 10 years and 30 years.
Below are the three analysis that will be performed in this notebook: 
1. Evaluate the Cryptocurrency Wallet by Using the Requests Library
2. Evaluate the Stock and Bond Holdings by Using the Alpaca SDK
3. Create a Financial Planner for Retirement

## Technologies Require
* This project leverages python version 3.8.5
* python dotenv Library
* Alpaca SDK
* Request Library
* JSON Library
* Project will be accomplished in JupyterLab

## Install python dotenv Library
* On the terminal (Git Bash) under the conda dev environment, type the code below:
pip install python-dotenv

## Install Alpaca SDK
* On the terminal (Git Bash) under the conda dev environment, type the code below:
pip install alpaca-trade-api

## Install Request Library
* On the terminal (Git Bash) under the conda dev environment, type the code below:
conda install -c anaconda requests

## Install JSON Libary
* On the terminal (Git Bash) under the conda dev environment, type the code below:
conda install -c jmcmurray json



## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run

## Required Imports
* pandas - data manipulation and analysis
* Path from pathlib - import CSV files
* %matplotlib inline - assist in building plots and visuals
* numpy - calculating  square roots
* os - portable way of using operating system dependent functionality
* requests - standard for making HTTP requests in Python.
* json - convert the python dictionary from the API into a JSON string that can be written into a file
* from dotenv import load_dotenv - reads key-value pairs from a .env file and can set them as environment variables
* import alpaca_trade_api as tradeapi -  used to get API trading data for this project. To gain access to Alpaca's API key and API secret keys, the user needs to register for personal account and save their own keys.
* from MCForecastTools import MCSimulation - generate range of possible outcomes on the portfolio

## Install Guide
* import os
* import requests
* import json
* import pandas as pd
* from dotenv import load_dotenv
* import alpaca_trade_api as tradeapi
* from MCForecastTools import MCSimulation
* %matplotlib inline

## Usage
To use the JupyterLab notebook clone the repo and run git bash, open notebook financial_planning_tools.ipynb and create a new .env file that holds your alpaca API key and secret API key

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT
