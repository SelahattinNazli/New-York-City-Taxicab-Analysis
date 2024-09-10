# New-York-City-Taxicab-Analysis

## Problem Definition
The goal of this project is to predict the average fare amount spent on taxi rides for each region of New York City, based on specific time periods such as given days and hours. This is a supervised regression problem, where the task is to estimate a continuous target variable (taxi fare) using historical data that includes actual fare amounts as labels.

The problem can be broken down into the following aspects:

**Supervised Learning:** The dataset contains labeled data, where the target variable (fare amount) is known for each taxi ride. The model learns from these historical data points to make future predictions.

**Regression Task:** Since the value we aim to predict is continuous (taxi fare amounts), this problem falls under regression. The model needs to predict a numerical outcome rather than a categorical class.

By building an accurate predictive model, we can understand the relationships between various factors such as pickup location, dropoff location, day of the week, hour of the day, and how these factors influence the average taxi fare. This insight can be useful for city planning, optimizing taxi fleet management, and providing valuable predictions for potential fare costs in specific regions at particular times.

The challenge is to handle the complexity and variability in the data, such as time-based patterns, spatial variations across different regions, and other contextual factors that may influence taxi fare pricing.

## Project Overview

The main goal of this project is to explore and model New York City taxi trip data. The analysis includes:
- **Data cleaning and preprocessing** to handle missing values and outliers.
- **Exploratory Data Analysis (EDA)** to understand ride patterns across different locations, times, and days of the week.
- **Feature Engineering** to create new variables such as weekend indicators, public holiday markers, and more.
- **Machine Learning Models** for predicting fare amounts and analyzing factors that impact taxi rides.

## Dataset

The dataset used for this project includes New York City yellow taxi trip records. It contains information about:
- **Pickup and Dropoff locations** (latitude/longitude and zone IDs)
- **Trip distances** (in miles)
- **Fare amounts** (total fare for each trip)
- **Passenger count** and other related variables.

Source of the data: [New York City Taxi & Limousine Commission (TLC)](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

## Project Structure

- **data/**: Contains the raw data files in `.csv` or `.parquet` format.
- **notebooks/**: Google Colab notebooks used for data analysis and model development.
- **models/**: Saved machine learning models.
- **src/**: Source code for data preprocessing, model training, and evaluation.
- **README.md**: Project description and details.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/SelahattinNazli/nyc-taxicab-analysis.git
