# sales-data-analysis
Combine and analyze 12 months of sales CSVs for a business, with data cleaning, aggregation, and visualizations in Jupyter.

---

## Overview

This repository provides a complete workflow to ingest, clean, and analyze 12 months of sales data for an imaginary company. It includes a Jupyter notebook that:
- Loads individual monthly CSV files
- Cleans and standardizes data (e.g., formats dates, handles missing values)
- Aggregates data into a single DataFrame
- Performs exploratory data analysis (EDA) to uncover trends and insights
- Generates visualizations to highlight key sales patterns

---

## Key Features

1. **Imports & Setup:** Load necessary libraries and set plotting options.
2. **Data Ingestion:** Read in each monthly CSV and concatenate into a master DataFrame.
3. **Data Cleaning:** Handle missing values, correct data types, and standardize formats.
4. **Exploratory Data Analysis (EDA):** Calculate summary statistics, identify trends, and detect anomalies.
5. **Visualizations:** Generate charts (e.g., time-series line plots, bar charts) to illustrate key findings.
6. **Conclusions & Next Steps:** Summarize insights and propose potential extensions (e.g., forecasting, automated reporting).

---

## Prerequisites

* Python 3.8 or above
* Required Python libraries:
    ```bash
    pip install pandas matplotlib numpy jupyter seaborn
    ```

---

## How to Run the Analysis

1.  Ensure you have Python and the required libraries installed.
2.  Place the data file (e.g., `sales_2019.csv`) in the same directory as the `main.ipynb` file.
3.  Open and run the `main.ipynb` Jupyter Notebook. The notebook contains the Python code that performs the analysis and generates the visualizations.

---

## Project Structure
```
├── sales-dataset/
│   ├── Sales_April_2019.csv
│   ├── Sales_August_2019.csv
│   ├── ...
│   └── Sales_September_2019.csv
├── sales_2019.csv
├── main.ipynb
├── LICENSE
└── README.md
```

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.