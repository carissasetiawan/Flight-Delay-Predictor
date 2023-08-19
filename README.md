# Flight-Delay-Predictor

# Problem
According to the BTS data, 1.4 out of 5.1 million flights were delayed nationwide in 2022. That’s about 20.5% of all scheduled domestic flights in the country. Delays affect both passengers and air carriers. For a carrier, they suffer financial losses, dissatisfaction of passengers, time losses, loss of reputation and bad business relations. The aim of this study is to build a flight delay predictor so both air carriers and passengers can have a better idea regarding their flight and plan incase a delay would happen.

# Research Question
Which airline and airport has the most delays? And can machine learning build a flight delay predictor?

# The Dataset
Data used: 
2015 Flight Delays and Cancellations (Flights.csv)
https://www.kaggle.com/datasets/usdot/flight-delays
The data set contains data from the Bureau of Transportation Statistics listing flights that are delayed, cancelled and their causes. It is specific to the airline, airport, delay cause and so on. 

# Methodology
Business understadning - understanding how a delay impacts the industry and how a flight delay predictor can be utilized.
Data understanding - undertsanding past data and the performance in the industry.
Data preparation & cleaning - cleaning the data and making it uniform so it can be used for machine learning.
Modeling - develop a machine learning model, I will be using logistic regression.
  Includes:
    - Discovering correlations
    - Further cleaning the data
    - One hot encoding 
    - Machine learning model development
Evaluation - make sure the model is performing at it's best
Deployment - deploy the model and test it's functionality!

# Exploratory Results
<img width="1106" alt="image" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/c55d1dc8-3f59-4282-8f0a-75f44c3479f8">
Figure 1. This graph shows the total flights of each airline and out of those how many are Yes (Delayed), No (Not delayed) and NaN (Cancelled).
The graph shows that almost half of Southwest (WN) and United (UN) flights are delayed. 

<img width="1152" alt="image" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/e29f1a71-218c-4a32-983e-844c7c2e97dd">
Figure 2. This graph shows the total flights of each origin airport and out of those how many are Yes (Delayed), No (Not delayed) and NaN (Cancelled). The graph shows the top 10 airport with most fights.
This graph shows that the top 3 busiest airports is: ATL, ORD and DFW. All the 3 airports have the same amount of delays.

<img width="1150" alt="image" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/0a03aa35-681c-47bb-97a9-f569aa096c7d">
Figure 3. This graph shows the flight delay minutes frequency.
The graph shows that the most frequent delays is within 0-20 minutes. 

<img width="1736" alt="image" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/560d687e-00c3-4538-86c0-37b787ca2cef">
Figure 4. This graphic shows a calendar format of flight cancels in 2015. 
The graph shows that December has a good amount of cancels, followed by January and February that has a strong amount of cancels.

# Predictor Demonstration
<img width="488" alt="Screen Shot 2023-08-19 at 5 32 48 PM" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/e728797e-979d-4a86-a26a-5a2c40d6dd52">

The model will ask a couple of questions regarding the passenger's flight from DEN to LGA.

<img width="407" alt="Screen Shot 2023-08-19 at 5 33 44 PM" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/9dcc65ab-2bfd-440c-a6d8-d5121942358f">

Proceed to input answers then run the following codes.

<img width="230" alt="Screen Shot 2023-08-19 at 5 34 13 PM" src="https://github.com/carissasetiawan/Flight-Delay-Predictor/assets/114559450/786afbc7-cb86-4874-9428-592b1b9fd285">

Last cell in the workbook shows the prediction result!

# Conclusion & Lesson Learned

I was able to discover facts about delays among flights in the US. I was also able to develop a flight delay predictor using one hot encoder and logistic regression machine learning. Through the process I learned a lot of valuable lessons which definitely improved my coding skills. I am eager to develop this model further and increase its capabilities to other airports and routes. And I would also be interested in updating the model using more recent data once provided by the DOT. 


