# Funnyball - A Baseball Statistics Predictor Inspired by Moneyball (2011)
In this project, we'll create a machine learning model that can predict a Major League Baseball player's future Wins Above Replacement (WAR) statistic for the next season based off current statistics using Python, Pandas, and Machine Learning.

We first download baseball players' season data using the `pybaseball` library and clean the data. Next, we perform feature selection with a sequential feature selector to identify the most relevant predictors for our machine learning model. Using these features, we train a ridge regression model to predict players' future season WAR. Finally, we evaluate the model's performance and measure error to improve its accuracy.

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
Please install the following Python libraries locally to run this project correctly:
* `os`
* `pandas`
* `numpy`
* `pybaseball`
* `scikit-learn`
