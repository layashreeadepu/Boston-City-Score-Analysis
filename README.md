# Computation and Visualization (IE 6600)  
**Assignment 1**  
**Layashree Adepu**  
**NUID: 002201120**  

**Submission Date:** 10-15-2024  

---

## 🔍 Data Cleaning and Preprocessing

To ensure data accuracy and reliability, I undertook comprehensive cleaning and preprocessing steps:

- **🧹 Null Value Removal:** I eliminated all null values in the "day score" column to avoid skewing the analysis with incomplete data. This ensures that the total number of incidents precisely reflects actual occurrences.
- **🔎 Data Filtering:** Rows missing key temporal data such as day, week, month, and quarter scores were filtered out.
- **❌ Duplicate Removal:** Any duplicate entries were removed to avoid inflating the incident counts and ensure consistency in reporting.

These steps were crucial for ensuring the integrity of the dataset, enabling accurate trend identification and reliable insights.

---

## 📊 Metric Classification

The metrics analyzed in this project are categorized into four key groups:

### 1. **🛡️ Crime and Safety Metrics**
   - **🔪 Stabbings (Trend)**  
   - **🔫 Shootings (Trend)**  
   - **🕵️‍♂️ Homicides (Trend)**  

These metrics provide insights into safety and security patterns across different time frames, helping identify high-risk periods and areas.

### 2. **⚙️ Operational Efficiency Metrics**

This category assesses how well the city delivers essential services. The following metrics were evaluated:

- **🚑 EMS (Emergency Medical Services) Response Time**
- **🚒 BFD (Boston Fire Department) Response Time**
- **💡 Streetlight On-Time Percentage**
- **📋 On-Time Permit Reviews**
- **🚮 Trash Pickup Schedule Adherence**
- **🚰 Water Service Delivery Time**
- **❄️ Snow Removal Efficiency**
- **🚦 Traffic Signal Repair Time**
- **🛠️ Road Pothole Repair Time**
  
These metrics collectively reflect the operational capacity of the city to respond to issues and maintain service levels.

### 3. **📞 City Services Satisfaction Surveys**
   - **☎️ 311 Call Center Performance**  
   - **💬 Constituent Experience Surveys**  

These surveys measure public satisfaction with city services, offering insights into areas where improvement may be needed based on direct feedback from citizens.

### 4. **🏫 Service Delivery Metrics**
   - **👩‍🏫 BPS (Boston Public Schools) Attendance Rates**
   - **📚 Library Usage Trends**

These metrics track service usage patterns, reflecting public engagement and service availability.

---

## 📈 Key Insights from Data Analysis

### **⏰ Incident Trends by Time of Day**
- **🌅 Morning Peak:** The data shows over 3,000 incidents occurring at **7 AM**, likely due to morning rush hour activity. 
- **🏢 Mid-Day Stability:** From **10 AM to 5 PM**, the number of incidents remains stable, reflecting a relatively quiet period during standard working hours.
- **🌆 Evening Surge:** A noticeable spike occurs at **6 PM**, coinciding with post-work and evening commutes, followed by a sharp decrease after **8 PM**.
- **🌙 Late Night Drop:** By **2-3 AM**, incidents fall to minimal levels, as expected in late-night hours.

### **⚠️ Performance Gaps in Operational Efficiency**
Several **operational efficiency** metrics underperformed against historical benchmarks:
- **💡 Streetlight On-Time Percentage** and **🚑 EMS Response Time** fell below targets, indicating potential inefficiencies in emergency and infrastructure services.
- **🚮 Trash Pickup Schedule Adherence** and **❄️ Snow Removal Efficiency** also showed variability, suggesting areas for process improvements, especially in seasonal services.

### **📞 Satisfaction Surveys**
- **☎️ 311 Call Center Performance** showed lagging response times, and **💬 constituent experience surveys** indicated that further enhancements are needed in customer service.

---

## 📆 Annual and Seasonal Trends

### **📚 Library Usage:**
- A significant increase in library usage was observed in **December** and **January**, possibly driven by colder weather, with many patrons seeking indoor reading environments.
- Year-round, library usage remained stable, with a score consistently around **1.75**, reflecting steady engagement.

### **🏫 BPS Attendance:**
- The **BPS Attendance Day Score Line Chart (2023-2024)** reveals consistent school attendance patterns, with a concerning dip towards the end of **June**, suggesting potential seasonal effects on student presence.

---

## 🧮 Annual Summary of Metrics

I calculated the **yearly sum of monthly scores** for each metric to provide a holistic view of performance across time. For **part-to-whole analysis**, I performed trend analysis for each metric throughout the year and calculated the **percentage contribution** of each metric to the overall daily total score.

---

## 📊 Areas for Improvement

While daily scores across most metrics showed consistent patterns, certain areas, especially those related to **operational efficiency**, require attention:
- **💡 Streetlight On-Time Percentage** and **🚑 EMS Response Time** need significant improvements to meet target benchmarks.
- **📞 311 Call Center Response** and **💬 Constituent Experience Surveys** reveal that satisfaction with city services is falling short, necessitating better engagement strategies and quicker response times.

---

This analysis sheds light on critical operational trends, highlights key areas for improvement, and presents a detailed examination of city service efficiency.
