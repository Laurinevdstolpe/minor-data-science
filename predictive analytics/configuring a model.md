# Configuring a model

With the mvlr-model I first made a feature selection. I made a correlation matrix of the next features:
- [holidays]()
- [google trends]()
- [knmi weather data]()
- [weekdays]()

Here is the link were you can find the model I created for client 153 of our data: https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/MVLR%20klant%20153.ipynb
I chose the feature 'last day', because the correlation between 'the next day' and 'day before' was good (see:https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/mvlr%20feature%20weekdagen%20klant%20153.ipynb )
Initially the correlation between 'next day' prediction and 'holidays' wasn’t very good, but I tried it anyways to see if the model became better and it did, so I kept that feature as well.
