## Predicting NBA CHampions with Machine Learning
![Screenshot 2025-04-23 220921](https://github.com/user-attachments/assets/f64d5fa5-3b8c-48a8-9299-541eabca1505)

## Overview:
This project uses historical NBA team statistics to predict the 2025 NBA CHampion. Leveraging classification models like Random Forest and Linear Regression, we evaluate how regular season performance metrics contribute to playoff success and championship outcomes.

## Goals

Predict wjeater a team will become NBA champion using bianary classification

Identify key statiscal patterns and features correlated with championship teams.

Compare Model accuracy, precision and feature importance

convert probabilities into visual formats like pie charts and money lines

## Data Collection:

![Screenshot 2025-04-23 221628](https://github.com/user-attachments/assets/00abe0b6-ee2b-4f62-a114-cf47c2a83064)
![Screenshot 2025-04-23 185054](https://github.com/user-attachments/assets/252baf88-1073-47b2-ae3f-15665ac88241)

## Models Used

Random Forest Classifier
 Best performing classifier so far

 Handles nonlinear feature interactions

 Useful for identifying most important predictive features

 ## Prediction Output

 2025 playoff teams ranked by predicted probability

 Cahrt visualization of championship chances

 Monat Line conversion based on model probabilities

 ## File Overview:

 Project Outline NBA.docx - Initial draft of the project planning and requirement
 
 project.ipynb - MAin notebook containing data processing , model training , evaluation and prediction
 
 project-bj.ipynb - Notebook with added visual graphs and data model comparision and evaluation
 
 /Resources/ - Cleaned historical CSVs with added Season and Champion columns

/Resources/nba_train_2014_2024_with_champion.csv - Training data set

/Resources/nba_playoffs_2025.csv - Test set for champion prediction


## Main Components of the code

# Data Aggregation and Labeling

ALl team stats from 2014 to 2025 are combined into a single dataset

A new column Champion is added, labeled 1 for the actual NBA champion of each season and 0 for all the others

# Feature Engineering

Both offensive and opponent/defensive sats are used 

Features are selected to train machine learning models

# Model Training

A Ranodom Forest classifier is trained on 2014 -2024 data to predict the Champion

The model outputs probabilities of each team being the 2025 champion

# Evaluation

 Accuracy, precision , recall and F1 score are calculated on a validation split

 A confision matrix helps visualize the models performance

 # Prediction Output

 2025 team probabillities are ranked

 A pie chart visualizes the top teams by the title odds

 Moneyline odds are calculated and printed for easy comparision to public betting lines

 ## Data Visualization Overview:
 
![Screenshot 2025-04-23 223052](https://github.com/user-attachments/assets/bb1b7f74-9328-49ea-a6aa-f0d112166104)


![Screenshot 2025-04-23 223126](https://github.com/user-attachments/assets/ad0fba2f-f6bb-4a20-88c2-a674fbcc3f60)


![Screenshot 2025-04-23 223143](https://github.com/user-attachments/assets/4fbc479c-b6c1-4ff0-a6a4-41d1559ee87c)


![Screenshot 2025-04-23 223152](https://github.com/user-attachments/assets/af326f37-0906-4977-870d-3eb8b8ceaefc)


![Screenshot 2025-04-23 223200](https://github.com/user-attachments/assets/81e70b19-16be-4264-8911-8e0cf8687bfd)


![Screenshot 2025-04-23 223209](https://github.com/user-attachments/assets/b6b114e3-1de5-4554-bb46-a2c41d748fb0)
