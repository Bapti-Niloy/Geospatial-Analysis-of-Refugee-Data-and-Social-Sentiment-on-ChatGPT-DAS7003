
# 🌍 Geospatial Analysis of Refugee Data and Social Sentiment on ChatGPT (DAS7003)

Welcome to the repository for my **DAS7003 - Geospatial Analysis** coursework at Cardiff Metropolitan University (2024–25 Semester 2). This project applies geospatial data analytics and sentiment analysis to explore forced displacement trends and public perceptions of AI technologies using real-world datasets.

---

## 📌 Overview

This repository showcases my solutions to the practical assessment tasks that explore:
1. **Global refugee population trends** using UNHCR & World Bank data.
2. **Geospatial conflict events** using the UCDP Georeferenced Event Dataset (GED).
3. **Sentiment and subjectivity analysis** of tweets related to the launch of ChatGPT using location-based social media data.

---

## 📁 Project Structure

```
📦 Geospatial-Refugee-Sentiment-Analysis/
│
├── 📄 DAS7003_stXXXXXX_PRAC1.ipynb      # Main Jupyter Notebook with all solutions
├── 📄 API_SM.POP.REFG.OR_DS2.csv        # World Bank Refugee Population dataset
├── 📄 GEDEvent_v24_1.csv                # UCDP Georeferenced Conflict Events dataset
├── 📄 tweets.csv                        # Twitter dataset for ChatGPT sentiment analysis
├── 📄 DAS7003_S2_PRAC1_Assessment.pdf   # Official assessment brief
└── 📄 README.md                         # This file
```

---

## 🧠 Key Tasks Covered

### 🔹 Task 2.1: Choropleth Visualisation (2000 vs 2023)
- Cleaned and preprocessed refugee data using `pandas` and `geopandas`.
- Created choropleth maps to show country-wise refugee populations for 2000 and 2023.
- Provided comparative visual analysis and interpretation.

### 🔹 Task 2.2: Conflict & Refugee Analysis
- Merged refugee and conflict datasets.
- Visualised spatial correlations and trends including:
  - Countries with >5000 conflicts since 1993.
  - Middle East refugee-conflict intersections.
  - Top 10 refugee-hosting nations and their conflict profiles.
  - Change in refugee population (2003–2023).
  - Correlation between mean refugee population & conflict intensity (1990–2023).

### 🔹 Task 3: Geospatial Sentiment Analysis on Tweets
- Filtered verified tweets with geolocation and >100 followers.
- Geocoded tweet locations (latitude/longitude).
- Calculated polarity and subjectivity scores using `TextBlob`.
- Plotted geospatial sentiment maps and storified findings from a market research/advisory perspective.

---

## 🛠 Tools & Libraries Used

- **Python**: Jupyter Notebook, Pandas, GeoPandas, Matplotlib, Seaborn, TextBlob, Geopy, Folium
- **Datasets**: World Bank (Refugee), UCDP GED (Conflict), Twitter (ChatGPT-related)
- **Geocoding APIs**: Nominatim (OpenStreetMap)

---

## 📊 Skills Demonstrated

- Geospatial data cleaning and merging
- Choropleth map generation
- Temporal-spatial trend analysis
- Social media data mining and NLP-based sentiment analysis
- Integration of geopolitical data for storytelling

---

## 📌 Assessment Info

This project satisfies the requirements of:
- [✔] LO1: Geospatial concept application
- [✔] LO2: Social media analytics
- [✔] LO3: Prototype and implement analysis framework
- [✔] LO4: Identify trends and technologies in geospatial analysis

---

## 👨‍🎓 Author

**Name:** Bapti Niloy Sarkar  
**Student ID:** st20310829  
**University:** Cardiff Metropolitan University  
**Module:** DAS7003 - Geospatial Analysis  
