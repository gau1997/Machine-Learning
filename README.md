# Machine-Learning
Bike Sharing System Regression Model
This project aims to build a regression model for predicting bike rental demand in a bike sharing system, based on historical data and relevant features.

Data->
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



Dependencies
The following Python libraries are required for running the code:

pandas
numpy
matplotlib
seaborn
sklearn


Usage
To run the regression model, you can use the Linear regression bike sharing assignment.ipynb Jupyter notebook. The notebook includes the following steps:

Loading and preprocessing the data
Exploratory data analysis (EDA)
Feature engineering
Splitting the data into training and testing sets
Building and training the regression model
Evaluating the model's performance

