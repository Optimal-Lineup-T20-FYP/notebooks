This repository contains all the ipynb notebooks. 


This project aims at creating a rating mechanism for cricketers. This idea of impact rating is inspired by the Weighted Runs Above Average metric in baseball. 
With the help of 651000 deliveries available on cricsheet.org, a pipeline was built to clean, preprocess, feature engineer, and model the data. 

The core idea is to predict the expected outcome in each ball of a T20 game based on the match situation using the previously available outcomes.
The match situation (total runs scored by the team, balls remaining, wickets remaining, striker's score, partnership etc) is used to predict the number of runs scored in a particular ball. A linear regression predictive model is used. Once an outcome is predicted, it is compared to the actual outcome in the test set to calculate the impact of the player.

For example, using past data, when we predict that 2 runs are being scored by an average batter in that particular match situation and the batter in the current game scores 4 off that ball, the impact is +2 runs for that ball. This is accumulated over a period to understand how many runs a player would contribute per game when compared to an average player. 

Project impact:

Designed a player rating mechanism to quantify a player’s contribution in Twenty20 cricket matches, and programmed
an integer optimization algorithm that enhanced team selection strategies by 53.63 percent.

Extracted, transformed, and analyzed the data of 651k balls across 2644 T20 matches to gain actionable insights.

Developed a Runs Above Average predictive machine learning model using linear regression to predict the outcome for
each ball based on the match situation and reduced prediction error by 54.55 percent compared to the baseline model.
