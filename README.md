# 🚗 Road Accident Analysis | Power BI

## 📌 Project Overview

This project is an end-to-end **Road Accident Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze road accident data and identify meaningful patterns related to accidents, casualties, accident severity, vehicle types, road conditions, light conditions, and geographical distribution.

The project follows a complete data analytics workflow, starting from raw data preparation and transformation to data modeling, DAX calculations, and interactive dashboard development.

---

## 🎯 Project Objectives

- Analyze overall road accident and casualty trends
- Identify accident severity patterns
- Analyze casualties by vehicle type
- Compare casualties across urban and rural areas
- Analyze road types associated with casualties
- Understand the impact of light conditions
- Analyze road surface and weather conditions
- Identify geographical patterns in accident casualties
- Compare current-year and previous-year accident trends
- Build an interactive dashboard for data-driven analysis

---

## 🔄 Project Workflow

**Kaggle Dataset**  
↓  
**Data Cleaning & Transformation**  
↓  
**Power Query**  
↓  
**Data Modeling**  
↓  
**Calendar Table**  
↓  
**DAX Measures & Calculations**  
↓  
**Interactive Power BI Dashboard**  
↓  
**Insights & Analysis**

---

## 🗂️ Dataset

The dataset used in this project was obtained from **Kaggle**.

The dataset contains information related to road accidents, including:

- Accident Date
- Accident Severity
- Number of Casualties
- Vehicle Type
- Road Type
- Road Surface Conditions
- Weather Conditions
- Light Conditions
- Urban / Rural Area
- Latitude & Longitude
- Junction Details
- Carriageway Hazards
- Local Authority
- Accident Index

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

The major transformation steps included:

- Connecting to the source dataset
- Navigating and selecting required data
- Promoting headers
- Correcting data types
- Replacing inconsistent values
- Filtering unnecessary records
- Preparing the dataset for analysis

### Power Query Applied Steps

`Source → Navigation → Promoted Headers → Changed Type → Replaced Value → Filtered Rows`

---

## 🏗️ Data Modeling

A structured data model was created to support efficient analysis.

A dedicated **Calendar Table** was created containing:

- Date
- Year
- Month
- Month Number

The Calendar table was connected with the main accident data using the **Accident Date** field.

### Relationship

`Data[Accident Date] → Calendar[Date]`

**Relationship:** Many-to-One (*:1)  
**Cross-filter Direction:** Single

---

## 📐 DAX & Calculations

DAX measures were created to calculate important analytical metrics.

Key metrics include:

- Total Casualties
- Total Accidents
- Fatal Casualties
- Serious Casualties
- Slight Casualties
- Current Year Casualties
- Previous Year Casualties
- Monthly Accident Trends
- Year-over-Year Analysis

---

## 📊 Dashboard Features

The interactive dashboard provides analysis through multiple visualizations.

### 🔹 Key Performance Indicators

- Total CY Casualties
- Total CY Accidents
- Fatal Casualties
- Serious Casualties
- Slight Casualties

### 🔹 Vehicle Analysis

Casualties are analyzed across different vehicle categories such as:

- Cars
- Bikes
- Buses
- Vans
- Agricultural Vehicles
- Other Vehicles

### 🔹 Time-Based Analysis

- Monthly casualty trends
- Current Year vs Previous Year comparison
- Accident trend analysis

### 🔹 Location Analysis

- Urban vs Rural casualties
- Geographical accident distribution
- Accident casualty mapping using latitude and longitude

### 🔹 Road & Environmental Analysis

- Road Type
- Road Surface Conditions
- Weather Conditions
- Light Conditions

### 🔹 Interactive Filters

- Road Surface
- Weather Conditions

---

## 📷 Project Screenshots

### Power Query Transformation

![Power Query](screenshots/power-query.png)

### Data Model

![Data Model](screenshots/data-model.png)

### Calendar Table

![Calendar Table](screenshots/calendar-table.png)

### Final Dashboard

![Dashboard](screenshots/Final-dashboard.png)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard & Visualization |
| Power Query | Data Cleaning & Transformation |
| DAX | Calculations & KPIs |
| Data Modeling | Analytical Model |
| Excel | Data Handling |
| SQL | Data Analysis |
| Python | Data Analytics |
| Machine Learning | Future Enhancement |
| AI | Future Enhancement |

---

## 🚀 Future Enhancement

The next phase of this project is to extend the analytical dashboard into an **AI-powered real-time road safety system**.

The planned system could combine:

- Live traffic data
- Real-time road conditions
- Historical accident data
- Machine Learning models
- Route-based analysis

The system could identify potential hazards such as:

- Potholes
- Road damage
- Heavy traffic
- Hazardous road conditions
- Accident-prone zones

Based on the detected risk level, the system could provide **early safety alerts and notifications** to users before they reach a potentially hazardous location.

### Future Technology Focus

`Python` `SQL` `Machine Learning` `AI` `Real-Time Data` `Power BI`

---

## 📈 Key Outcome

This project demonstrates an end-to-end approach to transforming raw road accident data into an interactive analytical solution.

It combines **data preparation, data modeling, DAX, visualization, and analytical thinking** to generate meaningful insights into road safety patterns.

---

## 👨‍💻 Author

**Krishna Kiran Ladhe**

MCA Student | Data Science | Machine Learning | Data Analytics

### Skills

`Python` `SQL` `Machine Learning` `Power BI` `DAX` `Power Query` `Data Analytics` `Data Visualization`

---

⭐ If you find this project useful, feel free to explore the repository and connect with me.

