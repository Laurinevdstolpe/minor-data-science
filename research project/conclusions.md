# Conclusions

The research question of this project was: How can PostNL apply machine learning models, to predict how many parcels are being processed the next day? 

In this project we figured out that the mvlr-model and the SARIMA model are good models to predict the number of parcels for the next day. The mvlr model has an r2-score of 0,86, which is quite a good model. It delivers good results for an average day of the week, but when it comes to inconsistant days like christmas it is definitly not optimal. [Here](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/research%20project/AFBEELDING%20CONCLUSIE.png) you can see the results. Sarima has a little more trouble with predicting the number of parcels, therefor it has an r2-score of 0,34. [Here](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/research%20project/2021-01-12%20(16).png) you can see the results visualized. So to some up, PostNL can apply machine learning to predict the number of parcels for the next day by using the mvlr-model and SARIMA-model for every client individually. They can improve these models for example by adding more features like google trends to the mvlr-model. 




