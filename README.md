# Predicting-viewership-decline-for-a-digital-media-company
This project builds a linear model to predict the decline in viewership of a show launched by a digital media company.

## The dataset
The dataset tracks multiple aspects related to the show on a datewise basis which include: 
number of views of the show, number of visitors, number of views of the digital platform, number of ad impressions, whether there was a cricket match of India on that date and the lead character of the show.

## Feature engineering
Various features were derived from existing features which include:
1) Days since show started airing
2) Wether a particular date fell on a weekend or not
3) The weekday that fell on a particular date
4) A 1 day lag in viewership

## Model building
Various models are built to test significance of various features and calculate R^2 values for different combinations of features so as to evaluate the importance of different features in making predictions.

## Model evaluation
After running linear regression models using different sets of features as inputs, the following features were observed to lead to the highest R^2 values:
1) Whether it was a weekend on a particular date or not
2) Whether character A was the lead character in the TV show or not
3) Number of ad impressions

## Results
A final model with R^2 value of 80.3% and adjusted R^2 value of 79.5% was achieved. The predicted values along with actual values was plotted for visual clarity.
