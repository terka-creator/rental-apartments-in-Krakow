# rental-apartments-in-Krakow
Data analysis of rental apartments in Kraków from November 2023 to June 2024.

# 🏙️ Rental Apartment Analysis in Kraków

This project explores rental apartment listings in **Kraków, Poland**, focusing on identifying patterns, anomalies, and price-driving factors. It includes interactive visualizations of apartment locations using **Folium**.

## 📊 Project Objectives

- **Detect outliers** in apartment features, such as unusually high room counts for a given size.
- **Analyze the relationship** between apartment size and number of rooms.
- **Investigate whether proximity to the city center affects rental prices.**
- **Visualize apartment locations** on an interactive map of Kraków.

## 📍 Interactive Map

The project includes a **Folium-based interactive map** displaying the geographic distribution of rental offers in Kraków. Map is centered and zoomed around Kraków for intuitive navigation.

## 📁 Dataset

The dataset includes the following key features:

- `price` — rental price in PLN
- `area` — apartment size in square meters
- `rooms` — number of rooms
- `latitude`, `longitude` — geographic coordinates
- `distance_to_center` — distance from the city center (in km)
- `location` — neighborhood or district

> *(Source: [Apartment Prices in Poland] (https://www.kaggle.com/datasets/krzysztofjamroz/apartment-prices-in-poland/data)*

## 🧪 Methods Used

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Outlier detection (based on size-room mismatch)
- Correlation and trend analysis
- **Folium map for spatial exploration**
- Visualization using matplotlib, seaborn, and folium

## 📈 Key Questions Explored

- Are there apartments with **unusual room counts** relative to their size?
- Do **rental prices increase** as apartments are **closer to the city center**?
- How are apartments **geographically distributed** across Kraków?

## 🚀 How to Use

1. Open the notebook: `Rental apartments in Krakow.ipynb`
2. Run all cells step by step
3. The interactive map will display at the beginning of the notebook

## 🧰 Requirements

- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `folium`
- (optional) `scikit-learn` for modeling/outlier detection

Install requirements via pip:

```bash
pip install pandas numpy matplotlib seaborn folium scikit-learn
