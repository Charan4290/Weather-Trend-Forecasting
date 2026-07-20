# Weather Trend Forecasting

## Project Overview

This project analyzes the **Global Weather Repository** dataset to identify weather trends and build a basic weather forecasting model. The project includes data cleaning, exploratory data analysis (EDA), time series analysis, and model evaluation.

This project was completed as part of the PM Accelerator Technical Assessment.

## PM Accelerator Mission

PM Accelerator helps aspiring professionals gain practical experience by working on real-world projects, developing technical and product management skills, and building industry-ready portfolios.

## Dataset

**Dataset:** Global Weather Repository

The dataset contains daily weather information collected from cities around the world, including temperature, humidity, wind speed, precipitation, air quality, latitude, longitude, country, weather conditions, and last_updated.

## Project Objectives

- Clean and preprocess the dataset
- Handle missing values and outliers
- Normalize numerical features
- Perform Exploratory Data Analysis (EDA)
- Visualize temperature and precipitation trends
- Build a basic forecasting model
- Evaluate model performance
- Perform time series analysis using the `last_updated` feature

## Data Cleaning

- Removed duplicate records
- Handled missing values
- Converted `last_updated` to datetime format
- Removed outliers using the IQR method
- Normalized numerical features using StandardScaler

## Exploratory Data Analysis (EDA)

- Dataset summary
- Correlation heatmap
- Temperature distribution
- Precipitation distribution
- Average temperature by country
- Temperature trend over time
- Precipitation trend over time

## Forecasting Model

A simple **Linear Regression** model was built using Day, Month, and Year extracted from the `last_updated` column.

### Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly

## Project Structure

```
Weather-Trend-Forecasting/
│
├── Weather_Trend_Forecasting.ipynb
├── GlobalWeatherRepository.csv
├── README.md
├── requirements.txt
```

## How to Run

1. Open the notebook in Google Colab.
2. Upload `GlobalWeatherRepository.csv`.
3. Run all cells in order.
4. Review the results and visualizations.

## Results

The project successfully cleaned the dataset, explored weather trends, built a forecasting model, and evaluated its performance.

## Author

Sai Charan Reddy Buchamma
