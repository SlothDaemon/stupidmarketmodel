## WHAT IS IT?

A stupid little time waster I wasted time making.
A fictitious stock of a fictitious company where you can buy and sell. Use the market-volatility slider to adjust the market's volatility. 
At any moment, you can buy a certain amount of stocks at the current price. Once you have more than 0 stock, you can sell it at the current price. The profit monitor monitors the amonut of profit you've made in total trading stocks.
If the stock hits 0, the model ends and you're bankrupt and all your stocks are converted into negative profit.

## HOW IT WORKS

Every tick the value variable increases or decreases with a normally distributed random number with an average of 10 and a standard deviation of 100 * market-volatility. Buying records the value at which you bought the stock, selling adjusts your profit accordingly to current market price and your bought price.

## HOW TO USE IT

Buy low and sell high, and pray that the company doesn't go bankrupt. Oh, and download NetLogo at https://ccl.northwestern.edu/netlogo/download.shtml

## THINGS TO NOTICE

NetLogo ties model speed to computational complexity. For the love of all that is holy,  slow down the model to the level indicated by the caret/arrow ^.

## EXTENDING THE MODEL

You could add shorting the stock. I'm not about to program that shitshow in.

## CREDITS AND REFERENCES

Creator: Sloth Demon. https://github.com/SlothDaemon/stupidmarketmodel
