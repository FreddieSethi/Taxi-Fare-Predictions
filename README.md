# Taxi-Fare-Predictions

This project focuses on developing a predictive model using the CRISP-DM methodology to estimate the fare of taxi journeys based on a set of attributes. The main objective is to build a Jupyter notebook that outlines the data exploration, preprocessing, modeling, and evaluation steps. The project also involves participating in a Kaggle competition, where the developed model will be assessed against other submissions. The ultimate goal is to create an accurate and reliable predictive model for estimating taxi fares.

## Task

As a Data Scientist employed by a local taxi company, you have been provided with a training dataset that contains information about past taxi journeys in the Bournemouth area. Each data instance in the training set is labeled with the fare in GBP charged for the journey. The goal of this project is to develop a model that can accurately estimate the fare of new taxi journeys based on the same attributes.

## Data

The training dataset consists of 10,000 instances, each representing a past taxi journey. The dataset is provided in a tabular format (.csv file) with each row corresponding to a journey and each column representing an attribute. The input attributes include:

- start_time: Date and time of the start of the journey.
- start_lat, start_lon: Latitude and longitude of the start of the journey.
- orig_addr: Address of the start of the journey.
- end_time: Date and time of the end of the journey.
- end_lat, end_lon: Latitude and longitude of the end of the journey.
- dest_addr: Address of the end of the journey.
- passengers: Number of passengers.
- booster_seat: Whether a booster seat was requested or not.
- large_luggage: Whether the passenger(s) carried a large piece of luggage or not.
- The target attribute that needs to be predicted is called fare.

## Intended Learning Outcomes (ILOs)

- Data Exploration and Preprocessing:
  - Gain experience in exploring and understanding the given dataset.
  - Handle missing values.
  - Perform necessary preprocessing steps such as data cleaning, feature engineering, and feature selection.
- Predictive Modeling:
  - Apply various machine learning algorithms and techniques for regression.
  - Develop a predictive model for estimating the taxi fare.
  - Involve model selection, parameter tuning, and evaluation using appropriate metrics.
- Feature Importance and Interpretability:
  - Analyze the importance of different features in the predictive model.
  - Understand their impact on the fare estimation.
  - Identify the key factors that influence the fare and provide interpretability to the model.
- Model Evaluation and Optimization:
  - Evaluate the performance of the developed model using appropriate evaluation metrics.
  - Compare the results with other submissions in the Kaggle competition.
  - Use the insights gained from the evaluation to further optimize the model and improve its accuracy.
- Communication and Documentation:
  - Present the findings, methodology, and results of the project in a clear and concise manner using a Jupyter notebook.
  - Effectively communicate the steps taken, the rationale behind decisions made, and the overall approach followed during the project.
