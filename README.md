# Customer Behavior Analysis Using Transaction Data

## Overview

This project focuses on understanding and analyzing customer behavior based on transactional data. The goal is to perform Exploratory Data Analysis (EDA) to derive valuable insights into customer preferences, purchasing patterns, and overall behavior.

## Dataset

The dataset contains the following columns:
- `MONTH`: The month of the transaction in the format M1, M2, etc.
- `STORECODE`: The code identifying the store where the transaction took place.
- `DAY`: The day of the transaction.
- `BILL_ID`: The unique identifier for the bill or transaction.
- `BILL_AMT`: The total amount of the bill.
- `QTY`: The quantity of items purchased.
- `VALUE`: The value of the transaction.
- `PRICE`: The price of individual items.
- `GRP`: Group category of the item.
- `SGRP`: Subgroup category of the item.
- `SSGRP`: Sub-subgroup category of the item.
- `CMP`: Company code or identifier.
- `MBRD`: Membership or reward details.
- `BRD`: Brand of the item.

## EDA Steps

### 1. Load the Data

Load the dataset from the CSV file.

### 2. Data Cleaning

- Convert `MONTH` column from M1, M2, etc., to numerical values.
- Check and handle missing values.
- Remove duplicate rows.
- Ensure correct data types for each column.

### 3. Univariate Analysis

Analyze individual variables to understand their distribution.

### 4. Bivariate Analysis

Explore relationships between two variables.

### 5. Customer Segmentation

Apply clustering techniques to segment customers based on their purchasing behavior.

### 6. Pattern Recognition

Identify frequent itemsets and associations using market basket analysis.

## Installation and Usage

### Prerequisites

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Mlxtend

### Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the EDA script:
    ```bash
    python eda_script.py
    ```

## Files

- `eda_script.py`: Script containing the EDA steps.
- `data/`: Directory containing the dataset file.
- `README.md`: This file.

## Results

The results of the EDA, including visualizations and insights, are saved in the `results/` directory.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

Thank you to everyone who contributed to the libraries and tools used in this project.
