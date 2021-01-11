# Selecting a model

We got the data from PostNL, which was a dataset with:  
- Procesdag  

- Cust_id  

- Aantal pakketten  

- Aantal pakketten volgende dag  

Because this is a timeseries problem, there was only looked at timeseries models. We found [eleven good models for timeseries](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/), but then we had to select only 2 models, because we could not do eleven models in this short of a timespan. We discussed it with eachother and decided to do SARIMA and HWES. But then we told our instructors about this choice and they said we had to do mvlr, because then we could implement a lot of features and with SARIMA and HWES that was not an option. So we decided to do SARIMA an mvlr. 

