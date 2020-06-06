+++
title = "get_dataframe()"
description = "Usage of the get_dataframe() method"
weight = 1
+++

The get_dataframe() method is the backbone of all the methods in Stonks. It serves as the only communication point with the internet, and is essential to the package. It will return the stock prices for the last 100 days.

## Usage
Here is how to call the method:

{{< code lang="python" >}}
import stonks
name = 'IBM'
df = stonks.get_dataframe(name)
#This would return stock prices for IBM for the past 100 days
{{< /code >}}


{{< alert style="warning" >}} The stock prices are returned as a pandas dataframe object {{< /alert >}}


### Parameters
#### name
The name parameter is the only parameter of the method. It determines what stock the data comes from. 

The name parameter accepts a String value, and must be in the proper stock name format.

Ex: 'MSFT' for Microsoft Inc.

