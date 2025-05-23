# Weather Data Generation and SQL Insertion

This repository contains Python scripts and Jupyter Notebooks for:
1.  **Generating Simulated Weather Data**: Creates synthetic weather data and saves it to Excel and SQLite.
2.  **Generating SQL Insert Statements**: Reads data from a CSV and creates SQL `INSERT` statements.

## Getting Started

### Prerequisites
* Python 3.x
* Jupyter Notebook
* `pip install pandas numpy` (for weather generation)
* `pip install ` (No specific extra libraries beyond standard ones for the SQL script, but pandas covers some if you use it in the SQL script. Otherwise, `csv` is built-in.)

### Usage

1.  **To generate weather data**:
    * Open `WEATHER_DATA_GENERATE.ipynb`.
    * Run all cells. This will create `weather_data.xlsx` and `weather_data.db`.

2.  **To generate SQL inserts from CSV**:
    * Ensure you have a CSV file (e.g., `simulated_weather_data.csv`).
    * Open `weather_sql.ipynb`.
    * Adjust `csv_file_path`, `database_name`, and `table_name` variables if needed.
    * Run all cells. This will create `weatherdata_insert.sql`.

## Files

* `WEATHER_DATA_GENERATE.ipynb`: Generates simulated weather data.
* `weather_sql.ipynb`: Converts CSV data into SQL `INSERT` statements.
* `.gitignore`: Specifies files to ignore (like generated data).
