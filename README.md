# ✨ City Metrics Analysis: Operational and Public Service Trends ✨

## 🌟 Project Summary
**Analyzing Urban Incident and Service Metrics for Operational Insights**

This project analyzes a city's operational metrics, public satisfaction surveys, and service delivery indicators. By cleaning, preprocessing, and categorizing data from multiple public services, it uncovers critical performance trends, identifies operational gaps, and proposes areas for improvement to enhance overall service delivery and safety.

---

## 📊 Data Preprocessing Steps
To ensure a reliable foundation for analysis, thorough data cleaning and preprocessing techniques were applied:

* 🧹 **Null Value Removal:** Eliminated all null values in the "day score" column to maintain data completeness.
* 🔎 **Data Filtering:** Removed entries missing critical temporal data (day, week, month, quarter).
* ❌ **Duplicate Removal:** Erased duplicate rows to ensure data consistency and avoid overestimation in incident counts.

These steps ensured the dataset's integrity, enabling meaningful trend analysis and actionable insights.

---

## 🧩 Metric Categories/ Table columns

### 🛡️ Crime and Safety Metrics
- Stabbings (Trend)
- Shootings (Trend)
- Homicides (Trend)

These metrics track safety and security patterns across different timescales to identify high-risk periods and areas.

### ⚙️ Operational Efficiency Metrics
- EMS (Emergency Medical Services) Response Time
- Boston Fire Department (BFD) Response Time
- Streetlight On-Time Percentage
- On-Time Permit Reviews
- Trash Pickup Schedule Adherence
- Water Service Delivery Time
- Snow Removal Efficiency
- Traffic Signal Repair Time
- Road Pothole Repair Time

These indicators measure how efficiently city services respond to operational demands.

### 📞 Public Satisfaction Surveys
- 311 Call Center Performance
- Constituent Experience Surveys

Survey responses reflect citizen satisfaction levels and identify areas needing service quality improvements.

### 🏫 Service Delivery Metrics
- Boston Public Schools (BPS) Attendance Rates
- Library Usage Trends

Service delivery metrics gauge engagement and accessibility in education and cultural services.

---

## 📈 Key Analytical Findings

### ⏰ Incident Trends by Time of Day
* **Morning Peak (7 AM):** Over 3,000 incidents reported during morning commutes.
* **Midday Stability (10 AM–5 PM):** Incident rates stabilized during working hours.
* **Evening Surge (6 PM):** Significant increase during evening commutes, dropping after 8 PM.
* **Late Night Drop (2–3 AM):** Minimal incident occurrences during late-night hours.

### ⚠️ Operational Efficiency Gaps
* **Streetlight On-Time Percentage** and **EMS Response Time** fell below target benchmarks.
* **Trash Pickup Adherence** and **Snow Removal Efficiency** showed seasonal inconsistencies requiring operational improvements.

### 📞 Public Satisfaction Gaps
* **311 Call Center Response Times** and **Constituent Experience Scores** indicated that citizen service responsiveness requires enhancement.

### 📆 Seasonal and Annual Trends
* 📚 **Library Usage:**  
  Increased significantly during December–January, suggesting weather-driven trends; otherwise remained stable (~1.75 score year-round).
* 🏫 **BPS Attendance:**  
  Consistent attendance throughout the year, with a minor decline towards late June, indicating seasonal impacts.

---

## 🧮 Annual Metrics Summary
An annual aggregation of monthly scores for each metric was performed, complemented by:

- **Trend Analysis:** Tracking metric fluctuations month-over-month.
- **Part-to-Whole Contribution:** Calculating each metric's percentage share of the overall daily score.

This holistic approach offered a clear understanding of the city’s operational strengths and weaknesses across time.

---

## 🚀 Areas for Improvement
The analysis identified targeted improvements to optimize service delivery and citizen satisfaction:

- Enhance **streetlight maintenance** and **EMS response times** to meet service benchmarks.
- Improve **311 call center responsiveness** and **overall constituent satisfaction** through better communication strategies and faster issue resolution.

---

## 🛠️ Skills and Tools Utilized
- **Skills:** Data Cleaning, Trend Analysis, Metric Classification, Insight Extraction
- **Tools:** Python (Pandas, NumPy, Matplotlib), Excel
