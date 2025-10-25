## 📊 Project Title: Data Warehouse - Data Mining and Data Analysis

**Author:** Răzvan-Alexandru Macovei
**Domain:** Data Mining 

### I. 🎯 Project Objective

The goal of this project is to apply Data Mining methodologies to transform raw data from Kaggle Database.

* To extract, clean, and load the data using a robust **ETL process**.
* To identify hidden patterns and correlations within the dataset.

### II. 🛠️ Technical Specifications and Toolset

This project was developed using the following technologies and concepts:

| Category | Details | Data Mining Focus |
| :--- | :--- | :--- |
| **Data Sources** | Raw CSV files sourced from **Kaggle**.
| **ETL Process** |  Complex SQL queries. | Ensuring data quality and structuring it for analysis. |
| **Data Quality** | Checking and handling of missing values, outliers, and formatting errors. | Adjusting the data for standardization |
| **Dimensional Model** | I used Data Warehouse concepts: Fact/Dimension Tables. | Structuring data for fast querying (BI/Analytic Queries). |
| **Software** | SQL Server | The specific tool utilized. |

### III. 🔄 Detailed ETL Process (Data Pipeline)

The project followed a structured ETL (Extract, Transform, Load) approach to prepare the data:

1.  **Extract:** Data was pulled from the **Kaggle source** and loaded into a staging area.
2.  **Transform (Cleaning & Preparation):** This stage included:
* **Cleaning:** Removing/imputing missing values and treating outliers.
3.  **Load:** The transformed data was loaded into a ready-for-analysis database for future BI queries.
