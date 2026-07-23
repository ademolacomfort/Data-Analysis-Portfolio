🌍 Global Air Pollution Analysis using Google BigQuery & Python


📌 Project Overview

This project analyzes a global air quality dataset (2016–2022) queried from Google BigQuery. SQL was used to extract the 

data, while Python was used for data cleaning, exploratory data analysis (EDA), and visualization to uncover pollution 

patterns, regional hotspots, and temporal trends.



🎯 Objectives


- Identify pollutant distribution across different locations
- Detect geographic pollution hotspots
- Analyze seasonal variations in air quality
- Study temporal (time-based) trends in pollution levels
- Investigate potential monitoring-source bias



🛠️ Tools & Technologies


- **SQL (Google BigQuery)**
- **Python** (Pandas, NumPy)
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**



⚙️ Workflow


### 1. Data Extraction
- Queried air quality data using SQL in Google BigQuery.
- Selected relevant pollutant, location, and time variables.

### 2. Data Cleaning
- Handled missing values.
- Standardized data formats.
- Prepared the dataset for analysis.

### 3. Exploratory Data Analysis
- Explored pollutant concentration distributions.
- Identified pollution hotspots.
- Analyzed seasonal and yearly trends.
- Investigated monitoring-source bias.

### 4. Data Visualization
- Created charts to communicate trends and patterns.
- Compared pollution levels across regions and time.




📊 Key Insights


- Pollution levels varied significantly across regions.
- Certain locations consistently recorded higher pollutant concentrations.
- Seasonal patterns were evident in air quality measurements.
- Monitoring sources showed differences that may indicate reporting bias.


---

## 📁 Project Structure

Air Quality Analysis/
│

├── data/
│   ├── global_air_quality_raw_data.csv
│   └── global_air_quality_cleaned_data.csv

│
├── notebooks/
│   └── global_air_quality_data_analysis.ipynb
│

├── visuals/
│   ├── Avg Pollution by Month.jpg
│   ├── Pollutant Counts.jpg
│   ├── Yearly Pollution Trend.jpg
│   └── ...
│
└── README.md


### Visuals
Contains visualizations including:

---

## 📈 Sample Visualizations

### Top 10 Countries by Average Pollution

![Top Countries](visuals/Top%2010%20Countries%20by%20Avg%20Pollution.jpg)

### Yearly Pollution Trend

![Yearly Trend](visuals/Yearly%20Pollution%20Trend.jpg)

### Pollution Value Distribution

![Distribution](visuals/Pollution%20Value%20Distribution.jpg)

---

## Skills Demonstrated

- Data cleaning with Pandas
- Data manipulation and transformation
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Working with datetime data
- Grouping and aggregation
- Statistical summaries

---

## ✅ Conclusion

This project demonstrates an end-to-end data analysis workflow, from SQL data extraction in Google BigQuery to data cleaning, exploratory analysis, and visualization in Python. The insights generated can support environmental monitoring and informed decision-making while showcasing practical data analytics skills.
