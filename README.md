# Exploratory Data Analysis on Vehicle Dataset

## Objectives
The purpose of this project is to perform exploratory data analysis (EDA) to understand vehicle trends and characteristics using a dataset containing 100,000 entries. The analysis is conducted using Python libraries such as Pandas, Matplotlib, and Seaborn.

## Dataset Description
The dataset contains the following columns:
- `brand`
- `model`
- `color`
- `registration_date`
- `year`
- `price_in_euro`
- `power_kw`
- `power_ps`
- `transmission_type`
- `fuel_type`
- `fuel_consumption_l_100km`
- `fuel_consumption_g_km`
- `mileage_in_km`
- `offer_description`

## Analysis Steps

### 1. Data Cleaning and Preparation
- Loaded the dataset and handled missing or incorrect values.
- Converted the `year` column to a numeric format and addressed anomalies (e.g., future years, or very old years).

### 2. Descriptive Statistics
- Provided summary statistics (mean, median, mode, range, variance, standard deviation) for the numeric columns: `price_in_euro`, `power_kw`, `power_ps`, `mileage_in_km`.
- Identified the most and least expensive cars by `brand` and `model`.

### 3. Distribution Analysis
- Created histograms to visualize the distributions of `price_in_euro`, `power_kw`, and `mileage_in_km`.
- Discussed any skewness in the data.

### 4. Categorical Data Analysis
- Counted and visualized the number of vehicles by `brand`.
- Analyzed the distribution of `transmission_type` and `fuel_type` across the dataset.

### 5. Time Series Analysis
- Plotted the number of vehicles registered each year.
- Identified any trends indicating an increase or decrease in registrations.

### 6. Correlation Analysis
- Analyzed the relationship between `price_in_euro` and `power_kw`, `power_ps` using scatter plots and correlation coefficients.
- Explored how `fuel_consumption_l_100km` relates to `power_kw` and `power_ps`.

### 7. Grouped Data Analysis
- Compared the average price of vehicles grouped by `fuel_type`.
- Analyzed average mileage grouped by `brand` and `transmission_type`.

### 8. Text Data Analysis
- Extracted keywords from `offer_description` that frequently appear in the top 5% priced vehicles.
- Identified features commonly advertised in higher-priced vehicles.

### 9. Multivariate Analysis
- Created pair plots for `price_in_euro`, `power_kw`, `mileage_in_km`, and `fuel_consumption_l_100km` to observe patterns.

### 10. Anomaly Detection
- Identified anomalies in `price_in_euro` and `mileage_in_km`.
- Discussed potential reasons for these anomalies and visualized vehicles that significantly deviate from the norm.

## Results
The analysis provided valuable insights into vehicle pricing trends, power distribution, brand popularity, and fuel efficiency. It also highlighted anomalies within the dataset.

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
