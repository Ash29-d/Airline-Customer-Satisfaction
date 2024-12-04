# Airline-Customer-Satisfaction


## Overview

This project focuses on analyzing and predicting airline customer satisfaction levels using a decision tree model. The dataset contains various features related to customer demographics, travel details, and service satisfaction ratings. The goal is to predict whether a customer is "Satisfied," "Neutral," or "Dissatisfied" with their airline experience based on these factors.


## Features

 * Dataset Attributes:
   
    * Customer Details: Gender, age, and loyalty status.
    * Travel Details: Travel type (Business or Personal), class of travel (Business, Economy, Economy Plus), and flight distance.
    * Service Ratings: Scores for inflight Wi-Fi, online booking ease, seat comfort, inflight entertainment, cleanliness, and more.
    * Delay Information: Departure and arrival delays in minutes.

  * Variable Descriptions:

    * Customer Type: Distinguishes loyal customers from disloyal customers.
    * Type of Travel: Indicates the travel purpose (e.g., Business, Personal).
    * Satisfaction: The target variable (Satisfaction, Neutral, Dissatisfaction).

## How It Works

  * Data Loading: The dataset is imported and processed using Python libraries (pandas, numpy, etc.).
  * Exploratory Data Analysis (EDA): Key visualizations and summary statistics are used to explore patterns in the data.
  * Data Preprocessing:
      * Missing values are handled appropriately.
      * Categorical variables are encoded for machine learning compatibility.
      * Feature scaling may be applied to numeric features.
  * Model Building:
      * A decision tree classifier is trained on the processed dataset.
      * Hyperparameters might be tuned to optimize performance.
  * Evaluation:
      * The model’s accuracy, precision, recall, and F1-score are calculated.
      * A confusion matrix or feature importance visualization helps interpret results.
  * Prediction:
      * The model predicts satisfaction levels for unseen data.
   
## Requirements

  * Libraries: numpy, pandas, matplotlib, scikit-learn.
