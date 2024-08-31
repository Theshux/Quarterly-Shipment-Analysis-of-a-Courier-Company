# Quarterly-Shipment-Analysis-of-a-Courier-Company

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Libraries Used](#libraries-used)
4. [Data Preprocessing](#data-preprocessing)
5. [Analysis and Visualizations](#analysis-and-visualizations)
   - [1. Plotting the Time Series Data](#1-plotting-the-time-series-data)
   - [2. Descriptive Statistics](#2-descriptive-statistics)
   - [3. Time Series with Mean and Median](#3-time-series-with-mean-and-median)
   - [4. Quarterly Comparison Barplot](#4-quarterly-comparison-barplot)
   - [5. Year-on-Year Quarterly Comparison](#5-year-on-year-quarterly-comparison)
   - [6. Distribution Plot](#6-distribution-plot)
   - [7. Time Series Decomposition](#7-time-series-decomposition)
6. [Conclusion](#conclusion)

## Introduction
This project aims to analyze the quarterly shipment data of a courier company from the 20th century. By exploring the trends, seasonal patterns, and distribution of shipments over different quarters and years, we gain insights into the company's shipment dynamics and potential factors influencing them.

## Dataset
The dataset contains quarterly shipment data, including columns for the year, quarter, and shipment volume.

- **Columns:**
  - `Year`: The year of the shipment data.
  - `Quarter`: The quarter of the year (Q1, Q2, Q3, Q4).
  - `Shipments`: The volume of shipments during that quarter.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib**: For creating static plots.
- **Seaborn**: For statistical data visualization.
- **Statsmodels**: For time series decomposition.

## Data Preprocessing
- The dataset was loaded using Pandas.
- The `Quarter` and `Year` columns were combined to create a datetime index for easier time series analysis.
- The dataset was then set to a quarterly time series format, with the `Date` as the index.

## Analysis and Visualizations

### 1. Plotting the Time Series Data
- **Objective**: Visualize the quarterly shipment trends over time.
- **Method**: A line plot was created using Seaborn to show the shipment trends from the start to the end of the dataset.
- ![image](https://github.com/user-attachments/assets/294325f6-022f-4482-a6a2-80728b57c3ae)


### 2. Descriptive Statistics
- **Objective**: Calculate basic descriptive statistics across different quarters.
- **Method**: Descriptive statistics (mean, median, standard deviation, etc.) were calculated for each quarter of different years.
- ![image](https://github.com/user-attachments/assets/d928dda0-1a00-424a-9f23-be1f859e3650)


### 3. Time Series with Mean and Median
- **Objective**: Understand the fluctuation of the data by comparing it to measures of central tendency.
- **Method**: The time series data was plotted alongside the mean and median of shipments for each quarter.
- ![image](https://github.com/user-attachments/assets/415c2c4f-5236-4da1-8299-1ca3900f5faa)


### 4. Quarterly Comparison Barplot
- **Objective**: Compare the average shipment volumes across different quarters.
- **Method**: A barplot was created to show the average shipments for each quarter across the dataset.
- ![image](https://github.com/user-attachments/assets/f78d2bd0-3182-4631-95ea-36067bedde59)


### 5. Year-on-Year Quarterly Comparison
- **Objective**: Compare quarterly shipment volumes year-over-year.
- **Method**: A grouped bar plot was created with each year as a different bar for each quarter.
- ![image](https://github.com/user-attachments/assets/b5f89b29-caee-47bc-a405-590793e1ee07)


### 6. Distribution Plot
- **Objective**: Visualize the distribution of shipments across quarters and years.
- **Method**: A distribution plot was created using Seaborn’s KDE plot, with the hue as the year and the x-axis as the quarter.
- ![image](https://github.com/user-attachments/assets/7062caf0-37fa-4dae-b339-5f40306a38a7)


### 7. Time Series Decomposition
- **Objective**: Decompose the time series into its trend, seasonal, and residual components.
- **Method**: The time series was decomposed using the additive model to separate the trend, seasonality, and irregular components.
- ![image](https://github.com/user-attachments/assets/f4f889dd-c80a-4cdb-adab-6a345ea547b5)


## Conclusion
The analysis provides a comprehensive understanding of the shipment trends, seasonal patterns, and fluctuations over the years. By leveraging various visualization techniques and statistical measures, we gain valuable insights into the dynamics of the company's shipments across different time periods.


