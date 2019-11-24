# global-terrorism-analytics
This project aims to analyse past terrorist activities and draw insights from them to predict success of future activities.
The codes have been neatly placed in notebooks to enable step by step execution to the viewers. These can be uploaded to Kaggle and executed without having any path issues. Dataset needs to be added to the Kaggle notebook. Search for 'Global Terrorism Database' in the 'Add Data' section.

This repo contains the following files:
  a. exploratory_analysis.ipynb : EDA performed on dataset for preliminary observations 
  b. Pre_Processing.ipynb : Extractin necessary features from dataset using chi-squared test
  c. cleaned_file.ipynb : Drops rows that have less popular attacking groups
  d. logistic.ipynb : performing logistic regression to model the data (excluding 'country' attribute)
  e. logistic regression with other attributes.ipynb : 'country' attribute included
  f. random_forest : modelling the data using random forest
  g. time_series_analysis.ipynb : testing for stationarity and forecasting success, ARIMA model
  h: reduced_dataset_final.csv : reduced dataset after cleaning
  i. attack_type_analysis.ipynb : Analyses how the different mechanisms of attacks have contributed to  the success
  j. temporary : folder conatins some intermediate code that was later merged to one of the above files

Link to Kaggle dataset : https://kaggle.com/start-umd/gtd
Link to Youtube video : https://www.youtube.com/watch?v=J9nVM-Pr6X0

