# Uber Trip Analysis Dashboard using Power BI

## Project Overview

This project presents an interactive Uber Trip Analysis Dashboard developed using Microsoft Power BI. The dashboard provides deep insights into Uber trip operations, customer ride behavior, booking trends, trip distances, payment methods, vehicle performance, and location-based analytics.

The dashboard was designed to help analyze large-scale ride-sharing data through dynamic visualizations and KPI tracking. The project focuses on transforming raw ride data into meaningful business insights using Power BI, Power Query, and DAX.

---

# Project Objectives

* Analyze Uber booking trends and ride patterns.
* Monitor revenue and booking performance.
* Identify peak ride hours and busiest days.
* Understand customer payment preferences.
* Analyze vehicle-wise booking distribution.
* Study pickup and drop-off location trends.
* Build an interactive dashboard for business intelligence reporting.

---

# Tools & Technologies Used

| Tool/Technology    | Purpose                                 |
| ------------------ | --------------------------------------- |
| Microsoft Power BI | Data Visualization & Dashboard Creation |
| Power Query        | Data Cleaning & Transformation          |
| DAX                | KPI Measures & Calculations             |
| Microsoft Excel    | Dataset Handling                        |
| Data Analytics     | Business Insight Generation             |

---

# Dataset Information

The dataset contains Uber trip records including:

* Trip ID
* Pickup Date & Time
* Drop-off Time
* Passenger Count
* Trip Distance
* Booking Value
* Payment Type
* Vehicle Type
* Pickup Location
* Drop-off Location

The dataset was cleaned and transformed before visualization to ensure accuracy and consistency.

---

# Dashboard Pages

## 1. Overview Analysis

The Overview Analysis page provides a complete summary of Uber trip performance using KPI cards and charts.

### Key Metrics:

* Total Bookings: 103.7K
* Total Booking Value: $1.6M
* Average Booking Value: $15
* Total Trip Distance: 349K Miles
* Average Trip Distance: 3 Miles
* Average Trip Time: 16 Minutes

### Features:

* Payment Type Analysis
* Trip Distance Analysis
* Vehicle Type Analysis
* Location Analysis
* Booking Trends by Day
* Most Frequent Pickup & Drop-off Locations

---

## 2. Time Analysis

The Time Analysis page focuses on ride trends based on hours and weekdays.

### Features:

* Hourly Trip Distance Analysis
* Day-wise Booking Analysis
* Heatmap Visualization
* Peak Ride Time Identification
* Daily Ride Performance

### Insights:

* Peak demand occurs during evening hours.
* Weekend trip activity is higher than weekdays.
* Ride demand gradually increases throughout the day.

---

## 3. Details Page

The Details page contains complete ride-level information in tabular format.

### Included Columns:

* Trip ID
* Pickup Date
* Pickup Hour
* Vehicle Type
* Payment Type
* Passenger Count
* Trip Distance
* Booking Value
* Pickup Location
* Total Booking

This page allows detailed inspection of individual trips and operational records.

---

# Key Business Insights

* UberX generated the highest number of bookings.
* Penn Station/Madison Sq West was the most frequent pickup point.
* Upper East Side North was the most common drop-off location.
* Evening hours showed the highest ride demand.
* Cash and Uber Pay were the most preferred payment methods.
* Weekend trips covered more distance compared to weekdays.

---

# Data Cleaning & Transformation

The following data preparation steps were performed:

* Removed null values
* Corrected inconsistent data formats
* Standardized date and time columns
* Created calculated columns using DAX
* Generated KPI measures
* Optimized data model relationships

---

# DAX Measures Used

Some important DAX calculations used in the project:

```DAX
Total Booking = COUNT(Trip[Trip ID])

Total Booking Value = SUM(Trip[Booking Value])

Average Booking Value = AVERAGE(Trip[Booking Value])

Total Trip Distance = SUM(Trip[Trip Distance])

Average Trip Distance = AVERAGE(Trip[Trip Distance])
```

---

# Dashboard Features

* Interactive Filters & Slicers
* KPI Cards
* Dynamic Charts
* Heatmaps
* Vehicle Analysis
* Location Analysis
* Responsive Dashboard Layout
* Drill-down Capability

---

# Screenshots

## Overview Dashboard

<img width="1423" height="785" alt="image" src="https://github.com/user-attachments/assets/2728bbd6-5418-4cfe-9f59-65627f211b37" />


## Time Analysis Dashboard

<img width="1422" height="792" alt="image" src="https://github.com/user-attachments/assets/879ae96e-e681-44ef-8ee2-9de43c80986d" />


## Details Dashboard

<img width="1422" height="804" alt="image" src="https://github.com/user-attachments/assets/87b1dcc9-efab-4df9-8791-629934440361" />


---

# Conclusion

The Uber Trip Analysis Dashboard successfully transforms raw trip data into interactive business insights using Power BI. The project demonstrates skills in data analytics, business intelligence, dashboard design, data modeling, DAX calculations, and data visualization.

This dashboard can help organizations monitor ride performance, optimize operations, and improve decision-making using analytical reporting.

---

# Future Enhancements

* Real-time dashboard integration
* Predictive analytics using machine learning
* Customer segmentation analysis
* Geographical map visualizations
* Advanced KPI forecasting

---
