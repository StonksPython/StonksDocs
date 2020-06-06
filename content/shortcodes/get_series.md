+++
title = "get_series()"
description = "Method that collects multiple dataframes at once"
weight = 2
+++

The get_series() method collects multiple dataframes, and organizes them into a neat list.


## Usage
Here is how to call the method:

{{< code lang="python" >}}
import stonks
names = ['IBM', 'AAPL', 'GOOGL']
series = stonks.get_series(names)
#This would return stock prices for IBM, AAPL, and GOOGLE for the past 100 days
{{< /code >}}

### Parameters
#### *names*
The names parameter is a list of names. These names have to be formatted with the Stock Symbol, as the get_series() implements get_dataframe().