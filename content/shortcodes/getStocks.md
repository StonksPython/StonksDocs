+++
title = "getStocks()"
description = ""
weight = 6
+++

The getStocks() method is another alternative to get_series(). It takes in a list of names as well, but return the output as one, joined dataframe object.




## Usage
Here is how to call the getStocks() method :

{{< code lang="python" >}}
import stonks
names = ['IBM', 'AAPL', 'GOOGL']
stocks = stonks.getStocks(names)
#This would return stock prices for IBM, AAPL, and GOOGLE for the past 100 days
{{< /code >}}



### Parameters
### Parameters
#### *names*
The names parameter is a list of names. These names have to be formatted with the Stock Symbol, as the getStocks() implements get_series().