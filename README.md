# 🌍 Global Disaster Response Analysis Dashboard (2018–2024)

An interactive Power BI dashboard that analyzes global disaster events between 2018 and 2024, evaluating disaster impact, response performance, and aid distribution to help governments, NGOs, and policy makers make faster, data-driven emergency management decisions.

---

## 📌 Background

Natural and man-made disasters pose a critical challenge to governments and humanitarian organizations worldwide. Effective disaster response depends not only on preparedness but also on timely aid delivery, resource management, and operational efficiency. Analyzing historical disaster data reveals patterns in occurrence, severity, and response effectiveness — helping decision-makers improve risk mitigation and emergency strategies.

## 🎯 Business Problem

Organizations handling disaster response currently lack a unified visual system to evaluate:

- Which countries are most affected by disasters
- Which disaster types cause the highest damage and casualties
- How response time affects recovery duration
- Whether higher aid amounts improve efficiency
- Where emergency operations are underperforming

Without a centralized dashboard, stakeholders struggle to identify high-risk regions, assess response efficiency, monitor trends over time, allocate resources effectively, and improve emergency planning.

## 🎯 Objective

Develop an interactive Power BI dashboard to analyze global disaster events (2018–2024) and provide insight into:

- Disaster frequency and trends by year and region
- Impact analysis using casualties and economic loss
- Performance evaluation based on response time and efficiency score
- Aid distribution analysis
- Relationship between disaster severity and recovery duration
- Identification of high-risk areas and inefficient response zones

---

## 🗂️ Dataset

**File:** `global_disaster_response_2018_2024.csv`
**Size:** ~50,000 disaster records
**Time Period:** 2018–2024

| Column | Description |
|---|---|
| `date` | Date of the disaster event |
| `country` | Country affected |
| `disaster_type` | Type of disaster (earthquake, flood, hurricane, wildfire, drought, tornado, landslide, storm surge, extreme heat, volcanic eruption) |
| `severity_index` | Numeric severity rating of the event |
| `casualties` | Number of casualties reported |
| `economic_loss_usd` | Estimated economic loss in USD |
| `response_time_hours` | Time taken to initiate emergency response (hours) |
| `aid_amount_usd` | Total aid distributed in USD |
| `response_efficiency_score` | Score representing response effectiveness |
| `recovery_days` | Number of days taken for full recovery |
| `latitude` / `longitude` | Geolocation of the disaster event |

---

## 📊 Dashboard Structure

The Power BI file contains **3 report pages**:

### 1. Global Disaster Response Analysis (Overview)
- KPI cards: Total Disasters, Total Casualties, Total Economic Loss, Avg Response Time, Avg Recovery Days, Countries Affected
- Country and disaster-type slicers
- Total disasters by year (trend)
- Total casualties by disaster type
- Total economic loss vs. casualties (scatter)

### 2. Disaster Impact & Overview
- Economic loss share by disaster type (pie chart)
- Aid amount distributed by country (bar chart)
- Detailed year-by-country breakdown table: casualties, economic loss, recovery days, response efficiency score

### 3. Response Performance
- Response efficiency score count by disaster type
- Average response time by year (trend)
- Response time vs. recovery duration (scatter, by disaster type)
- Top 10 deadliest disaster types by casualties

---

## 📈 Key KPIs Tracked

- Total number of disasters
- Countries affected
- Total casualties
- Total economic loss
- Average response time
- Total aid distributed
- Average recovery duration
- Average response efficiency score
- Deadliest disaster types
- Costliest disaster types

## 💡 Sample Insights from the Data (2018–2024)

- **~50,000** disasters recorded across **20 countries**
- **~5 million** total casualties
- **$253.43 billion** in total economic loss
- Average response time of **~12.18 hours** and average recovery time of **~49.68 days**
- Disaster frequency peaked around **2021** before declining through 2024
- Economic loss is fairly evenly distributed across disaster types (each ~9–11% of total loss), with earthquakes and hurricanes among the costliest
- Brazil, Germany, and the United States rank among the highest for combined casualties and economic loss

---

## 🎯 Target Users

- Government disaster management agencies
- NGOs and humanitarian organizations
- Policy makers
- Risk assessment teams
- Insurance companies
- Researchers and analysts

## 🚀 Expected Outcomes

The dashboard enables decision-makers to:

- Detect disaster-prone regions
- Understand which disasters cause the most damage
- Evaluate emergency response performance
- Identify delayed response patterns
- Optimize aid allocation
- Improve disaster preparedness strategies
- Forecast future risks through historical trends

---

## 🛠️ Tools Used

- **Power BI** — dashboard design, DAX measures, and interactive visuals
- **CSV (50,000 rows)** — source dataset

## 📁 Repository Structure

```
├── README.md
├── global_disaster_response_2018_2024.csv     # Source dataset
├── Global_Disaster_Dashboards.pbix            # Power BI dashboard file
└── Global_Disaster_Dashboards.pdf             # Exported dashboard preview
```

## ▶️ How to Use

1. Clone or download this repository.
2. Open `Global_Disaster_Dashboards.pbix` in **Power BI Desktop**.
3. Use the **Year** slicer (top-right of each page) to filter by a specific year or view all years.
4. Use the **Country** and **Disaster Type** filters on the Overview page to drill into specific segments.
5. Hover over charts for tooltips with exact figures; click chart elements to cross-filter other visuals on the same page.

---
