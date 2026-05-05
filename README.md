# 🚲 Divvy Bike Share — Rider Behaviour Analysis (2019 vs 2020)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-orange)
![YoY](https://img.shields.io/badge/Analysis-Year%20on%20Year-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> *"What happens to a city's bike rides when a pandemic hits?"*  
> This project answers that question — and uncovers two distinct rider personas along the way.

---

## 🎯 Objective

Analyse Q1 ridership data from **Divvy**, Chicago's bike-share company, for 2019 and 2020 
to understand rider behaviour patterns and the real-world impact of COVID-19 on urban mobility.

---

## 📦 Dataset

| File | Description |
|------|-------------|
| `Divvy_Trips_2019_Q1.zip` | Q1 2019 trip data (zipped due to file size) |
| `Divvy_Trips_2020_Q1.zip` | Q1 2020 trip data (zipped due to file size) |

**Source:** [Divvy Public Trip Data](https://divvybikes.com/system-data)

> **Note:** CSV files are zipped due to GitHub file size limitations. 
> Extract before running the notebook.

---

## 🔍 Analysis Sections

- **Data Pre-processing** — Merging, cleaning, feature engineering
- **Rider Type Analysis** — Members vs Casual riders
- **Trip Duration Patterns** — Who rides longer and when?
- **Time Patterns** — Hourly, daily and monthly trends
- **Station Analysis** — Top start and end stations by rider type
- **Demographics** — Age and gender distribution
- **Year-on-Year Comparison** — 2019 vs 2020 ridership trends

---

## 💡 Key Findings

### Two Distinct Rider Personas
| Behaviour | Members | Casual Riders |
|-----------|---------|---------------|
| Avg Trip Duration | ~8 minutes | ~23 minutes |
| Peak Usage | 8am & 5pm weekdays | Weekends & midday |
| Top Stations | Office & transit hubs | Tourist hotspots |
| Age Group | 25–35 years | 24–25 years |
| Usage Pattern | Commute | Leisure & recreation |

### The COVID-19 Signal 🦠
- January and February 2020 ridership was **higher** than 2019
- March 2020 shows a **sharp drop** — perfectly aligning with 
  COVID-19 lockdowns hitting Chicago in mid-March 2020
- Real-world events are clearly visible in the data

---

## 📋 Business Recommendations

- 🎯 Launch **weekend conversion campaigns** at casual hotspot stations 
  with membership pricing incentives
- 💰 Highlight **cost savings of membership** for riders using service 3x+ per week
- 📱 Target **25–35 age group digitally** via social media for casual-to-member conversion
- 👩 Design **female-focused campaigns** to grow the female rider segment
- 🌸 Increase **March marketing efforts** to capture the spring ridership growth wave

---

## 🛠️ Technologies Used

- Python 3.11 — Pandas, Matplotlib, Seaborn
- Jupyter Notebook
- Year-on-Year comparative analysis

---

## 📁 Project Structure

    Divvy-Bikeshare-Rider-Analysis/
    ├── python_EDA_RideShareAnalytics.ipynb   # Main analysis notebook
    ├── Divvy_Trips_2019_Q1.zip               # 2019 Q1 trip data (zipped)
    ├── Divvy_Trips_2020_Q1.zip               # 2020 Q1 trip data (zipped)
    └── README.md

---

**Author:** Anjana Ambika | **Date:** April 2026
