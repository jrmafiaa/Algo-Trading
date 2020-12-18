# Algo-Trading
Algorithmic Stock Trading Program with Python


## About 
This is a group project for the course Skills: Programming - Introduction Level at the University of St.Gallen. The project is done by chrissib and jrmafiaa. Due to our common interest in financial markets, we decided to develop a program that buys and sells shares on the markets using a selected trading strategy.

## Requierments  
The program is coded 100% with Python

In order to run it, the following libraries need to be installed:    
* datetime
* Pandas
* pandas_datareader
* matplotlib.pyplot
* numpy

## Description

This program is written to trade stocks due to our limitations regarding getting the newest information. This program past orientated and focuses on the past 365 Days and what earnings a user could have made with the trading strategy and a selection of the 3 specific stocks with a chosen amount of money. To get the program run in real-time also real time data from the markets is needed. That information could be collected for example with tools like quandl. 

## Diffrent Parts in our code  
* Import
* Trading Strategy / Creating Signals
* Plot and Development of the 3 Stocks
* Using Signals in a Simulation
* Plot simulated Portfolio


### Import
The first step in the program need to havr acess to diffrent python libaries. Unfrurtnally we don't have a Key to provide the program with real-time data from a tool like quandl. That is why the program is focused on past decisions. 


### Trading Strategy
The 3 stocks used in the Simulation are Apple, Microsoft, and BionTech. In the code, we wrote down as a comment some more examples that could be used. In practice, every public listed stock with a ticker symbol could be used in this program.


#### Momentum Strategy 
The momentum strategy is first used by Richard Driehaus. The Key is that the strategy realizes price based signals. With the strategy, we should buy stocks if they in the rising and sell them if they reached their peak. To recognize those trends the trader has to find signals for buy and sell actions. Our goal would be that we buy the stocks in short term uptrends and sell them if they reached their momentum. That our strategy will work we should choose three stocks with high volatility and a high trading volume. To see the signals from the momentum strategy we have to establish two time frames, a long term, and a short term. In our program, we set those short = 20 days and long = 100 days. The time frames could be changed to optimize the trading outcomes.

#### Creating Signals
Our start situation is now that the long-term window is higher than the short-term window. If those change so the short window of stock gets higher than the long window we create a buying signal for the specific stock. When now the short and long window switch again we create a selling signal. 

### Plot and Development of the 3 Stocks
After we created every necessary information we will visualize them in three charts, one for every chosen stock. Here we can see the development of the stock (red line), the short-term moving average (blue line), and the long-term moving average (orange line). The pyramids will show the discovered buy and sell signals. The magenta one will visualize a buy signal and the black one will visualize a sell signal. 

### Using Signals in a Simulation
To test our strategy we set up a simulation in a portfolio over the past 365 days. We set up the portfolio with an initial capital of 300,000 USD. The initial capital can be changed to see the outcome with different inputs. The simulation counts all profits and losses and will add value to the portfolio.

### Plot simulated Portfolio
To visualize the development of our invested money we will plot at the end the value of our portfolio. Here can the user of the program sees how the trading strategy would turn out over the year. 
###  
###   
###  
## Sources 

* https://github.com/datacamp/datacamp-community-tutorials/blob/master/Python%20Finance%20Tutorial%20For%20Beginners/Python%20For%20Finance%20Beginners%20Tutorial.ipynb
* https://www.youtube.com/watch?v=-MHhA-Y3DSk
* https://www.youtube.com/watch?v=SEQbb8w7VTw
* https://www.investopedia.com/trading/introduction-to-momentum-trading/#:~:text=Momentum%20investing%20is%20a%20trading,securities%20start%20to%20lose%20momentum.
* https://slsp-hsg.primo.exlibrisgroup.com/permalink/41SLSP_HSG/uq0rei/cdi_gale_infotracacademiconefile_A66964111 
