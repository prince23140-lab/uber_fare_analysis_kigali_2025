# 🚖 Uber Fare Dataset Analysis using Python & Power BI

 ## 👥 student Information 

| 👤 Name           | 🆔 Student ID | 🧑‍💻 Role          |
|------------------|---------------|-------------------|
| 🧑‍🔧 Nziza Prince | 26651      | 💻 Data Analyst    |
---


This project analyzes the Uber Fares Dataset to uncover key insights about fare patterns, trip volume, and time-based trends using Python and Power BI.

## 🎯 Objective

The aim of this project was to analyze the **Uber Fares Dataset** to derive insights related to:
- Fare distribution patterns  
- Ride distances  
- Temporal ride behavior (hourly, daily, monthly trends)  
- Identifying busiest periods  
- Creating an interactive Power BI dashboard  
- Recommending data-driven insights to improve Uber operations


## 🧰 Tools Used

- 🐍 Python (Jupyter Notebook) – Data cleaning, EDA, and feature engineering  
- 📊 Power BI – Data modeling, visualization, and dashboarding  
- 📁 CSV – Intermediate cleaned data file format  
- 🌐 GitHub – Documentation, version control, and project submission


## 📥 Dataset

- **Source**: [Uber Fares Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- **File Used**: `uber.csv`  
- The dataset contains:
  - `fare_amount`, `pickup_datetime`, `pickup_latitude`, `pickup_longitude`, `dropoff_latitude`, `dropoff_longitude`, `passenger_count`


## 🧼 1. Data Understanding & Preparation

### ✅ Steps Taken:
- Loaded dataset into Pandas using Python  
- Assessed structure (200,000 records × 9 columns)  
- Checked and handled missing values (2 missing drop-off coordinates)  
- Cleaned data types and removed/filtered invalid entries  
- Exported cleaned dataset as `cleaned_uber_fares.csv` for Power BI


## 📊 2. Exploratory Data Analysis (EDA)

### 📌 Summary Statistics:
- Computed mean, median, mode, standard deviation, range, and quartiles  
- Identified outliers using visualizations (box plots and scatter plots)

### 📊 Key Visualizations

## Fare Distribution Analysis
![fare amount distribution](https://github.com/user-attachments/assets/76cc3050-3fc6-4202-a3b7-7fba221e8149)

*Most fares cluster between $5-$25 with long-tail distribution*

Distance vs. Fare Relationship
![fare amount vs distance](https://github.com/user-attachments/assets/3e336277-330c-4cb5-9283-cbc8f9c6e13a)

Strong positive correlation with notable outliers beyond 20km

Passenger Load Patterns

![passenger_ count](https://github.com/user-attachments/assets/0a04ce9d-dca9-415e-b8f0-410b11e5c355)

*92% of rides serve 1-2 passengers, with minimal 5+ passenger trips*

Feature Correlations
![correlation matrix](https://github.com/user-attachments/assets/3c526c49-490f-4d2b-9a66-25e34acefcc8)

Key insights: Distance strongly impacts fare, passenger count has minimal effect



## 🛠️ 3. Feature Engineering

- Extracted new time-based features:
  - `pickup_hour`, `pickup_day`, `pickup_month`, `pickup_date`  
- Created distance using Haversine formula
  # Haversine distance calculation
  ![hav](https://github.com/user-attachments/assets/10c7d929-2519-4c38-b0a2-a21e8e8531c4)


- Saved enhanced dataset to `enhanced_uber_fares.csv` for Power BI


## 📉 4. Power BI Analysis

### 🚦 Visualizations Built:
- Monthly and hourly fare patterns  
- Distance vs. fare comparisons  
- Peak/off-peak trend lines  
- Fare summary by passenger count  
- Time-series trend line of fare over months  
- Filled Map: Geographic distribution using pickup/dropoff points  

### 🔍 Filters and Drill-downs:
- Enabled slicers for hour, day, month, and passenger count  
- Latitude/Longitude mapped with "Do Not Summarize" setting


## 📊 5. Power BI Dashboard

- ✔️ Clean UI with consistent formatting  
- ✔️ Histograms and boxplots for fare distribution  
- ✔️ Map visuals displaying ride locations  
- ✔️ Responsive filters for interactivity  
- ✔️ Professional layout for insights and storytelling

📸 Screenshots:
- Data Load
  
<img width="1871" height="889" alt="Loaded data" src="https://github.com/user-attachments/assets/6dffda67-8a0a-4086-9dea-c447c45d5950" />

- #### Dashboard Visuals (fare trends, maps, etc.)
- 
- ### Fare amount Trends
  ![PowerBI Dashboard 1](https://github.com/user-attachments/assets/862ce4d5-1b90-4e09-b91f-0812c32b65bd)


### Fare Amount Trends (Weekdays/ WeekEnds) And over the Years
![PowerBI Dashboard 2](https://github.com/user-attachments/assets/1eb5ed03-aef5-4416-8930-b1890029b75a)

 Busiest Hours are between  12 pm - 13 pm and 18 pm - 19 pm,  19 pm being the busiest.

Busiest days are between Wednesday and Friday, Thursday being the busiest.

Busiest Months are between March and May, May being the busiest.

### Monthly and Annual Ride Trends
![PowerBI Dashboard 3](https://github.com/user-attachments/assets/66c4908d-fa97-4ba3-8672-49822cad4e0b)

### Dropoff Latitude and Fare Amount
![PowerBI Dashboard 4](https://github.com/user-attachments/assets/959eb30b-5c0b-48b2-b95d-23572cdc2371)


## 📑 6. Analytical Report

### 🧾 Introduction
This project aims to uncover hidden patterns in Uber’s NYC fare data and build a data-driven dashboard for strategic decision-making.

### 📍 Methodology
- Used Python for data cleaning and preparation  
- Used Power BI for dashboard development  
- Enhanced dataset with new features and columns  
- Cleaned outliers and ensured data validity  

### 📊 Analysis & Results
- Most rides happen between 4 PM–8 PM (peak hours)  
- Fare tends to increase with distance, but has some exceptions (outliers)  
- Few multi-passenger rides; most trips involve 1 passenger  
- Map reveals high-density pickup areas in central NYC

### 🧠 Recommendations
- Improve service availability during evening hours  
- Introduce promotions for long-distance low-fare trips  
- Consider optimizing routes in fare-dense regions


## 📂 Deliverables

- ✅ Power BI Dashboard File: `Uber_fares_dashboard.pbix`  
- ✅ Cleaned Dataset: `cleaned_uber_fares.csv`   
- ✅ Python Notebook: `Uber.ipynb`  
- ✅ README File (This document)



## ✅ Final Notes

- The project fulfills all six assignment requirements    
- Dashboard and report aligned with professional standards



> ✨ Thank you for reviewing my Uber Fare Analysis Project! ✨  
> Wishing you a data-driven future ahead!

