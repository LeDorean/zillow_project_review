# Zillow Project Review

This repository contains a reviewed approach to a project I already worked on in an attempt to improve results.

The scope of the project is to determine the best US areas to invest in real estate through the use of Time Series Modelling using Zillow housing data.

I wanted to areas that had stable house prices with high returns. To do that I took the average of standard deviation of all my zipcodes and decided that the bottom half qualified as stable prices; next I took the average monthly return on all my zipcodes that were in the lower half of standard deviation. Lastly I took the top 5 areas that had the best return 

#Modeling
The first part of my modelling process I just wanted to get 5 baseline models for my zipcodes. I decided to use a SARIMA model since I detected a seasonality component to house prices.

One big thing I did was try to improve my baseline model, which I did by using the gridsearch function that returns the best parameters for my model. After I implemented my best params into my models, there was still something slightly off in my models. I went deeper to try and fix this problem but with no luck.

#Best 5 zipcodes
Model results provided my best 5 zipcodes 2 from Houston Texas, 1 from Pfulugerville Texas, 1 from El Paso Texas and lastly 1 from Nashville Tennessee. These turned out to have great returns and were very stable.


#Conclusion and future work
I would advise future investors in investing into the zipcodes. According to my models investing in these areas can make a great return on investment over the next 4 years at around 50% rate. 

Future work will include a bigger focus on the southern states and see why they are more stable than other states in America. For now my guess is that the tax laws might influence the housing prices. 
