# Arihant-5010.Air-Pollution-Analysis using R
This project presents an in-depth analysis of air pollution data from various Indian cities between 2015 and 2020. It includes data cleaning, visualization, and machine learning modeling to study patterns, outliers, and predictors of the Air Quality Index (AQI).

** Dataset**
The dataset (city_day.csv) contains daily air quality readings from over 25 Indian cities. Key pollutants tracked include PM2.5, PM10, NO2, SO2, CO, O3, and others.

 **Tools & Technologies Used**
Language: R

**Libraries:**

dplyr, lubridate, naniar – data manipulation and wrangling , ggplot2, corrplot, reshape2 – data visualization , caret, randomForest, rpart – machine learning

**Environment: RStudio**

**Key Features & Workflow**

**1. Data Cleaning & Preprocessing**

Handled missing values using mean imputation.

Renamed columns for better readability.

Converted character and factor variables appropriately.

Removed outliers using the IQR method.

**2. Exploratory Data Analysis (EDA)**

Boxplots and histograms for pollutant distributions.

Time-series plots of PM2.5 and AQI by city and year.

Heatmaps and correlation matrices to identify pollutant interrelationships.

AQI category counts and city-level comparisons.

**3. Comparative Analysis**

City-wise AQI trends.

Yearly comparisons of AQI levels.

Identification of the most polluted cities each year.

**4. Machine Learning**

Random Forest models to predict AQI.

**Achieved:**

**Random Forest MSE: 422.38**

**Random Forest R²: 0.83**

 **Visualizations**
 
Time-series plots of pollutant levels

Bar charts of average AQI per city

Correlation heatmaps between pollutants

City comparisons across different years
