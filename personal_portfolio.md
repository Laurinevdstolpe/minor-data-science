# Personal portfolio of Laurine van de Stolpe (Parcel)



## General information

**Student name:** Laurine van de Stolpe

**Student number:** 18122256

**Course:** applied data science minor

**Instructors:** Tony Andrioli;  Brian de Keijzer;  Brian de Keijzer;  Geertruida in 't Veld;  Ruud Vermeij;  Jeroen Vuurens;

**Task definition:** This portfolio summerizes my individual work and effort for the parcel project of the applied data science minor at the the hageu university. In the parcel project we aim to predict the number of parcels for the next day.



## Content

**1.1 DataCamp course**

**1.2 Reflection and evaluation**

**2. Research project**

**3. Predictive Analytics**

**4. Domain knowledge**

**5. Data preprocessing**

**6. Communication**


___



### 1.1 DataCamp Course

**Datacamp courses I have finished:**

[1. intermediate python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(11).png)

[2. manipulating DataFrames with pandas](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(2).png)

[3. pandas functions](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(3).png)

[4. introduction to data visualization in python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(4).png)

[5. introduction to python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(5).png)

[6. python data science toolbox (part 1)](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(6).png)

[7. python data science toolbox (part 2)](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-09-29%20(7).png)

[8. data types for data science in python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-10-05.png)

[9. cleaning data in python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-10-18.png)

[10. preprocessinghttps for machine learning in python](https://github.com/Laurinevdstolpe/minor-data-science/blob/main/2020-11-08.png)



### 1.2 reflection and evaluation   (400 woorden en STARR method)

(Reflection on own contribution to the product) //

(Reflection on own learning objectives) //

(Evaluation on the group project as a whole) //



___



### 2. Research project

**(Task definition)** Rick and I sat together to clearly discribe the context and research question a few times. The first time we created a research question we came to the following: How many parcels do we predict every client will process the next day?
We had to adjust the reserch question after that, because we knew what the problem owner wanted, but not how we would get there. The problem owner said that we needed to be more precise, so implement the fact that we were working with machine learning models. 
So after that we created the next research question: which machine learning model will result in the best prediction for the the amount of packages for the next day, based on the given data by PostNL? 
Then I had to look at the subquestions that could give an awnser to this research question and based them on the workshop we had from Tony Andrioli about the research methods. So I discussed it with Rick and took one from library (literature study): Wat zijn de meest gangbare machine learning modellen voor het voorspellen van tijdsreeksen?, workshop (prototype): Welke modellen zijn het best toepasbaar op de gegeven data?, field (data analyse): Welke data kan worden gebruikt voor het verbeteren van de voorspelling?, lab (data analyse): Welke data kan worden gebruikt voor het verbeteren van de voorspelling? 
Now that the subquestions were made, Rick and I started to take a second look at the research question and saw that it wasn't an open question, so we made a third research question and decided that our product owner had to decide which he thought was best. That last reseacht question was:	Hoe kan PostNL machine learning modellen toe passen, om te voorspellen hoeveel pakketten er voor de volgende dag verwerkt moeten worden? 
And this is the one our product owner thought was best so we made that our final research question. 
(You can see this in the onderzoeksplan in teams by planning.)



**(Evaluation)** // 



**(Conclusions)** //



**(Planning)** In the beginning of this project I said that we should do a daily standup every day, except for weekends, but the majority of the group didn't agree and said they didn't want to be awake that early every day. So we decided to try three times a week (monday, wednesday and friday), but after we had our meeting with Gerda we knew that wasn't going to work so we changed it to my proposal and do it five times a week. Rick and I sat together for a few times to plan the whole project.
In week 7 I came up with the idea to do one sprint a week where we come together on monday and figure out what we want to do that week, we call this sprint planning. Rick than said that we also needed a retrospective, so we have been doing this ever since. (You can find this in the map Retrospective under Parcel).
Also I came up with the plan to do literature study till week 8 and then begin with the models that we found in the literature.
Rick and I described an overview for the rest of the teammembers, so how many weeks we have till the final presentation and what we should do in that time.
(You can see what we did in the onderzoeksplan in teams by planning.)



___



### 3. Predictive analytics

**(Selecting a model)** As a group we decided that we would split up in two groups of three. My group had to create a multivariate linear regression model. We decided this model was the right model for our problem, because I did literature study on it (https://otexts.com/fpp3/) and it came out as a good model to start with. It was also recommended by our instructors. 



**(Configuring a model)** Here is the link were you can find the model I created for client 153 of our data: https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/MVLR%20klant%20153.ipynb
I chose the feature 'last day', because the correlation between 'the next day' and 'day before' was good (see:https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/mvlr%20feature%20weekdagen%20klant%20153.ipynb )
Initially the correlation between 'next day' prediction and 'holidays' wasn’t very good, but I tried it anyways to see if the model became better and it did, so I kept that feature as well. 



**(Training a model)** So when I trained the model I ran it a couple of times to see when the model was at its best. So for example I tried to take 2015 to 2018 as training set and then testing it on 2019. Then changing it to training: 2015 to 2019 month 11 and testing it on 2019 month 12. Eventually it ran best with 2015-2019 month 7 and testing it on 2019 month 7 to 2019 month 11. see: https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/MVLR%20klant%20153.ipynb



**(Evaluating a model)** We take a look at the difference between the model above and this model: https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/AR%20klant%20153%20(op%20de%20data%20van%20een%20week%20terug).ipynb
We can see that they are both pretty good at predicting the amount of packages for the next day. 



**(Visualizing the outcome of a model)** See links: https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/MVLR%20klant%20153.ipynb and https://datascience.hhs.nl:8888/user/18122256/notebooks/parcel/stolpe_l/AR%20klant%20153%20(op%20de%20data%20van%20een%20week%20terug).ipynb



___



### 4. Domain knoweldge

**(Introduction of the subject field)** Here is what I wrote as introduction to the subject field in Dutch:
PostNL is een internationaal dienstverlener in post, pakketten en e-commerce gerelateerde zaken. In dit onderzoek wordt er alleen aandacht gegeven aan de pakketten van PostNL in Nederland. Bij het verwerkingsproces van deze pakketten gaat het al snel om duizenden pakketten per dag. Om er zeker van te zijn dat alle pakketten op tijd worden verwerkt, moet de organisatie ten alle tijden over genoeg capaciteit, betreft het aantal werknemers, beschikken. Aan de hand van allerlei verschillende factoren kunnen er echter inconsistenties ontstaan in het aantal pakketten dat verwerkt moet worden. Dit vormt een probleem, aangezien een onverwachte stijging in het aantal pakketten druk legt op het aantal werknemers binnen dit verwerkingsproces, dat uiteindelijk kan leiden tot vertragingen. 
Om ervoor te zorgen dat de organisatie beter kan anticiperen op onverwachte situaties, wil de organisatie hun verwerkingsproces volledig automatiseren. Van het verzamelen van de pakketten tot het leveren van de juiste pakketten bij de juiste klant. Een bijdrage aan de overstap naar een volledig autonoom proces, is de ontwikkeling van een model dat dagelijks het aantal te verwerken pakketten kan voorspellen. Voordat deze ontwikkeling plaats kan vinden, is echter eerst een onderzoek nodig naar de toepassing van de benodigde machine learning modellen.  
Tot nu toe is er nog weinig onderzoek gedaan naar een voorspellend model voor pakketten. De hypothese is dat er een aantal benodigde machine learning modellen uitkomen die het probleem van PostNL kunnen helpen. Uiteindelijk wordt de data die PostNL uitgeeft beschermd door de namen van klanten niet uit te geven, waardoor er een onderzoekskloof ontstaat. Dit deel van de data zou namelijk het onderzoek kunnen helpen bij het vinden van het beste model voor ieder individuele klant.  
De onderzoeksvraag luidt: Hoe kan PostNL machine learning modellen toe passen, om te voorspellen hoeveel pakketten er voor de volgende dag verwerkt moeten worden? 
In dit onderzoek wordt er een geheel nieuwe benadering genomen, er is namelijk geen vooronderzoek.  



**(Literature research)** I found eleven relevant articles about machine learning in predicting things. But not all of them are still in our shared document, because we had to select two of them, but here are five (the first two I selected as best):
https://otexts.com/fpp3/
Google scholar term : forecasting

https://d1wqtxts1xzle7.cloudfront.net/53164853/Forecast_of_the_Commercial_UAS_Package_Delivery_Market-_2017.pdf?1495045023=&response-content-disposition=inline%3B+filename%3DForecast_of_the_Commercial_UAS_Package_D.pdf&Expires=1607532607&Signature=V1JPWPgXCNE8SiwJNRrmo05JkCHN5hkYBW1119is4UwhI4nNaMrHXlCvowty3sv-~RrHwnuGTukmOd2IjB71gRs4x9URQLqUdxCSm7grt1aRVwEFTFEv8ZAtGNFRiYLz8UagqOUi~5s2cArPcefxsQPXTGtk5lHByzw3EWFO6-~GY2mWHtCcRfaW1CETJzYVNwMBVCRQYTpixb9O6UassIm9pl0p8ZYiU9cmmzD3STzkipf4HNzprho7HORnVk44fKRpOyYKZeR~CyRv0yhK39kOMr9v0F-Ry~zE9Ypkl1fIWRu2zaahjm~nc~gIpezIkx7tyx3GljEfTKhusjCr6A__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA
Google scholar term: how to forecast package delivery 

https://patents.google.com/patent/US7676404B2/en 
Google scholar term : forecasting package delivering 
 
https://books.google.nl/books?hl=nl&lr=&id=8FppWLEFHU8C&oi=fnd&pg=PA4&dq=techniques+for+time+series&ots=b4Yqk5UHtt&sig=DhC0AqOOX72d90NDCVdaTrpkwj8&redir_esc=y#v=onepage&q=techniques%20for%20time%20series&f=false 
Google scholar term: time series analyses 
 
https://link.springer.com/chapter/10.1007%2F978-3-642-00296-0_5 
Google scholar term: pearson correlation 



**(Explanation of terminology, jargon and definitions)** You can find this on teams when you go to parcel – literatuur en referentiemateriaal – Glossary.



___



### 5. Data preprocessing

**(Data exploration)** //
**(Data cleaning)** // In the weekends (of the data) there were a lot of zero-values, so I had to filter those out.
**(Data preporation)** // With client 4 for example I needed to filter the first two years out, because it became a client after that.
**(Data explenation)** //
**(Data visualization)** //



____



### 6. Communication

**(Presentations)** I prepared and gave 1 presentation on friday the 25th of september. 
You may have noticed that since I changed the formatting of the slides this presentation, everybody is re-using that format.
I gave it a ogange look and put the PostNL logo on every slide so it is obvious what group we are.
I got two questions and anwsered them myself, for the rest I only got good feedback from the problem owner and the supervisors. 
Then I prepared and gave another presentation on monday the 16th of november. The questions that were asked here, I awnsered myself. I got a comment that we had to take a look at the day before and not the week before when we predict something. This was a usefull comment of Jeroen Vuurens. For the rest I was told that we had to tell more about what we train, validate and test our model with. Also usefull. For the rest there were no remarks. 



**(Writing paper)** Writing paper: I made an overview and wote the introduction for so far, here you can see what I wrote in Dutch:
Overzicht (overview)
Titel: Een titel is specifiek, duidelijk anders dan andere, niet te lang niet te kort, geen generale titel, denk aan wat mensen intypen in google scholar.  
Abstract (in 1 zin al deze subs beantwoorden): motivatie: waarom boeit ons het resultaat? probleemstelling: wat is het probleem en wat is het bereik van het werk? Aanpak: wat is er gedaan om het probleem op te lossen? Resultaat: wat is het antwoord op het probleem? Conclusie: wat zegt het antwoord ons? (In verleden tijd! Geen referenties)  
•	Introductie  
(van probleem tot oplossing)  
Onderzoeksvraag beantwoorden.  
Slide 9!!!  
•	Technieken  
Illustraties van het algoritme.  
Slide 10!!!  
•	Methoden  
Wat was het probleem? Beantwoorden.  
Doel beschrijven.   
In verleden tijd schrijven  
Slide 11!!!  
•	Resultaten  
Wat zijn de resultaten?  
In verleden tijd schrijven.  
Moet duidelijk zijn!  
Slide 12!!!  
•	Discussie  
Slide 13!!!  
Lijst van referenties.  (slide 14!!!)  
•	Conclusie  
Wat betekenen je vindingen?  
Verwijzen naar opening.  
  
Om ons te beoordelen (slide 17,18, 19, 20, 21)  

Introductie (introduction)
PostNL is een internationaal dienstverlener in post, pakketten en e-commerce gerelateerde zaken. In dit onderzoek wordt er alleen aandacht gegeven aan de pakketten van PostNL in Nederland. Bij het verwerkingsproces van deze pakketten gaat het al snel om duizenden pakketten per dag. Om er zeker van te zijn dat alle pakketten op tijd worden verwerkt, moet de organisatie ten alle tijden over genoeg capaciteit, betreft het aantal werknemers, beschikken. Aan de hand van allerlei verschillende factoren kunnen er echter inconsistenties ontstaan in het aantal pakketten dat verwerkt moet worden. Dit vormt een probleem, aangezien een onverwachte stijging in het aantal pakketten druk legt op het aantal werknemers binnen dit verwerkingsproces, dat uiteindelijk kan leiden tot vertragingen. 
Om ervoor te zorgen dat de organisatie beter kan anticiperen op onverwachte situaties, wil de organisatie hun verwerkingsproces volledig automatiseren. Van het verzamelen van de pakketten tot het leveren van de juiste pakketten bij de juiste klant. Een bijdrage aan de overstap naar een volledig autonoom proces, is de ontwikkeling van een model dat dagelijks het aantal te verwerken pakketten kan voorspellen. Voordat deze ontwikkeling plaats kan vinden, is echter eerst een onderzoek nodig naar de toepassing van de benodigde machine learning modellen.  
Tot nu toe is er nog weinig onderzoek gedaan naar een voorspellend model voor pakketten. De hypothese is dat er een aantal benodigde machine learning modellen uitkomen die het probleem van PostNL kunnen helpen. Uiteindelijk wordt de data die PostNL uitgeeft beschermd door de namen van klanten niet uit te geven, waardoor er een onderzoekskloof ontstaat. Dit deel van de data zou namelijk het onderzoek kunnen helpen bij het vinden van het beste model voor ieder individuele klant.  
De onderzoeksvraag luidt: Hoe kan PostNL machine learning modellen toe passen, om te voorspellen hoeveel pakketten er voor de volgende dag verwerkt moeten worden? 
In dit onderzoek wordt er een geheel nieuwe benadering genomen, er is namelijk geen vooronderzoek.  
 
Dit moet er nog in, maar kan nu  nog niet: 
(sketch the intent of the own work) 
(outline important characteristics and results of your own work) 
(give a brief outlook on the structure of the paper) 

