# Algo-Trading
Algorithmic Stock Trading Program with Python


## About 
This is a group project for the course Skills: Programming - Introduction Level at the University of St.Gallen. The project is done by chrisisb and jrmafiaa. Due to our common interest in financial markets, we decided to develop a program that buys and sells shares on the markets using a selected trading strategy. 

## Requierments  
The program is coeded 100% with Python

In order to run it, the following libraries need to be installed:    
* datetime
* Pandas
* pandas_datareader
* matplotlib.pyplot
* numpy

## Description

This program is written to trade stocks

The code is plit into following parts: 
* Import
* Trading Strategy / Creating Signals
* Plot and Development of the 3 Stocks
* Using Signals in a Simulation
* Plot simulated Portfolio


#### Collecting Data 
The first step in the programm is that we will collect data from diffrent stocks. Unfrurtnally we don't have a Key to provide the programm with real time data from a tool like quandl. That's why it is more focused on past decisions. 


#### Choosen Stocks 
The 3 stocks used in the Simulation are Apple, Microsoft and 3M. In the code we wrote down some more examples that could be used. In practise every public listed stock with an ticker symbol could be used in this program. 


#### Momentum Strategy 
The momentum strategy is first used by Richard Driehaus. The Key is that the strategy realizes price based singals. The Key behind this strategy is to buy stocks if they in the rising and sell them if they reached their peak. To reconise those trends the trader have to find signals for buy and sell actions. 


#### Backtester 

## Sources 
* https://www.quandl.com/ 
* https://github.com/datacamp/datacamp-community-tutorials/blob/master/Python%20Finance%20Tutorial%20For%20Beginners/Python%20For%20Finance%20Beginners%20Tutorial.ipynb
* https://www.youtube.com/watch?v=-MHhA-Y3DSk
* https://www.youtube.com/watch?v=SEQbb8w7VTw
