This GitHub repository contains our submissions for the Predicta 1.0 competition hosted by the University of Peradeniya. The competition involved two distinct tasks: predicting average temperatures for the first week of 2019 across 100 cities worldwide (Time Series Prediction) and classifying weather conditions based on daily observations (Classification).

Project Overview:

Time Series Prediction (Temperature Forecasting):

Dataset: Utilized historical_weather.csv containing weather records.
Methodology: Employed an XGBoost Regressor for time series forecasting after extensive data preprocessing and feature engineering.
Outcome: Predicted average temperatures for January 1-7, 2019, across 100 cities, with results stored in future_data.csv.
Classification (Weather Condition Prediction):

Dataset: Used daily_data.csv with daily weather observations.
Methodology: Implemented a Random Forest Classifier to predict weather conditions based on various features.
Outcome: Achieved high accuracy in weather condition predictions, addressing missing data through robust predictive modeling techniques.

Files Included:

historical_weather.csv: Dataset for temperature forecasting. [https://www.kaggle.com/competitions/predicta-1-0-predict-the-unpredictable/overview]

daily_data.csv: Dataset for weather condition classification. [https://www.kaggle.com/competitions/predicta-1-0-predict-the-unpredictable-part-2/overview]

predict_the_unpredictable.py: Python script for temperature prediction.

classify_the_weather.py: Python script for weather condition classification.

Results and insights from both tasks are detailed in the accompanying report.


Dependencies:

Python 3.x with libraries including pandas, numpy, scikit-learn, and xgboost.


Usage:

Clone the repository, install dependencies, and run the respective Python scripts to reproduce the predictions and classifications.


Future Improvements:

Explore advanced feature engineering techniques and ensemble methods for further enhancing model accuracy and robustness.

This repository demonstrates our approach and methodologies for the Predicta 1.0 competition, showcasing the application of machine learning in weather forecasting and classification tasks. For detailed methodologies and findings, refer to the attached report.

[Predicta_Report_P120.pdf](https://github.com/user-attachments/files/15959111/Predicta_Report_P120.pdf)
