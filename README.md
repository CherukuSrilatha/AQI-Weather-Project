# AQI-Weather-Project
Analyzed Hyderabad’s AQI using weather data (2018–2024). Used machine learning for classification and regression to predict air quality based on features like temperature, humidity, pressure, rainfall, and wind.

---

## 📌 Project Overview

This project combines historical weather and air quality data to understand the impact of climate on pollution levels. It applies machine learning techniques to classify air quality categories and predict AQI values using weather features.

---

## 📂 Datasets Used

- `weather_2018_2024.csv` — Scraped weather data from tutiempo.net
- `Hyderabad_AQI_Dataset.csv` — AQI data for Hyderabad
- `enhanced_weather.csv` — Additional weather features
- `merged_aqi_weather.csv` — Final merged dataset on Date

---

## 📊 Features Used

- Temperature
- Humidity
- Dew Point
- Wind Speed
- Rainfall
- Pressure
- AQI (Target)

---

## 🤖 Machine Learning Tasks

### 🔹 Classification
- Predicts air quality category (e.g., Good, Moderate, Poor)
- Algorithms used: (e.g., Decision Tree, Random Forest, etc.)
- Evaluation: Accuracy, Precision, Recall, F1-Score

### 🔹 Regression
- Predicts exact AQI value
- Algorithms used: (e.g., Linear Regression, Random Forest Regressor, etc.)
- Evaluation: MAE, MSE, R² Score

---

## ⚙️ How to Run

1. Clone the repository
2. Install required libraries (Pandas, Scikit-learn, BeautifulSoup, etc.)
3. Run notebooks:
   - `MY_PRO.ipynb` – Data scraping and cleaning
   - `MY_PRO_CLA.ipynb` – Classification model
   - `MY_PRO_REG.ipynb` – Regression model

---

## 📈 Results

- Classification models achieved good accuracy.
- Initial models showed overfitting, which was addressed through tuning and feature selection.

---

## 🙋‍♀️ Author

**Cheruku Sri Latha**  
B.E. Artificial Intelligence & Data Science  
Chaitanya Bharathi Institute of Technology

---

## 📌 Acknowledgements

- [Tutiempo.net](https://www.tutiempo.net) for climate data
- [Central Pollution Control Board](https://cpcb.nic.in/) for AQI data
