# Retail Sales Data Analysis

This project performs an Exploratory Data Analysis (EDA) on a retail sales dataset to uncover insights into customer behavior, popular products, and sales trends.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

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

To run this project locally, you'll need Python and several libraries.

1.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

2.  **Install the required libraries:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn scipy
    ```

---

## Usage

To execute the customer segmentation analysis:

1.  **Ensure you have the dataset:** Place the `retail_sales_dataset.csv` file in the root directory of the project.
2.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "1.EDA on retails sales data.ipynb"
    ```
    This will open the Jupyter interface in your browser. You can then run all cells in the notebook to reproduce the analysis.

---

## File Structure

├── retail_sales_dataset.csv
└── 1.EDA on retails sales data.ipynb
└── README.md

-   `retail_sales_dataset.csv`: The raw dataset used for the retail sales analysis.
-   `1.EDA on retails sales data.ipynb`: A Jupyter Notebook containing the exploratory data analysis (EDA) of the retail sales data.
-   `README.md`: This file, providing an overview and instructions for the project.

---

## Results and Insights

The `1.EDA on retails sales data.ipynb` notebook provides detailed insights into the retail sales data. This includes:
-   Visualizations of sales trends over time.
-   Analysis of sales by product, region, or customer.
-   Key metrics and statistics on the sales dataset.
-   Recommendations based on the data analysis for business strategies.

---

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For any questions or inquiries, please contact [Manchikanti Gayathri/gayathri.manchikanti14@gmail.com].

