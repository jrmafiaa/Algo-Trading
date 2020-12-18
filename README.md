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

This program is written to trade stocks due our limitations regarding getting the newest informations is this program past orientated and focus on the past 365 Days and what earnings a user could have made with the trading strategy and a selection of the 3 spezific stocks with a zirtent amount of money. To get the program run in real time also real time date from the markets is needed. Those infromations could be colleccted for example with tools like quandl. 

## Diffrent Parts in our code  
* Import
* Trading Strategy / Creating Signals
* Plot and Development of the 3 Stocks
* Using Signals in a Simulation
* Plot simulated Portfolio


### Import
The first step in the programm is that we will collect data from diffrent stocks. Unfrurtnally we don't have a Key to provide the programm with real time data from a tool like quandl. That's why it is more focused on past decisions. 


### Trading Strategy
The 3 stocks used in the Simulation are Apple, Microsoft and 3M. In the code we wrote down some more examples that could be used. In practise every public listed stock with an ticker symbol could be used in this program. 


#### Momentum Strategy 
The momentum strategy is first used by Richard Driehaus. The Key is that the strategy realizes price based singals. With the strategy we should buy stocks if they in the rising and sell them if they reached their peak. To reconise those trends the trader have to find signals for buy and sell actions. Our goal would be that we  buy the stocks in short term uptrends and sell them if they reached their momentum. That our strategy will work we should choose three stocks with a high volatility and a high trading volume.   

#### Creating Signals

### Plot and Development of the 3 Stocks
 
### Using Signals in a Simulation

### Plot simulated Portfolio
###
###
###
## Sources 

* https://github.com/datacamp/datacamp-community-tutorials/blob/master/Python%20Finance%20Tutorial%20For%20Beginners/Python%20For%20Finance%20Beginners%20Tutorial.ipynb
* https://www.youtube.com/watch?v=-MHhA-Y3DSk
* https://www.youtube.com/watch?v=SEQbb8w7VTw
* https://www.investopedia.com/trading/introduction-to-momentum-trading/#:~:text=Momentum%20investing%20is%20a%20trading,securities%20start%20to%20lose%20momentum.
