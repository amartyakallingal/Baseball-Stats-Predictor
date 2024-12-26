# Funnyball - A Baseball Statistics Predictor Inspired by Moneyball (2011)
In this project, I created a machine learning model that can predict a Major League Baseball player's future Wins Above Replacement (WAR) statistic for the next season based off current statistics using Python, Pandas, and Machine Learning.

I first downloaded baseball players' season data using the `pybaseball` library and cleaned the data. Next, I performed feature selection with a sequential feature selector to identify the most relevant predictors for my machine learning model. Using these features, I trained a ridge regression model to predict players' future season WAR. Finally, I evaluated the model's performance and measured error to improve its accuracy.

**Project Steps Summarized**
* Download baseball season data
* Clean the data and prepare it for machine learning
* Run feature selection
* Create a machine learning model and estimate accuracy
* Improve accuracy

## File Overview
* `next_war.ipynb` - A Jupyter Notebook containing code to clean player data and predict next season's WAR.
* `batting.csv` - A CSV file with all the player data during and between the 2002 and 2022 MLB seasons.

## Local Setup and Installation
The following Python libraries are necessary to run this project correctly:
* `os`
* `pandas`
* `numpy`
* `pybaseball`
* `scikit-learn`
