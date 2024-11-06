# Project 4: Big Data Analysis with PySpark on Weather Data

**Due Date**: Nov 3, 11:59 PM  
**Total Points**: 10

## Project Objective
This project involves analyzing and extracting insights from the NCEI Global Surface Summary of Day dataset. The data will be processed using PySpark, Jupyter Notebook, and various data engineering and analytics techniques, providing hands-on experience with big data. Key tasks include handling and analyzing weather data from Cincinnati and Florida for years 2015-2024.

## Requirements and Setup

1. **Anaconda and PySpark Installation**  
   - Download and install [Anaconda](https://www.anaconda.com/products/distribution) and [Apache Spark 3.5.3](https://spark.apache.org/downloads).
   - Set up environment variables and install the PySpark library:
     ```bash
     pip install pyspark
     ```
   - Launch Jupyter Notebook from Anaconda.

2. **Dataset Download**
   - Download weather data for Cincinnati (72429793812) and Florida (99495199999) from the NCEI database for 2015-2024.
   - Organize datasets by year and location (e.g., `2015/72429793812.csv` for Cincinnati 2015).

## Analysis Tasks

1. **Setup Verification**
   - Provide screenshots showing Anaconda and PySpark installation and Jupyter Notebook launch.

2. **Data Loading**
   - Load each CSV file and display the record count for verification (20 datasets).

3. **Hottest Day Analysis**
   - Find the hottest day (MAX temperature) for each year, providing station code, name, date, and temperature.

4. **Coldest Day in March**
   - Identify the coldest day in March across all years with station code, name, date, and temperature.

5. **Annual Precipitation Comparison**
   - Determine the year with the most precipitation for Cincinnati and Florida, including station code, name, year, and mean precipitation.

6. **Missing Value Percentage**
   - Calculate the percentage of missing values in the wind gust (GUST) column for Cincinnati and Florida in 2024.

7. **Temperature Statistics (2020)**
   - Compute mean, median, mode, and standard deviation of the temperature (TEMP) for each month in Cincinnati for 2020.

8. **Lowest Wind Chill Days (2017)**
   - Calculate Wind Chill for days in 2017 where temperature (TEMP) was below 50°F and wind speed (WDSP) above 3 mph. Display the top 10 lowest Wind Chill days.

9. **Extreme Weather Analysis for Florida**
   - Analyze the FRSHTT column to count days with extreme weather events (fog, rain, snow, etc.) in Florida.

10. **Temperature Prediction for Cincinnati (Nov-Dec 2024)**
    - Predict maximum temperatures for November and December 2024 based on previous two years' data, including a brief discussion of the model and possible improvements.

## Submission Requirements

Submit two files:
1. **Results File**: `My_Results.txt` (e.g., `My_Results.txt`)
2. **Spark Code**: `My_Spark.ipynb` (e.g., `My_Spark.ipynb`)

## Key Points to Remember
- Remove missing or invalid readings from the dataset as per the README.
- Organize and analyze data by leveraging Spark's capabilities for handling large datasets efficiently.
- Ensure results for all tasks are clear and well-documented in the code and output.

---

## Submission Files

The following files are submitted for the completion of Project 4:

1. **Results File**: A text file containing the results of the data analysis.  
   [Download My_Results.txt](My_Results.txt)  

3. **PySpark Code**: The Jupyter notebook containing the Spark code used for data analysis.  
   [Download My_Spark.ipynb](My_Spark.ipynb)

