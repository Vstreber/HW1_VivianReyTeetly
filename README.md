[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GaZg1ATZ)
# hw01-R

## Description
The purpose of this homework is to practice assessing model fit, and to practice performing Linear Regression. 

## Instructions

### Part 1: Assessing Fit
Complete in-class activity 1: 

The candy-data.csv dataset (https://www.kaggle.com/datasets/fivethirtyeight/the-ultimate-halloween-candy-power-ranking/data) contains data on Halloween candies. 
The last two columns of the dataset are results of machine learning models. 

Column N, chocolate-prediction, is the output of a logistic regression. This column contains a 1 if the model predicted the candy is chocolate and a 0 otherwise. Column O, win-prediction, is the output of a linear regression. This column contains the model's predicted winpercent for each candy.

Write code to calculate the error rate for each of these predictions (separately, you will calculate the error of chocolate-prediction and the error of win-prediction).

Explain what your error rate indicates about each model. Do you think the model is a good fit? Why or why not? 

### Part 2: Simple Linear Regression 
Use the Auto dataset to complete this part of the assignment. 

Do the following:
1. Perform a simple linear regression with mpg as the response and horsepower as the predictor. Print the results of your regression and answer the following:
    * Is there a relationship between the predictor and the response?
    * How strong is the relationshoip between the predictor and the response?
    * Is the relationship between the predictor and the response positive or negative? 
What is the predicted mpg associated with a horsepower of 98? What are the associated 95% confidence and prediction intervals? 
1. Plot the response and the predictor. Show the least squares regression line on your plot. (You can use base R or ggplot for this.)
1. Produce the diagnostic plots for your least squares regression fit. 
    * Do you see any issues with the fit?  

## Submission and Grading
Please see the assignment overview from the course website for submission instrucitons and rubric. 