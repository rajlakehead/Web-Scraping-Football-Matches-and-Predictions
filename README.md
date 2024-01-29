# Football Match Predictor Using Machine Learning

## Overview
This project uses machine learning to predict football match results. The data, spanning two seasons, was scraped from [FBref.com](https://fbref.com/en/).

## Data Collection and Preprocessing
- Scraped data using Pandas, Requests, and BeautifulSoup.
- Investigated and cleaned missing data.
- Prepared the data for machine learning modeling.

## Model
- Employed RandomForestClassifier for prediction.
- Time series data split into training and testing sets.
- Utilized rolling averages to enhance model precision, achieving a 20% improvement.

## Results
The model combines home and away game data, providing a comprehensive prediction system.


---

