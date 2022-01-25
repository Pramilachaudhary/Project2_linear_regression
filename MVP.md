# Predicting Domestic Revenue of a Movie

**Objective:** 
  
  Creating a linear regression model to predict domestic Revenue of a movie based on different features.

**Methodology:** 
  
 1. Scraped 1200 movies from boxofficemojo.com and worked on 459 data points because I was only able to get movie budget for 459 movies from the same website
 2. created the data frame from all the srcaped data and did some cleaning in order to get the necessary values.
 3. Splited data into train and test data frames and predicted the movie revenue using Linear Regression model.
  
**Output:** 

for Linear Regression model:
used 459 data points
features used are: movie_budget, widest_release

Prediction on train data set = $34648693.33406599
Prediction on test data set = $34762487.0779915


<img width="774" alt="Screen Shot 2022-01-24 at 3 40 21 PM" src="https://user-images.githubusercontent.com/89863226/150883723-e9197c9e-d6e4-4001-93b6-21ad907fe499.png">

Further in the analysis  I would add more features like running_time, year, MPAA rating to make the model unbias and will
creating the models with cross validation and regularization in order to determine best model to fit data.
