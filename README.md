# Financial Planning Tools

This program runs two seperate financial analysis programs for an individual portfolio. First, the program evaluates the customer's cryptocurrency wallet valuation and stocks and bonds holdings using API requests. The program then runs the valuations of both, plots them and lets the customer know where they stand with regards to funding their emergency fund.  Secondly, the program runs the stocks and bonds portfolio through several Monte Carlo simulations and shows 95% confidence intervals for both so they can make an educated decision on how to structure their portfolio for maximum returns.

---

## Technologies

This application is compatible with Python 3.9.
The Pandas, dotenv, MCForecastTools and alpaca_trade_api libraries were used along with matplotlib and must be installed in order to run the program correctly.

Pandas is used for data science and analysis and machine learning.

Matplotlib allows for the visualization of data in the form of plots and graphs.

dotenv is a library that allows for secure usage of API keys.

MCForecastTools is a module that allows data to be run through a series of simulations for potential future outcomes.

alpaca_trade_api is an API from Alpaca that gives you real time stock ticker data that can be used for analysis.

This program will work on Windows, MacOS and Linux with Python 3.9 installed. The user will need to run the program in a code editor such as Juypter Lab or Visual Studio Code.

Documentation for the Pandas library can be found [here.](https://pandas.pydata.org/docs/)

Documentation for the dotenv library can be found[here.](https://pypi.org/project/python-dotenv/)

Documentation for matplotlib can be found [here.](https://matplotlib.org/stable/users/index)

Documentation for alpaca_trade_api can be found [here.](https://pypi.org/project/alpaca-trade-api/)

---

## Installation Guide

Install the following dependencies before running the program.

To install the pathlib, pandas and matplotlib libraries type the following into your CLI:

```
python
pip install pandas
pip install -U python-dotenv
pip install -U matplotlib
pip3 install alpaca-trade-api
```
---

To ensure you can run the MCForecastTools module, you'll want to make sure the file ``` MCForecastTools.py``` is present in the directory of your ```financial_planning_tools.ipynb``` file.

## Usage

To run the program open your code editor and navigate to the folder containing the file "financial_planning_tools.ipynb".

Load the program and run the cells in sequence from top to bottom.

The output displays various points of detailed analysis of the data including visual plots and graphs so the user can get a well rounded view of the data.

---

## Contributors

Developed by:

Graham Johnstone
Email: johnstonegr@gmail.com

---

## License
This code is published under the Creative Commons License, 2021.

