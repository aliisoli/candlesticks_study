# Candlesticks_Study
Statistical study of accuracy of candlestick patterns in predicting the stock market and their occurrence 

In technical analysis, a candlestick pattern is a movement in prices shown graphically on a candlestick chart that some believe can predict a particular market movement. The recognition of the pattern is subjective and programs that are used for charting have to rely on predefined rules to match the pattern. There are 42 recognised patterns that can be split into simple and complex patterns.

In this study, we analyze the most commonly used candlestick patterns by traders to choose a position on a stock. 
To do this, we look at the historical trading information of popular FAANG stocks (Facebook, Amazon, Apple, Netflix, Google)
The patterns are first identified in the historical data, and the following trend is compared against the prediction of the pattern.
A criteria for scoring the prediciton accuracy of candlesticks is defined and applied. 
The bias in the data is discussed and mitigated, and a correction is implemented in the scoring system to account for the bias.

At the end, the occurence of each candlestick pattern is plotted, as well as their accuracy score.

The whole process is then implemented in a single function to simplify analyzing other stocks.
This function was used to repeat the process on other stocks and the results were plotted.

Interesting conclusions were drawn at the end. 

Would love to hear your thoughts and comments
