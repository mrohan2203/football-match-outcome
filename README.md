# Football match outcome predictor using Random Forest

Given the attacking statistics of a team, we predict the outcome of a football match using Random Forest and XGBoost.

1. We perform web scraping on fbref.com and gather statistics of matches played in the Premier League between 2022 and now.
2. We try to clean the data and remove irrelevant features from the dataset.
3. We perform Label Encoding on categorical columns, namely 'Venue,' 'Opponent,' and 'Day.' We also extract the 'hour' column from the time.
4. We develop Random Forest and XGBoost using train and test samples. The train sample is the matches before 2024, and the test sample is the matches played in 2024.
5. We compare and contrast the accuracy scores for both models and pick the better one.
6. We perform Rolling averages to smoothen our data and improve accuracy.
7. We re-run the model to check the accuracy and make predictions.
