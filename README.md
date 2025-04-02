# Rain in Australia - Next-Day Rainfall Prediction

## Overview

This project predicts whether it will rain tomorrow in Albury, Australia, based on historical weather data. Using machine learning, specifically K-nearest neighbors (KNN) classification, we classify whether it will rain the next day based on features like temperature, wind speed, and humidity.

## Approach

- **Data Preprocessing**: We cleaned the dataset by removing irrelevant and missing data and selected significant predictor variables.
- **Model**: A K-nearest neighbors (KNN) classification model was built, and the best value of K was selected using cross-validation.
- **Evaluation**: The model's performance was evaluated on a test set, with visualizations to explore relationships between key features.

## Key Features

- **MinTemp**: Minimum temperature (°C)
- **MaxTemp**: Maximum temperature (°C)
- **Rainfall**: Amount of rainfall (mm)
- **WindGustSpeed**: Strongest wind gust speed (km/h)
- **Humidity9am**: Humidity at 9am (%)
- **Pressure9am**: Atmospheric pressure at 9am (hPa)

## Expected Outcomes

- A model to predict next-day rainfall (Yes/No).
- Insights into the influence of weather parameters on rainfall prediction.

## Significance

Rainfall prediction helps in daily decision-making (e.g., travel plans, agriculture). This project demonstrates the use of machine learning to forecast weather conditions.

## Future Work

- Extend to other variables or regions.
- Try regression to predict rainfall amounts.
- Compare KNN with other machine learning models.

## Libraries Used

- `tidyverse`: Data manipulation and visualization
- `tidymodels`: Model building
- `leaps`: Feature selection

## Data Sources

- [Bureau of Meteorology - Climate Data Online](http://www.bom.gov.au/climate/data/)
- Barrera-Animas et al., 2021, [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S266682702100102X)

