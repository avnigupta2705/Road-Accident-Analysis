# 🚗 Road Accident Analysis Dashboard

## 📊 Project Overview

The **Road Accident Analysis Dashboard** is an interactive Power BI project designed to analyze road accident patterns, casualties, accident severity, road conditions, vehicle types, and geographic distribution.

The dashboard transforms a large road accident dataset into meaningful visual insights that can help users understand **when, where, and under what conditions road accidents and casualties occur**.

The project combines **Excel data preparation, Power BI data modeling, DAX measures, interactive visualizations, and geographic analysis** to provide a comprehensive view of road accident trends.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze the number of road accidents and casualties.
* Compare current-year performance with the previous year.
* Analyze accidents based on severity.
* Identify monthly casualty trends.
* Understand casualties by vehicle type.
* Compare casualties across different road types.
* Analyze casualties in urban and rural areas.
* Study the impact of light conditions.
* Analyze casualty distribution geographically.
* Allow users to filter the analysis based on weather and road surface conditions.

---

## 🗂️ Dataset

The analysis is based on a road accident dataset containing:

* **307,973 accident records**
* **21 attributes**
* Accident information including date, location, severity, road conditions, weather, vehicles, and casualties.

### Dataset Fields

| Column                       | Description                                      |
| ---------------------------- | ------------------------------------------------ |
| `Accident_Index`             | Unique identifier for each accident              |
| `Accident Date`              | Date on which the accident occurred              |
| `Day_of_Week`                | Day of the week of the accident                  |
| `Junction_Control`           | Type of junction control                         |
| `Junction_Detail`            | Type/details of junction                         |
| `Accident_Severity`          | Severity classification of the accident          |
| `Latitude`                   | Geographic latitude                              |
| `Longitude`                  | Geographic longitude                             |
| `Light_Conditions`           | Lighting conditions at the time of accident      |
| `Local_Authority_(District)` | Local authority/district where accident occurred |
| `Carriageway_Hazards`        | Hazards present on the carriageway               |
| `Number_of_Casualties`       | Number of casualties involved                    |
| `Number_of_Vehicles`         | Number of vehicles involved                      |
| `Police_Force`               | Police force responsible for the area            |
| `Road_Surface_Conditions`    | Condition of the road surface                    |
| `Road_Type`                  | Type of road                                     |
| `Speed_limit`                | Speed limit at the accident location             |
| `Time`                       | Time of the accident                             |
| `Urban_or_Rural_Area`        | Classification of the accident location          |
| `Weather_Conditions`         | Weather conditions during the accident           |
| `Vehicle_Type`               | Type of vehicle involved                         |

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Microsoft Excel**
* **Power BI Data Modeling**
* **Data Visualization**
* **Geospatial Analysis**

---

# 📈 Dashboard Features

## 1. KPI Overview

The dashboard provides high-level KPI cards for quickly monitoring accident performance.

The KPIs include:

* **Current Year Accidents**
* **Current Year Casualties**
* **Year-over-Year Accident Change**
* **Year-over-Year Casualty Change**
* **Fatal Accident Casualties**
* **Serious Accident Casualties**
* **Slight Accident Casualties**

These KPIs provide a quick summary before moving into detailed analysis.

---

## 2. Casualties by Vehicle Type

The dashboard analyzes casualties according to vehicle categories.

This helps identify how casualty numbers are distributed across different vehicle types such as:

* Cars
* Motorcycles
* Buses
* Vans
* Other vehicle categories

The visualization makes it easier to compare the contribution of different vehicle categories to overall casualties.

---

## 3. Monthly Casualty Trend

### CY Casualties vs PY Casualties by Month

A monthly trend visualization compares:

* **Current Year (CY) casualties**
* **Previous Year (PY) casualties**

This helps identify:

* Monthly fluctuations
* Seasonal patterns
* Periods with comparatively higher casualties
* Changes between the current and previous year

The comparison is particularly useful for identifying whether casualty patterns are changing over time.

---

## 4. Casualties by Road Type

The dashboard provides a breakdown of casualties by road type.

This allows analysis across different road categories such as:

* Single carriageway
* Dual carriageway
* One-way street
* Roundabout
* Other road types

This visualization helps understand which road environments account for larger casualty volumes.

---

## 5. Urban vs Rural Analysis

A donut chart compares casualties between:

* **Urban areas**
* **Rural areas**

This provides a geographical classification of casualty distribution and allows users to explore how accident impact differs between urban and rural environments.

---

## 6. Casualties by Light Conditions

The dashboard analyzes casualties according to lighting conditions.

Examples include:

* Daylight
* Darkness
* Darkness with street lights
* Other lighting conditions

This helps investigate the relationship between visibility conditions and casualty occurrence.

---

## 7. Geographic Accident Analysis

The **Casualty by Location** map uses:

* Latitude
* Longitude
* Local Authority/District
* Number of casualties

to display the geographic distribution of casualties.

This allows users to identify areas with relatively higher concentrations of road accident casualties.

---

## 8. Interactive Filters

The dashboard includes interactive slicers for:

### 🌦️ Weather Conditions

Users can filter the dashboard based on weather conditions.

### 🛣️ Road Surface Conditions

Users can also filter the analysis according to road surface conditions such as:

* Dry
* Wet or damp
* Frost/ice
* Other conditions

These filters allow users to perform more focused analysis instead of relying only on overall accident statistics.

---

# 🔄 Data Analysis Process

The project follows a typical BI analysis workflow:

```text
Raw Excel Dataset
       ↓
Data Cleaning & Preparation
       ↓
Power BI Data Model
       ↓
DAX Measures & Calculations
       ↓
Interactive Visualizations
       ↓
Road Accident Insights
```

---

# 🧮 Key DAX Analysis

The dashboard uses DAX measures to calculate important metrics such as:

* Current Year Accidents
* Current Year Casualties
* Previous Year metrics
* Year-over-Year changes
* Casualties by accident severity
* Casualty aggregations across different dimensions

A separate calendar table is also used to support time-based analysis and current-year vs previous-year comparisons.

---

# 📊 Dashboard Layout

The dashboard contains the following major analytical sections:

| Section           | Analysis                                        |
| ----------------- | ----------------------------------------------- |
| KPI Cards         | Current year accidents and casualties           |
| YoY KPIs          | Year-over-year accident and casualty comparison |
| Severity KPIs     | Fatal, Serious and Slight casualties            |
| Vehicle Analysis  | Casualties by vehicle type                      |
| Time Analysis     | Monthly CY vs PY casualty trend                 |
| Road Analysis     | Casualties by road type                         |
| Area Analysis     | Urban vs Rural casualties                       |
| Lighting Analysis | Casualties by light conditions                  |
| Map Analysis      | Geographic casualty distribution                |
| Filters           | Weather and road surface conditions             |

---

# 💡 Key Analytical Questions

This dashboard can be used to answer questions such as:

* How many accidents occurred during the current year?
* How many casualties resulted from those accidents?
* How has the current year changed compared with the previous year?
* How are casualties distributed across accident severity levels?
* Which vehicle types contribute to the highest casualty counts?
* Which months experience higher casualty levels?
* Which road types account for the largest number of casualties?
* How do casualties differ between urban and rural areas?
* How do light conditions relate to casualty occurrence?
* Where are casualties geographically concentrated?
* How do weather and road-surface conditions affect the analysis?

---


# 🚀 How to Use the Dashboard

1. Download or clone this repository.
2. Open `Road accident dashboard.pbix` using **Microsoft Power BI Desktop**.
3. Interact with the KPI cards and visualizations.
4. Use the **Weather Conditions** and **Road Surface Conditions** slicers to filter the dashboard.
5. Hover over charts and map points to explore detailed values.
6. Use the visual interactions to investigate accident and casualty patterns.

---

# 📌 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Data Cleaning
* Power BI
* DAX
* Data Modeling
* KPI Development
* Time-Series Analysis
* Year-over-Year Analysis
* Data Visualization
* Geographic Analysis
* Interactive Dashboard Development
* Business Intelligence

---

# 🎓 Project Outcome

The project demonstrates how a large accident dataset can be transformed into an interactive Business Intelligence solution.

Instead of analyzing thousands of individual accident records manually, the dashboard provides a consolidated view of **accident volume, casualties, severity, time trends, road characteristics, environmental conditions, vehicle categories, and geographic patterns**.

The project also demonstrates the ability to design an end-to-end Power BI workflow, from raw structured data to an interactive analytical dashboard.

---

## 📷 Dashboard Preview

Add a screenshot of your Power BI dashboard here:

```markdown
![Road Accident Dashboard](dashboard-preview.png)
```

---

## ⭐ Project Highlights

* 📊 **307K+ accident records analyzed**
* 📈 Current Year vs Previous Year analysis
* 🚗 Vehicle-type casualty analysis
* 🛣️ Road-type analysis
* 🌦️ Weather and road-surface filtering
* 🌙 Light-condition analysis
* 🗺️ Geographic casualty mapping
* ⚠️ Accident severity analysis
* 📅 Monthly trend analysis
* 💻 Interactive Power BI dashboard

---

## 👩‍💻 Author

**Avni Gupta**

Data Analyst | Power BI | SQL | Python | Excel

---

⭐ If you found this project useful, feel free to explore the repository and the Power BI dashboard.
