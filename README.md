# Market-Mix-Modeling-Python
Python code for market mix modelling

Project Overview
This repository contains an end-to-end Python-based Market Mix Modeling (MMM) project. The goal of this analysis is to quantify the impact of different marketing channels, pricing, and other factors on sales. The project demonstrates a full data science pipeline, from data input and validation to model fitting and visualization of key business insights like Return on Investment (ROI) and channel contribution.

Features
Data Validation: Robust functions to check for required columns and correct data types, ensuring the integrity of the analysis.
Adstock Transformation: Implementation of a geometric adstock model to capture the delayed and lingering effects of marketing spend over time.
OLS Regression: Uses statsmodels to fit a multiple linear regression model, providing interpretable coefficients and statistical metrics (R 
2  , p-values).

Contribution Analysis: Computes the total sales contribution of each marketing channel, as well as non-marketing factors like price and seasonality.
ROI Calculation: Calculates the ROI for each media channel, providing a crucial metric for marketing budget allocation.
Data Visualization: Generates four key plots to visualize model performance and business insights:

Actual vs. Predicted Sales
Sales Contribution by Channel
Marketing Channel ROI
Illustrative Adstock Curves

Technologies
Python: The core programming language for the project.
Jupyter Notebook: The interactive environment used for the analysis and visualization.
Pandas: For data manipulation and handling.
NumPy: For numerical operations.
Statsmodels: For the Ordinary Least Squares (OLS) regression model.
Matplotlib: For data visualization and plotting.
scikit-learn: For calculating model evaluation metrics like MSE and R2
tkinter: For the user-friendly file selection dialog.

How to Use
Clone or Download: Clone this repository or download the ZIP file to your local machine.

Install Libraries: Install the required Python libraries. You can use the following command:

Bash

pip install numpy pandas matplotlib statsmodels scikit-learn
Run the Notebook: Open the MMM_Analysis.ipynb (or similar) notebook in Jupyter.

Execute Cells: Run the notebook cells sequentially. When prompted, a file dialog will open, allowing you to select your own CSV data file with the specified format. The notebook will then perform the entire analysis and display the results.
