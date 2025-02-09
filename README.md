# Premier League Match Outcome Prediction - Machine Learning Project

![Premier League Predictions](https://e0.365dm.com/22/12/1600x900/skysports-premier-league-predictions_6009362.jpg?20221230100523)

This project focuses on predicting the outcome of Premier League football matches using machine learning. The model leverages historical head-to-head data, team rankings, and other relevant features to predict whether a match will result in a **Home Win**, **Away Win**, or **Draw**. The model is deployed as a REST API, allowing users to make predictions by sending a POST request with match details.

---

## Project Overview

The goal of this project is to build a machine learning model that predicts the outcome of Premier League matches based on:
1. **Head-to-Head History**: Historical performance between the two teams.
2. **Season Rankings**: Current league rankings of the home and away teams.
3. **Additional Features**: Other relevant factors that influence match outcomes.

The model is trained on historical Premier League data and deployed as an API for easy integration into applications, websites, or other systems.

---

## API Deployment

The model is deployed as a REST API using **Render**. You can access the API at the following link:

**API Deployment Link**: [https://machninelearning-v2-1.onrender.com/predict](https://machninelearning-v2-1.onrender.com/predict)

---

## How to Use the API

To make a prediction, send a **POST request** to the API with the following JSON payload:

### Example API Request

```json
{
  "home_team": "Man City",
  "away_team": "Arsenal",
  "home_rank": 1,
  "away_rank": 7
}
