# 🏅 Tokyo Olympic Data Transformation Project

This repository contains a data transformation and analysis pipeline for the **Tokyo Olympics** dataset, utilizing **Apache Spark**, **Azure Databricks**, **Azure Synapse Analytics**, **SQL**, and **Python**. The project processes raw data files about athletes, teams, coaches, and medals from the Tokyo Olympics, cleaning and transforming the data into a structured format for analysis and reporting. This demonstrates efficient big data processing techniques and advanced reporting using cloud platforms.

## 🚀 Project Overview

The **Tokyo Olympic Data Transformation** project takes raw datasets related to the Olympics and transforms them into an organized structure for analysis and reporting. By leveraging **PySpark** on **Azure Databricks** for large-scale data processing and **SQL** for querying the transformed data, we prepare the datasets for advanced reporting in **Azure Synapse Analytics**.

### Key Datasets:
- **Athletes**: Detailed information on participants, including their names, countries, and disciplines.
- **Coaches**: Information on the coaches leading teams in various sports.
- **Teams**: Data about the teams competing in different events.
- **Medals**: Records of medals won, including the country and athlete.
- **Entries by Gender**: Gender distribution data across different disciplines and countries.

### Key Features:
- **Data Loading**: Efficient loading of large datasets using Spark's `read.csv()` function.
- **Data Transformation**: Cleaning and restructuring of datasets, including handling missing values and inconsistencies.
- **SQL Queries for Analysis**: SQL is used to query the transformed datasets to gain insights on athlete participation, country performance, and medal distributions.
- **Data Export**: The final, transformed datasets are exported as CSV files, partitioned for optimized storage and processing.
- **Analysis & Reporting**: **Azure Synapse Analytics** is used to analyze the processed data and generate reports that provide insights into Olympic performances, trends, and gender participation.

## 🌩️ Cloud Platform: Azure

This project makes extensive use of **Azure** services, including **Azure Databricks** and **Azure Synapse Analytics**, for processing, analyzing, and reporting on the Tokyo Olympics data.

### Azure Services Used:
- **Azure Databricks**: Used to execute Spark-based transformations at scale.
- **Azure Synapse Analytics**: Utilized for performing data analysis and reporting on the transformed datasets using SQL.
- **Azure Blob Storage** or **Azure Data Lake**: (If applicable) for storing and retrieving raw data and saving transformed datasets.

## 🛠️ Technologies Used

- **Azure Databricks**: For scalable Apache Spark processing in the cloud.
- **Azure Synapse Analytics**: For data analysis, querying using SQL, and generating reports.
- **Apache Spark**: For large-scale data processing and transformations.
- **SQL**: Used for querying and analyzing the transformed data.
- **Python**: For scripting the transformations and running the pipeline.
- **CSV Format**: Both input and output data are handled as CSV files.

## 📂 Project Structure

```
📦 Tokyo-Olympic-Transformation
 ┣ 📜 README.md                  # Project Documentation
 ┣ 📂 raw-data                   # Directory containing raw CSV datasets
 ┣ 📂 transformed-data           # Directory for output transformed data
 ┣ 📂 notebooks                  # Jupyter notebooks or scripts
 ┗ 📜 Tokyo Olympic Transformation.ipynb  # Main Notebook for data processing
```

### Files:
- **Tokyo Olympic Transformation.ipynb**: The main notebook that handles data loading, transformation, and export.
- **Raw Data**: Input CSV files for athletes, coaches, teams, medals, and entries by gender.
- **Transformed Data**: Output folder containing the cleaned and processed CSV files.

## 🔑 Setup and Installation

To run this notebook and transform the data on **Azure**:

1. **Azure Databricks Setup**: 
   - Create a new Databricks cluster in your Azure environment.
   - Upload the notebook (`Tokyo Olympic Transformation.ipynb`) to Databricks and attach it to the cluster.
2. **Azure Blob Storage Integration**:
   - Store the raw data files in **Azure Blob Storage** or **Data Lake Storage**.
   - Use Spark's `wasbs` protocol to connect to the storage account and access the data.
   ```python
   athletes = spark.read.format("csv").option("header", "true").option("inferSchema", "true").load("wasbs://<container-name>@<storage-account-name>.blob.core.windows.net/athletes.csv")
   ```
3. **Install Required Libraries**: Ensure that `pyspark` is installed locally for testing:
   ```bash
   pip install pyspark
   ```
4. **Run the Notebook**: Execute the notebook in Databricks or Jupyter and follow the steps for data transformation.
5. **Analysis in Azure Synapse Analytics**: Once the transformed data is saved, use **Azure Synapse Analytics** to query the data using SQL and generate reports. Load the transformed CSV files into Synapse to perform the analysis.

## 📊 Outputs

The transformed data is stored in the `transformed-data` folder as CSV files:
- `athletes.csv` – Cleaned and organized athlete data.
- `coaches.csv` – Data about coaches transformed and ready for analysis.
- `teams.csv` – Information on Olympic teams.
- `medals.csv` – A detailed breakdown of medals won by country and athlete.
- `entriesgender.csv` – An aggregation of athlete entries based on gender.

### Analysis & Reporting:
- Perform SQL queries in **Azure Synapse Analytics** to analyze country performance, athlete participation trends, and medal distributions.
- Generate detailed reports on gender participation, country rankings, and Olympic trends using **Synapse Analytics**.

## 📈 Future Enhancements

- **Data Visualization**: Integrate detailed visualizations to display insights about performance, medal distribution, and participation.
- **Machine Learning**: Build prediction models to forecast medal wins based on country performance.
- **API Integration**: Implement APIs to dynamically fetch the latest Olympic data and perform real-time transformations.

## 🤝 Contributions

Contributions are welcome! If you have ideas to improve the project or want to add new features, feel free to fork this repository, make your changes, and submit a pull request.

This version integrates both **SQL** and **Azure Synapse Analytics** for analysis and reporting. Let me know if any other adjustments are needed!

Reference: Darshilparmar
