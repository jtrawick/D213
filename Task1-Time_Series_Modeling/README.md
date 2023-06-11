# D213 - Advanced Data Analytics: Task 1 - Time Series Modeling

This repository contains the work for Task 1 of the D213 Advanced Data Analytics project. The goal of this task is to use time series analysis to model and forecast hospital revenue data.

## Repository Contents

- `D213_task1.docx`: This file contains the written report for the task.
- `D213_task1.html`: This file contains the HTML output of the analysis.
- `D213_task1.ipynb`: This file contains the Jupyter notebook with the Python code used for the analysis.

## Project Overview

The project involves the use of an ARIMA (AutoRegressive Integrated Moving Average) model to forecast future revenues based on the first two years of daily revenue data. The data was prepared by transforming the time series to achieve stationarity and then split into training and testing subsets. The optimal ARIMA parameters were determined to be (1, 0, 0) and the model was evaluated using the Root Mean Squared Error (RMSE) metric.

## Recommendations

The ARIMA model provides a compelling answer to the research question posed: using the first two years of daily revenue data, we indeed created a reliable model for forecasting future revenues. Therefore, one proposed course of action based on these results is to integrate this model into the organization's operational procedures for revenue prediction and planning. However, it is important to ensure the model continues to provide accurate predictions as the business environment and conditions change over time. Hence, it is recommended to implement a procedure for regular model updates and validations.