# 🌦️ Weather Dashboard Project

## 📌 Overview
This project is a **Weather Data Analysis Dashboard** built using data collected from the **OpenWeather API**. The data is processed, stored in Excel, and visualized in an interactive dashboard to analyze weather patterns and attributes.

The dashboard provides insights into temperature, wind, precipitation, radiation, and other atmospheric conditions.

---

## 🚀 Project Workflow

1. **Data Collection**
   - Weather data is fetched using the **OpenWeather API**
   - Includes multiple attributes like temperature, humidity, wind, pressure, etc.

2. **Data Storage**
   - Collected data is stored in **Excel (.xlsx format)**
   - Data is structured and cleaned for analysis

3. **Data Processing**
   - Categorized attributes into:
     - Metric System
     - Imperial System
     - Other (Derived/Indicators)
   - Added units, meanings, and classifications

4. **Dashboard Creation**
   - Built an interactive dashboard (Power BI / Excel / Visualization Tool)
   - Visualized trends and summaries

---

## 📊 Dashboard Features

### 🔹 Summary Cards
- Total number of attributes
- Number of systems (Metric, Imperial, Other)
- Average values of key parameters

### 🔹 Filters
- Filter data by system:
  - Metric
  - Imperial
  - Other

### 🔹 Visualizations
- 📈 **Average Value by Time** (Time Series Analysis)
- 📊 **Sum of Value by Attribute** (Comparison)
- 🥧 **Count of Attributes by System** (Distribution)

### 🔹 Attribute Table
- Attribute name
- Emoji/Icon representation 🌡️💨🌧️
- Description (Proper meaning)
- System classification

---

## 📂 Dataset Information

The dataset contains the following types of attributes:

### 🌡️ Temperature
- temp_c, temp_f, feelslike_c, feelslike_f, etc.

### 💨 Wind
- wind_kph, wind_mph, gust_kph, gust_mph

### 🌧️ Precipitation
- precip_mm, precip_in, chance_of_rain

### ❄️ Snow
- snow_cm, chance_of_snow

### 🌬️ Pressure
- pressure_mb, pressure_in

### ☀️ Radiation
- short_rad, diff_rad, dni, gti

### 💧 Others
- humidity, cloud, uv, is_day

---

## 🧠 Key Insights

- Metric system is the most commonly used in the dataset
- Radiation features (DNI, GTI) are important for solar analysis
- Probability features (chance_of_rain, chance_of_snow) are useful for prediction models
- Duplicate units (Metric vs Imperial) can be optimized for ML models

---

## 🛠️ Tools & Technologies

- **API**: OpenWeather API  
- **Data Storage**: Microsoft Excel  
- **Visualization**: Power BI / Excel Dashboard  
- **Data Processing**: Manual + Data Cleaning Techniques  

---

## 💡 Use Cases

- Weather data analysis  
- Machine Learning feature engineering  
- Climate and environmental studies  
- Dashboard design practice  


---

## 🔮 Future Improvements

- Automate data collection using Python (API integration)
- Store data in a database (MySQL / MongoDB)
- Build a real-time dashboard
- Deploy as a web app using Streamlit

