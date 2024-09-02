# Airbnb Price Prediction Project

This project analyzes Airbnb listing data to predict the price of listings based on various features such as location, room type, and availability. The project employs both Linear Regression and Random Forest models to perform the predictions and includes visualizations to better understand the relationships between the features.

## Project Overview

The goal of this project is to predict the price of Airbnb listings using a dataset that includes various attributes like neighborhood, room type, and availability. The project includes data preprocessing, feature engineering, exploratory data analysis, model training, and evaluation. A final model is saved as a pickle file for future use.

## Dataset

The dataset used in this project is an Airbnb dataset that contains features such as:

- `neighbourhood_group`
- `neighbourhood`
- `latitude`
- `longitude`
- `room_type`
- `price`
- `minimum_nights`
- `number_of_reviews`
- `reviews_per_month`
- `availability_365`


## Data Preprocessing

The following preprocessing steps were applied:

- Dropped unnecessary columns like `id`, `name`, `host_name`, `last_review`, etc.
- Handled missing values in the `reviews_per_month` column by filling them with 0.
- Removed listings with a price of 0.
- Dropped columns like `latitude`, `longitude`, `number_of_reviews`, etc., after initial analysis.




