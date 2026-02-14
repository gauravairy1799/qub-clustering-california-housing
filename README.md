# Bike Rental Usage Analysis & Outlier Investigation

## Objective
Analyse bike rental behaviour to identify peak usage patterns, understand user differences, and investigate factors associated with unusually long rental durations.

---

## Dataset
- Bike rental trip records with temporal, user, and station information  
- Additional metadata describing station and rental characteristics  
- Data cleaning performed to remove missing or invalid durations  

---

## Methodology
- Exploratory Data Analysis using **Pandas and Matplotlib**  
- Identification of peak rental hours and usage behaviour  
- Statistical comparison of **rental duration by user type**  
- Detection of unusually long rentals using the **95th percentile rule**  
- Investigation of long-duration trips using **SQL queries**  
- Visualisation of behavioural patterns for interpretation  

---

## Key Insights

### Peak Hourly Usage
![Hourly](assets/01_hourly_usage.png)

### Rental Duration by User Type
![Duration](assets/02_user_type_duration.png)

### Long Rentals by User Type
![Long User](assets/03_long_rental_user_type.png)

### Stations Associated with Long Rentals
![Stations](assets/04_long_rental_station.png)

---

## Tech Stack
Python · Pandas · Matplotlib · SQLite · SQL  

---

## Business Insight
Long-duration rentals are disproportionately associated with **specific user groups and stations**, suggesting opportunities for targeted pricing, operational monitoring, and demand management.

---

## Project Structure
- Notebook: `notebooks/bike_rental_usage_analysis.ipynb`  
- Data: `data/`  
- Visuals: `assets/`  
- Report: `reports/bike_rental_report.html`  

---

## Author
**Gaurav Singh Airy**  
MSc Data Analytics — Queen’s University Belfast
