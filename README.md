<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Predicting Air Quality for Schools

Mapping the cause and effect of traffic and weather on air quality in schools and the school run

## Summary

As air pollution has proven to have a direct effect of children's health, specifically respiratory issues, parents and schools should be aware when levels are at their highest in an around the schools. Data is available, but usually this is after the fact - based on historical data captured. 
If we could predict when air quality will be worse, especially with local granularity, then schools could decide not to let children use an outdoor space on a specific day/time. They could decide to close classroom windows on an afternoon. Parents could choose to turn left instead of right out the school gates to avoid the worst pollution.
Combining traffic, weather and air quality data, a model could be created to predict future issues based on inputs for weather forecasts or traffic. The model could be used by schools who lack good air quality equipment to at least provide a traffic light system for the main pollutants.

## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* Air pollution is getting worse and affecting childrens health
* Approx 1/3 of childrens lives are spent going, being at or leaving school
* Air pollution is caused by urban immissions from industry and building, traffic, air traffic and is compunded or releived by weather
* Air quality data is not available everywhere
* Traffic data and weather data is available with good resolution
* Can we predict future air quality using a trained model with future traffic and weather features applied ?
* Using ML techniques, schools and parents could have a graphic model of air quality in and around a school
* That model could be used to change the route to school or to keep the chldren out the playground

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
<!-- 

 -->

## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?

Traffic data from multiple sources, including telematics and connected car data brokers
Weather data from Accuweather and public databases
Air Quality data from Kings College London

<!-- 


 -->

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

It cannot solve the accuracy of air quality monitoring, which can be very complex and not widespread. Need to rely on accurate data. 

Prediction cannot provide an absolute metric, but can provide a scale of bad, ok, good


## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

It's all about the data and the ability to prepare the data.

Main tasks are to identify the available sources and the detail of the data.

Find a data scientist to interpret that data to outline potential training data.

## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
<!-- 
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
 -->
