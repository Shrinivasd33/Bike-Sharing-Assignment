# Bike Sharing Predictors
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

   1. Which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands


<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US based bike-sharing system wants to know
   1. Which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands
- We need to find the predictors and their effect for count(total bike shared) so that company can take an informed decision.
  A linear regression model is used here.
- Dataset - Bike sharing dataset is used. 
  - day.csv
    =========================================
    Dataset characteristics
    =========================================	
    day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Technologies Used
- python - 3.10.0
- numpy - 1.25.2
- pandas - 2.0.3
- matplotlib - 3.7.2
- seaborn - 0.12.2
- sklearn - 0.24.2
- statsmodels - 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
