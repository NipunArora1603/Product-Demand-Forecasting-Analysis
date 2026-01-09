# Product-Demand-Forecasting-Analysis

Product Demand Forecasting Analysis
This repository contains a data science project focused on forecasting product demand using time-series analysis and deep learning models. The project utilizes the Darts library to implement and compare various forecasting techniques, including traditional statistical methods and machine learning algorithms.

Key Features
Time-Series Modeling: Implements multiple forecasting models such as Exponential Smoothing, AutoARIMA, and FFT (Fast Fourier Transform) to predict future product sales.

Data Processing: Includes workflows for data cleaning, transforming standard CSV data into time-series objects, and splitting datasets into training and validation sets.

Library Integration: Leverages the Darts library for an easy-to-use interface to state-of-the-art forecasting models.

Visualization: Provides detailed plots comparing actual sales data against forecasted trends to evaluate model accuracy.

Technical Stack
Language: Python

Key Libraries:

Darts: For time-series forecasting.

Pandas: For data manipulation and processing.

Matplotlib: For generating performance and trend visualizations.

NumPy: For numerical computations.

Project Workflow
Environment Setup: Installation of the Darts library and its dependencies.

Data Ingestion: Loading SKU-level sales data from CSV files.

Preprocessing: Converting date columns and formatting data into TimeSeries objects compatible with Darts.

Forecasting:

Applying Exponential Smoothing for trend and seasonality capturing.

Using AutoARIMA for automated parameter selection in autoregressive models.

Utilizing FFT to find periodicities in the data.

Evaluation: Visual comparison of forecasts against actual validation data.
