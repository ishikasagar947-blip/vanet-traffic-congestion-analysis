# VANET Traffic Congestion Analysis 🚦

## 📖 Project Overview
This project analyzes **Vehicular Ad-hoc Network (VANET) traffic data** to study congestion patterns, weather impacts, and communication reliability.  
The goal is to derive meaningful insights using **feature engineering** and **exploratory data analysis (EDA)**, making the dataset ready for predictive modeling.

---

## 🎯 Objectives
- Identify congestion distribution across traffic states.
- Analyze the relationship between vehicle density, queue length, and average speed.
- Study the impact of weather (rain intensity) on traffic flow.
- Evaluate communication reliability (channel busy ratio vs packet loss).
- Generate engineered features for advanced modeling.

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Analytics & Visualization**

---

## 📊 Feature Engineering
New analytical features were created:
- `speed_density_ratio` → Efficiency measure (speed vs density).
- `congestion_pressure` → Combined congestion severity (density × wait time).
- `wireless_congestion_intensity` → VANET communication degradation (channel busy × packet loss).

---

## 🔎 Exploratory Data Analysis (EDA)
Key visualizations:
1. **Congestion Distribution** → Frequency of traffic states.
2. **Average Speed vs Congestion** → Speed decreases with congestion severity.
3. **Density vs Queue Length** → Positive correlation confirms jam buildup.
4. **Rain Intensity vs Speed** → Weather negatively impacts traffic flow.
5. **Channel Busy Ratio vs Packet Loss** → Communication reliability declines under congestion.
6. **Correlation Heatmap** → Strong feature interdependencies identified.

---

## 📈 Insights
- Heavy congestion states dominate the dataset.
- Average speed consistently decreases with congestion.
- Vehicle density strongly correlates with queue length.
- Rain intensity negatively impacts traffic efficiency.
- Communication reliability worsens with higher channel busy ratios.
- Correlation heatmap highlights predictors of congestion and efficiency.

---

## 🚀 Next Steps
- Build predictive models for congestion classification.
- Extend analysis with SQL queries for traffic reporting.
- Deploy dashboards using **Power BI / Streamlit** for real-time visualization.

---

## 👩‍💻 Author
**Ishika Sagar**  
Bachelor of Computer Applications (BCA), 2026  
Aspiring Data Analyst | Python • SQL • Power BI • Excel  
