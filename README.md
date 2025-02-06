# NYC Taxi Demand Prediction 🚖

## Overview

This project analyzes **New York City taxi trip data** to extract meaningful insights related to ride duration, fare distribution, and trip patterns. The analysis leverages data visualization, feature engineering, and machine learning techniques to uncover trends and optimize taxi operations.

## Business Problem

Understanding NYC taxi trips can help:
- Identify peak hours for demand optimization.
- Analyze fare structures for better pricing strategies.
- Improve route recommendations and reduce trip duration.
- Provide insights into seasonal variations in taxi demand.

## Features

- **Data Preprocessing**: Cleaning and filtering raw trip data.
- **Exploratory Data Analysis (EDA)**: Visualizing trip duration, fare distribution, and geographical patterns.
- **Feature Engineering**: Creating additional features such as trip distance, pickup/drop-off locations, and time-based attributes.
- **Machine Learning Models**: Implementing predictive models for estimating trip fares and durations.
- **Geospatial Visualization**: Mapping taxi routes and hotspots across NYC.

## Dataset Requirements:

The dataset should include:
pickup_datetime: Timestamp of when the trip started.
dropoff_datetime: Timestamp of when the trip ended.
passenger_count: Number of passengers.
trip_distance: Distance traveled.
fare_amount: Fare charged for the trip.
pickup_longitude, pickup_latitude: GPS coordinates of the pickup location.
dropoff_longitude, dropoff_latitude: GPS coordinates of the drop-off location.
Visualizing Data:

Run individual cells to generate:
Histograms of trip durations and fares.
Heatmaps of pickup/drop-off locations.
Time-series analysis of trip frequency.

## Model Details
The notebook explores different machine learning approaches to predict taxi fare amount based on trip details. Models include:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Machines (GBM)
Each model is evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to determine predictive accuracy.

## Results
- Trip duration trends: Identified rush hours and traffic patterns.
- Fare analysis: Studied price variations based on distance and time of day.
- Geospatial mapping: Visualized popular pickup and drop-off locations in NYC.

## Future Enhancements
- ✅ Deep Learning Models: Experiment with neural networks for improved fare prediction.
- ✅ Real-time Analysis: Implement live tracking for fare estimation.
- ✅ Integration with Ride-Sharing Apps: Provide dynamic fare estimates based on traffic conditions.

## Acknowledgements
- **[NYC Taxi and Limousine Commission (TLC)](https://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml)** for providing the dataset.
- **[pandas](https://pandas.pydata.org/)**, **[NumPy](https://numpy.org/)**, **[Matplotlib](https://matplotlib.org/)**, **[Seaborn](https://seaborn.pydata.org/)**, and **[Scikit-Learn](https://scikit-learn.org/)** for powerful data analysis tools.
