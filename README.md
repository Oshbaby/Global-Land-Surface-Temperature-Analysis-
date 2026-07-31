# 🌍 Global Climate Analytics & Forecasting Pipeline

## Project Overview

This project explores more than 50 years of global land surface temperature and CO₂ emissions data to understand how climate patterns have changed over time. The objective was to build an end-to-end analytics workflow using Python, covering data cleaning, exploratory analysis, statistical modelling, and long-term forecasting.

Rather than focusing solely on visualisations, this project investigates historical climate trends, examines the relationship between CO₂ emissions and land surface temperatures, and develops predictive models to forecast future temperature patterns. It reflects the type of analytical workflow commonly used in real-world data analytics projects.

---

## Business Problem

Environmental datasets are often large, incomplete, and collected over long periods, making them difficult to analyse. Before meaningful insights can be generated, the data must be cleaned, transformed, and validated.

This project addresses challenges such as:

- Cleaning large historical datasets
- Handling missing observations
- Detecting long-term trends and seasonality
- Measuring relationships between variables
- Developing forecasting models
- Evaluating model performance

---

## Business Questions

The analysis answers several key questions:

- How have global land surface temperatures changed over the last 50 years?
- Which countries have experienced the fastest warming trends?
- How do temperature trends differ between industrialised and developing countries?
- Is there a measurable relationship between CO₂ emissions and land surface temperatures?
- Which forecasting model performs better for long-term climate prediction?
- What temperature trends are projected over the next 30 years?

---

## Technical Skills Demonstrated

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- pmdarima
- Scikit-learn

### Data Analytics Skills

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Correlation Analysis
- Linear Regression
- Time Series Analysis
- Forecasting
- Model Evaluation
- Data Visualisation

---

## Project Workflow

The project followed a structured analytics workflow from raw data through to predictive modelling.

1. Imported multiple publicly available climate datasets.
2. Cleaned inconsistent and incomplete records.
3. Standardised date formats and converted date fields into datetime objects.
4. Filtered historical observations between 1963 and 2013.
5. Treated missing values using interpolation techniques.
6. Identified potential outliers using Z-score analysis.
7. Engineered analysis-ready datasets.
8. Performed exploratory data analysis.
9. Built regression models.
10. Conducted stationarity testing.
11. Developed ARIMA and SARIMA forecasting models.
12. Evaluated forecasting performance using standard error metrics.
13. Generated long-term temperature forecasts.

---

## Analysis Performed

### Data Preparation

- Cleaned and transformed multiple datasets.
- Standardised date formats.
- Removed redundant columns.
- Filtered more than 50 years of historical observations.
- Treated missing values.
- Preserved genuine outliers where appropriate.

### Exploratory Data Analysis

- Trend analysis
- Distribution analysis
- Country comparisons
- Time series visualisations
- Temperature distribution
- CO₂ emissions distribution
- Industrialised versus developing country comparisons

### Statistical Analysis

- Linear Regression
- Correlation Analysis
- R² Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Time Series Analysis

- Augmented Dickey-Fuller (ADF) Test
- Stationarity Analysis
- Differencing
- Autocorrelation (ACF)
- Partial Autocorrelation (PACF)

### Forecasting

- ARIMA
- SARIMA
- 30-year forecasting
- Model comparison
- Forecast evaluation

---

## Key Outcomes

This project successfully:

- Built a complete end-to-end analytics pipeline from raw climate data to predictive forecasting.
- Analysed historical climate patterns across multiple countries.
- Quantified the relationship between CO₂ emissions and land surface temperatures.
- Developed predictive forecasting models for long-term climate trends.
- Compared forecasting models using industry-standard evaluation metrics.
- Produced clear visualisations to communicate analytical findings.

---

## What This Project Demonstrates

This repository demonstrates practical experience in:

- ✔ Data Cleaning
- ✔ Data Wrangling
- ✔ Feature Engineering
- ✔ Exploratory Data Analysis
- ✔ Statistical Modelling
- ✔ Regression Analysis
- ✔ Time Series Analysis
- ✔ Forecasting
- ✔ Model Evaluation
- ✔ Python Programming
- ✔ Data Storytelling
- ✔ Business Communication

---

## Repository Structure

```text
Global-Climate-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── Exploring Trends in Global Land Surface Temperature 1111 to include table change.ipynb
│
├── visualisations/
│
├── forecasts/
│
└── README.md
```

---

## Future Improvements

Potential enhancements include:

- Building an automated ETL pipeline for continuous data ingestion.
- Integrating cloud-based data storage and processing.
- Expanding forecasting using Prophet and LSTM models.
- Developing an interactive dashboard with Streamlit or Power BI.
- Deploying the forecasting workflow as a REST API.

---

## Why This Project Matters

This project demonstrates the ability to work through the complete analytics lifecycle, from collecting and preparing raw data to building statistical models and forecasting future outcomes. It showcases practical experience in data analysis, statistical modelling, and communicating insights through visualisation, making it representative of the type of work expected in data analytics and business intelligence roles.
