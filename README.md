# weather-etl-pipeline
ETL pipeline: Kaggle CSV → Parquet → BigQuery
# 🌤️ Weather Data ETL Pipeline

A complete, end-to-end ETL (Extract, Transform, Load) pipeline that moves weather data from a raw CSV file into Google BigQuery, using Parquet as an efficient intermediate storage format.

## 📋 Project Overview

This project takes an open-source weather dataset from Kaggle, cleans and transforms it, converts it to the efficient Parquet columnar format, and loads it into Google Cloud's BigQuery data warehouse.

## 🛠️ Tech Stack

- **Python** — core programming language
- **Pandas** — data transformation and cleaning
- **Parquet** — columnar, high-performance file format
- **Google BigQuery** — cloud-based data warehouse
- **Google Colab** — development environment

## 🔄 Pipeline Steps

1. **Extract** — Downloaded the raw CSV dataset from Kaggle via the Kaggle API
2. **Transform** — Cleaned and engineered the data with Pandas:
   - Handled missing/null values
   - Removed duplicate rows
   - Standardized column names
   - Fixed data types (e.g., date formatting)
3. **Convert** — Converted the cleaned data into Parquet format
4. **Load** — Loaded the Parquet file into Google BigQuery

## 📊 Outcome

The cleaned weather data is now stored in BigQuery, queryable via SQL, giving team members centralized, scalable access to the dataset.

## 📁 Project Structure

```
weather-etl-pipeline/
├── README.md
├── notebook.ipynb       # Main ETL code (Google Colab)
├── requirements.txt      # Required Python libraries
└── .gitignore            # Excludes sensitive files (JSON key, etc.)
```

## 📈 Skills Demonstrated

- Extracting data from CSV with Python
- Cleaning and transforming data with Pandas
- Working with columnar file formats (Parquet)
- Loading data into BigQuery with Python and SQL
- Understanding cloud data warehouse concepts


---

*This project was built to practice core data engineering fundamentals — ETL, cloud data warehousing, and modern data formats.*
