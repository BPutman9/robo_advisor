# Robo-Advisor

![](https://digital.hbs.edu/platform-rctom/wp-content/uploads/sites/4/2018/11/investorjunkie-robo-advisors-4-1-421x200.jpg)

## New Users Start Here ##

Thank you for choosing our Robo Advisor tool to help get you started in investing. To use our program, you'll need to make sure you have a few basic requirements installed.

- Python version 3.7 or later [Anaconda](https://www.anaconda.com/products/individual)
  - Once installed, make sure to set up Jupyter Lab as well. In your terminal, run the command, "conda install -c conda-forge jupyterlab"
  - The necessary Python libraries and links to their documentation to help get you started:
    - [Pandas](https://pandas.pydata.org/docs/)
    - [Panel](https://panel.holoviz.org/)
    - [Plotly Express](https://plotly.com/python/plotly-express/)
    - [HV Plot](https://hvplot.holoviz.org/)
    - [Matplotlib](https://matplotlib.org/)
    - [Numpy](https://numpy.org/install/)
    - [OS](https://docs.python.org/3/library/os.html)
    - [Dotenv](https://pypi.org/project/python-dotenv/)
    - [Requests](https://pypi.org/project/requests/)
    - [Alpaca Trade API](https://alpaca.markets/docs/api-documentation/)
    - ***Optional*** [Pyttsx3](https://pypi.org/project/pyttsx3/)
    
- There are a few files leveraged by the program for creating historical returns visuals and for running the monte carlo simulation. These are included in the Git Hub project folder [here](https://github.com/BPutman9/robo_advisor)

**The file for running the program is Inputs_data_pulls_3.ipynb **

When running the program, the software will prompt you for some user inputs to help customize your investment options and resulting dashboard:
- Name
- Age
- Desired retirement age
- Your experience with various investments 
- Tolerance for risk 
- Asset classes
- Starting investment amount
- Annual contribution amount

Based on your inputs, Alpaca will retrieve the appropriate ticker symbols to include in the Monte Carlo simulation. 
Please expect this simulation to take a few minutes to run, depending on the speed of your computer, and number of assets selected. 

## Resulting Visuals ##

Your results will be packaged in a dashboard for you to view. 

## Day 1 ##

## Project Summary ##

Our team is building a robo advisor to help individual investors assess potential investment performance based on their:

- Investment horizon
- Initial investment amount and future contributions
- Asset selection
- Appetite for risk

## Project Goal ##

Leverage the user inputs to feed our Python code to make the process as automated as possible. The user's inputs will impact the investment results which will be displayed on an investor dashboard. 

## Questions to be Answered ##

- How does a user's investment time period impact their returns? 
- How does a user's aggressive, moderate, or conservative investment approach affect long-term gains?
- Do annual contributions have a material impact the compounding of the portfolio's return?
- Does rebalancing the portfolio meaningfully improve the performance of the retirement portfolio?

## Day 2 ##


### Our Data Set ###

Our data was generated using the Alpaca API. We chose a 10 year historical window as 10 year historical performance is an industry standard in assessing an asset's performance
We also felt this date range covered both up and down markets so as to not risk being skewed by using a shorter timeframe

### The Questions We Will Address ###

- How can we create both a low cost option, while still providing the client with guidance along the way?
- Can we leverage user input to offer a variety of investment options?
- Can we help motivate an investor by showing them the cost of doing nothing?

### The Packages to be Used ###

- Pandas
- Panel
- OS 
- Dotenv
- Hvplots
- Plotly Express
- Alpaca Trade API
- Matplotlib

### Analysis Methods to be Used ###
- Returns and cumulative returns
- Standard deviation
- Monte Carlo simulation
- Data plotting and visualization   

## Day 3 ##

- Further code development
- PowerPoint draft presentation created

## Day 4 ##

- Edge testing performed
- Additional visualizations created
- Iteration to allow for both a starting investment amount as well as recurring investment amount added
- Python library not used in class added
