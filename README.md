# Retail Sales Data Analysis

This project performs an Exploratory Data Analysis (EDA) on a retail sales dataset to uncover insights into customer behavior, popular products, and sales trends.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Highlights](#analysis-highlights)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
This repository contains a Jupyter Notebook (`1.EDA on retails sales data.ipynb`) that conducts a detailed Exploratory Data Analysis (EDA) on retail sales data. The primary goal is to understand various aspects of the sales, identify patterns, and visualize key metrics.

The analysis covers:
* Data Loading and Initial Inspection
* Descriptive Statistics
* Checking for Missing Values
* Data Visualization to identify trends and distributions

---

## Dataset
The dataset used for this analysis is `retail_sales_dataset.csv`. It contains the following columns:
* `Transaction ID`: Unique identifier for each transaction
* `Date`: Date of the transaction
* `Customer ID`: Unique identifier for each customer
* `Gender`: Gender of the customer
* `Age`: Age of the customer
* `Product Category`: Category of the purchased product (e.g., Beauty, Clothing, Electronics)
* `Quantity`: Number of units purchased
* `Price per Unit`: Price of a single unit of the product
* `Total Amount`: Total amount of the transaction

The dataset consists of 1000 entries and 9 columns, with no null values.

---

## Installation
To run this notebook, you will need to have Python installed along with the following libraries:
* pandas
* numpy
* matplotlib
* seaborn

You can install these dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn
