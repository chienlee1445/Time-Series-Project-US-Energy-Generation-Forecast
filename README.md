# Time-Series-Project-US-Energy-Generation-Forecast

## Abstract
This time series forecasting project aims to predict energy generation by all sectors in the United States using monthly data from January 2001 to March 2022. Energy, an indispensable aspect of human life, prompted the need to uncover trends and patterns in U.S. energy production over this period. Various time series techniques were employed, including data transformation, plotting, autocorrelation function (acf), and partial autocorrelation function (pacf) analysis to determine the optimal model for energy generation. Twelve selected data points were utilized for forecasting, testing, and evaluating model accuracy, with the final choice being the $SARIMA(2,1,1)\times(1,1,2)_{12}$ model. The results indicate a steady development trend in energy generation, accompanied by evident seasonality.

## Introduction

This project seeks to forecast energy generation across all sectors in the United States, analyzing monthly data spanning from January 2001 to March 2022. The generation of energy is intricately linked to time, climate, environment, and human factors. Understanding future trends is crucial for the well-being of the country, its inhabitants, and future generations. Energy, being an irreplaceable element in our lives, necessitates the calculation of potential energy, storage, and consumption to prevent overuse. The goal is to assess whether the trend of energy production in the U.S. is influenced by recent extreme weather events and the growing environmental awareness.

The project's outcomes offer insights into the historical behavior of U.S. energy production, shedding light on its future trajectory. Positive results affirm the effectiveness of selected models in predicting the dynamics of energy production across the United States. Methods employed in the project include Box-Cox transformation, variance checking, acf/pacf analysis, differencing, and diagnostic checking.

## Data Source Details

- **Source:** U.S. Energy Information Administration
- **Release:** U.S. Department of Energy
- **Units:** Thousand Megawatt Hours
- **Frequency:** Monthly

The data, spanning from January 1, 2001, to March 1, 2022, is collected by the Energy Information Administration (EIA) and includes information about net electricity generation in the United States. The dataset is sourced from Kaggle and the U.S. Energy Information Administration (EIA) database.

## Packages Used

The following R packages were employed in the project:

- "astsa"
- "MuMIn"
- "tsdl"
- "MASS"
- "ggplot2"
- "ggfortify"
- "qpcR"
- "forecast"
