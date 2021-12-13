# Bike Sharing: Multiple Linear Regression
> Boombike is a bike sharing provider which provides a bike sharing service in which bikes are made available for shared use to 
individuals on a short term basis for a price or free. The company wants to understand the factors affecting the demand for these 
shared bikes in the American market. 
The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- This project applies the multiple linear regression model to predict the bike demands based on different impacting factors.
	Steps involved in perfroming the linear regression is as below.
	Step1: Reading and Understanding the data
	Step2: Visualizing the data to make some initial inferences
	Step3: Prepare data for linear regression model creation
	Step4: Splitting the Data into Training and Testing Sets for unsupervised learning
	Step5: Feature selection and Build the linear model
	Step6: Residual analysis of training data
	Step7: Make predictions using the final model
	Step: Evaluate the model

- The model predicts the demand for shared bikes with the available independent variables. The model will be used by the Boombikes management to understand 
  how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
  Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
-Equation for best fitted linear regression line is: 
cnt = 0.1259 + (yr × 0.2329) - (holiday × 0.0987) + (temp × 0.5480) − (windspeed × 0.1532) + (summer × 0.0881) + (winter × 0.1293) − (weathersit2 × 0.0784) − (weathersit3 × 0.2829) + (month_9 x 0.1012)
where, 
	cnt = count of total rental bikes including both casual and registered
	holiday = whether day is a holiday or not
	temp = temperature in Celsius
	windspeed = wind speed
	weathersit2 = Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
	weathersit3 = Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
	month_9 = September month

- Based on above equation, "temp", "weathersit3" and "yr" are the most influencial variables for bike rental counts.


## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- sklearn - version 0.24.1


## Contact
Created by [@saketbihari] - feel free to contact me!