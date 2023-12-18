# LondonTemperature-XGBoost-Predictor

## Project Overview
This project harnesses the predictive power of the XGBoost machine learning algorithm to forecast London's daily temperature trends using historical weather data sourced from [Kaggle](https://www.kaggle.com/datasets/emmanuelfwerr/london-weather-data). It showcases the evolution of the forecasting model through two versions, each on a separate branch within this repository.

## Features
- Time series forecasting with XGBoost
- Data cleaning and preprocessing with pandas
- Visualization of missing data with seaborn
- Performance evaluation of the predictive model

## Challenges Overcome
I tackled missing values effectively by visualizing them with a heatmap and opted to drop rows with NaN values, which were minimal and did not affect the dataset significantly.

## Results
The model successfully captures the yearly temperature trend, yet there is room for improvement, particularly in utilizing additional weather parameters to enhance accuracy.

## Installation
Clone the repository, download the dataset and model file, and execute the Jupyter Notebook to reproduce the forecast.

## Branches
- `version-1`: Initial model using train-test split.
- `version-2`: Refined approach employing time series cross-validation for enhanced sophistication.

## Future Directions
Plans to refine the model include leveraging additional dataset features like cloud cover and pressure, aiming for more detailed and accurate predictions.

## Collaboration and Contact
This is an individual project, inspired by Rob Mulla's tutorial on YouTube for a similar project. Feel free to reach out for discussions and collaborations.

LinkedIn: [Tobi Fakoya](http://www.linkedin.com/in/tobi-fakoya)
