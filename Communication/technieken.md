# Techniques


*Cross validation*

De techniek “cross validation” is toegepast bij het regressie-model. Bij cross validation heb je een training, validatie en test gedeelte van je data. Het gebruikelijke bij cross validation is een groot percentage trainingset (bijvoorbeeld 90%) en een kleiner percentage testset (bijvoorbeeld 10%) (artikel: chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://link.springer.com/content/pdf/10.1007/BF00993106.pdf ). In dit onderzoek is ervoor gekozen om de cross validation zo toe te passen dat de trainingsset 60% (jaar 2015 tm 2017) is, de validatieset 20% (2018) is en de testset 20% (2019) is. De validatieset is erbij gekozen om te zorgen dat het model niet overfit op de traningsset. De percentages zijn zo gekozen, omdat dit data is waarbij je seizoenen hebt die niet zomaar gesplitst kunnen worden en er dus is hele jaren gesplitst moet worden. De trainingsset is gebruikelijk het grootst en de validatieset en testset daardoor in dit geval gelijk. 


*Schalen van data*

Bij het schalen van data wordt er gekeken naar waar de uitschieters liggen. In dit onderzoek is de data geschaald bij het regressie als bij de Time Series model. De standard scaler van Sklearn is daar toegepast om het gemiddelde van de data te bekijken (dit gemiddelde bevindt zich op een lijn met y-waarde 0) en daar een standaarddeviatie van (+-)1 op toe te passen. Alles boven die waarde van 1 of –1 is een piek. Bij de consistente pieken en dalen voorspelt het model beter, maar bij inconsistente pieken zoals December voorspelt het model slecht. Hieronder is een illus


*Multivariate lineair regression (mvlr)*

Multivariate lineair regressie wordt gebruikt wanneer er meerdere features een correlatie hebben met de feature die voorspeld wordt. Deze features zouden dan helpen bij het voorspellen van in dit geval het aantal pakketjes voor de volgende dag. De features die in het mvlr-model worden betrokken zijn: de dag van de week (1), de maand (2), het aantal pakketten van vorige week (3) en de feestdagen (4). Ter illustratie: 
