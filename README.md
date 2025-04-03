# New York Taxi Driver Analysis

This project is a guided exploratory data analysis (EDA) of New York City Taxi Trip Data, focusing on understanding the distribution of fares, identifying anomalies, and preparing the data for further modeling or insights.

---

## Problem Statement
The objective of this project is to analyze taxi trip data from New York City to explore:
- The distribution of trip fares (`total_amount`)
- Data quality issues (e.g., missing values, negative fares, extreme outliers)
- Relationships between fare amounts and other features like trip distance, passenger count, and pickup/drop-off locations.

---

## Dataset
The dataset used is the **Yellow Taxi Trip Data - January 2025** available in `.parquet` format.

| Column | Description |
|--------|-------------|
| tpep_pickup_datetime | Date and time when the trip started |
| tpep_dropoff_datetime | Date and time when the trip ended |
| passenger_count | Number of passengers in the taxi |
| trip_distance | Distance traveled during the trip (in miles) |
| RatecodeID | Code representing the rate category of the trip |
| PULocationID | Pick-up location ID |
| DOLocationID | Drop-off location ID |
| payment_type | Type of payment used |
| total_amount | Total amount paid (fare + extras) |

---

## Main Tasks Completed
✅ Imported and inspected the dataset  
✅ Performed data cleaning (removed unnecessary columns and outliers)  
✅ Handled missing values  
✅ Explored distributions using histograms and scatter plots  
✅ Visualized negative and extreme fare amounts  
✅ Prepared data for future modeling and analysis

---

## Visualizations
- Histograms of all numerical columns
- Scatter plots of total amount vs index
- Filtered plots to focus on normal fare ranges
- Detection of negative fares and outliers

---

## Tools Used
- Python 3.x
- Pandas
- Matplotlib
- Numpy

---

## Credits
This project is part of the guided project by Misra Turp and the IBM Data Science Professional Certification.
