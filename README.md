# 🌫️ AQI_Forecasting  
**AQI Forecasting Using Python & Pandas**

This project involves analyzing and preprocessing air quality data to forecast **Air Quality Index (AQI)** levels. It uses Python and the `pandas` library for data manipulation, including essential steps like handling missing data, converting date/time formats, and preparing the dataset for potential modeling or visualization.

---

## 📁 Project Summary

- **Dataset**: Contains air quality measurements including **PM2.5**, **PM10**, **NO2**, etc., recorded along with **date and time**.
- **Goal**: Prepare and clean the dataset for accurate AQI forecasting or visualization.
- **Notebook**: All steps are performed and documented in a **Jupyter Notebook**.

---

## ✅ Features

- Converts date from `DD/MM/YYYY` to standard `YYYY-MM-DD` format.
- Converts time strings to `datetime.time` objects.
- Handles missing values (`NaN`) in numerical columns.
- Calculates the mean of all numeric columns safely.
- Selects only numeric data for aggregation and analysis.
- Prepares data for future forecasting models or visualization tools.

---

## 🧠 Libraries Used

- `pandas`
- `numpy`
- *(optional)* `matplotlib`, `seaborn` for future visualization

---

## ⚙️ Getting Started

1. Clone this repo or upload the notebook to your environment.
2. Ensure the dataset CSV is available and paths are correctly set.
3. Run through the cells to clean and process the data.

---

## 📝 Notes

- Missing values are handled using **mean imputation**.
- Date/time conversions are done carefully to avoid errors with misinterpreted formats.
- Designed to be used as a starting point for building **time series models or dashboards**.
