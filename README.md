# 🌦️ Weather Forecasting and Analysis – Bangalore (1990–2021)

This project involves extensive analysis and visualization of historical weather data for Bangalore over a period of 32 years. It covers key aspects like temperature trends, rainfall patterns, and extreme weather events using Python-based data science tools.

---

## 📊 Project Objective

- Analyze historical weather data (1990–2021) for Bangalore.
- Perform data cleaning and feature engineering.
- Identify trends in temperature and rainfall.
- Visualize key findings to uncover seasonal patterns and anomalies.

---

## 📁 Dataset Details

- **File**: `Bangalore_1990_2022_BangaloreCity.csv`
- **Duration**: Jan 1990 to Dec 2021 (2022 data was removed due to incompleteness)
- **Features**:
  - `time`: Date
  - `tavg`: Average temperature
  - `tmin`: Minimum temperature
  - `tmax`: Maximum temperature
  - `prcp`: Precipitation

---

## 🔧 Data Cleaning and Preprocessing

- Converted date column to `datetime` format.
- Set `time` column as index.
- Handled missing values using:
  - Forward fill (`tavg`, `tmin`, `tmax`)
  - Replaced missing precipitation with `0.0`
- Removed year 2022 as it had incomplete data.

---

## 📈 Data Analysis Highlights

- **Hottest Year**: 2019 (Avg Temp: 24.48°C)
- **Coolest Year**: 1992 (Avg Temp: 23.22°C)
- **Hottest Month**: April 2016 (Avg Temp: 29.64°C)
- **Coolest Month**: January 1992 (Avg Temp: 19.8°C)
- **Hottest Day**: 25th April 2016 (Max Temp: 39.2°C)
- **Coolest Day**: 8th August 1992 (Min Temp: 9.3°C)
- **Wettest Year**: 2007
- **Driest Year**: 2003
- **Highest Rainfall Day**: 13th July 2007 (271.3 mm)

---

## 📊 Visualizations

- Line charts of:
  - Daily average temperature
  - Daily precipitation
  - Yearly average temperature & rainfall
  - Monthly average temperature & rainfall
- Grouped analysis by `year`, `month`, and `day`.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📌 Observations

- Temperature rises between March and May.
- Noticeable spike in temperature and rainfall during September.
- Rainfall pattern in Bangalore is very strange as it increases between April and May and rises again in October.