# Sleep_Quality_Analysis
To explore the causal relationship between the number of sedentary minutes for an individual recorded and their sleep quality

## Introduction
The aim of our project is to examine if there is a causal relationship between the number of sedentary minutes for an individual recorded and their sleep quality. In our case, total sleep time in bed is used as a proxy for sleep quality. In order to determine if there exists a causal effect, we used methods varying from a simple linear model regression to a panel regression to do so. 

## Files Included:
dailyActivity_merged.csv

sleepDay_merged.csv

EEA Final.Rmd

## Important Variables in Dataset:
TrakcerDistance - the distance traveled recorded by Fitbit
VeryActiveDistance - the amount of distance where the user was highly active (high heart rate)
VeryActiveMinutes - the total minutes where the user was highly active (high heart rate)
SedentaryMinutes - the total minutes where the user stays sedentary
Calories - amount of calories burned
SedentaryTreatment - whether the user has a sedentary minutes higher than average American's sedentary minutes
SedentaryMinutes: SedentaryTreatment - used to examine how the marginal changes if a user has a sedentary minutes higher than average American's sedentary minutes
TotalMinutesAsleep - our target variable, total minutes the user was asleep


## Data Source:
FitBit Fitness Tracker Data from Kaggle - https://www.kaggle.com/datasets/nurudeenabdulsalaam/fitbit-fitness-tracker-data?select=dailyActivity_merged.csv

## Literature Links:
(1) https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6352043/

(2) https://www.washingtonpost.com/national/health-science/the-big-numberthe-average-us-adult-sits-65-hours-a-day-for-teens-its-even-more/2019/04/26/7c29e4c2-676a-11e9-a1b6-b29b90efa879_story.html

(3) https://www.hermanmiller.com/research/categories/white-papers/can-chair-lower-office-stress/

(4) https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6082791/ 


