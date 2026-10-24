# Python & Pandas Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Online Retail dataset using Python, Pandas, Matplotlib, and Seaborn. The goal is to understand retail transaction patterns, identify missing values, analyse numerical and categorical data, and discover meaningful insights through visualisation.

## Dataset
- **Name:** Online Retail Dataset
- **Rows:** 541,909
- **Columns:** 8
- **Source:** [Online Retail Dataset – Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Objectives
- Examine the dataset structure, data types, and memory usage.
- Identify and visualise missing values.
- Calculate descriptive statistics, including mean, median, standard deviation, and quartiles.
- Explore categorical variables and frequently listed products.
- Analyse quantity and unit price distributions.
- Investigate country-wise transactions and monthly transaction trends.
- Examine correlations between numerical variables.
- Summarise key findings from the analysis.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Visualisations
The notebook includes six visualisations:
1. Distribution of transaction quantities
2. Top 10 countries by transaction count
3. Distribution of unit prices
4. Monthly transaction row count
5. Correlation between quantity and unit price
6. Top 10 most frequently listed products

Each visualisation includes a title, labelled axes, and an interpretation.

## Key Observations
- The dataset contains 541,909 transaction rows and 8 columns.
- The `CustomerID` column has 135,080 missing values (approximately 24.93%).
- The `Description` column has 1,454 missing values (approximately 0.27%).
- The remaining columns contain no missing values.
- Additional insights are explored through summary statistics and visualisations in the notebook.

## How to Run
1. Download or clone this repository.
2. Open `eda_analysis.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the dataset CSV file when required.
4. Run all cells from top to bottom.

## Project Outcome
This project demonstrates practical skills in data exploration, data quality assessment, descriptive statistics, and visualisation using Python.
