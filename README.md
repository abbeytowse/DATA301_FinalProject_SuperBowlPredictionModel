# DATA301_FinalProject_SuperBowlPredictionModel

## Purpose of each file: 

### 1) *data_collection_&_cleaning.py: 
#### The purpose of this file is to create the 'football.csv' file included in this repository. This file is created through a series of webscraping and data cleaning. 
##### *This file takes a long time to run due to the amount of data being scrapped and cleaned. 

### 2) data_exploration.py:
#### The purpose of this file is to create visualizations to start to determine which NFL stats have an influence on whether or not a team wins the Super Bowl.

### 3) machine_learning.py: 
#### The purpose of this file is to determine the best data model (ie combination of variables) to predict Super Bowl winners. The best model is selected based on the best f1 and k value. 

## Conclusion: 

### Our model was reasonably accurate based on the fact that for every season from 2002 to 2021 the model had the actual Super Bowl winner in its prediction of potential winners. 

### The goal of our project was to determine who would win the Super Bowl in the 2022 season. The conclusion of our initial project was that based on the 2022 NFL season as of December 2022, abd the predicted winner of the Super Bowl at the time would be the San Francisco 49ers or the Buffalo Bills. In retrospect, we now know the winner of the 2022 Super Bowl was the Kansas City Chiefs. To further test our model, the model was ran again after the 2022 NFL season was completed (now that all the season's stats are finalized) to see if the model was capable in predicting the correct winner. Unfortunately, this is the part where our model failed; the model predicted no teams had a probably of winning the 2022 season. This sparks a couple of additional research questions: 

#### 1) What is it about the data in 2022 that lead no winners to be predicted. Are variables used in the data model drastically different in the 2022 season compared to all other seasons? 

#### 2) Would a different data model yield accurate results for the 2022 season as well as all other seasons. 

#### 3) If we retrained the model including the 2022 season, would the model be more accurate in its prediction for all other seasons? Would the model be able to more accurately predict the results of the 2023 season than the current model? 
