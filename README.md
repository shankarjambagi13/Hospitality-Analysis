# 🏨 Hospitality Analytics Dashboard

A comprehensive **Power BI dashboard** built to analyze hotel performance metrics across multiple properties and cities. This project demonstrates end-to-end data analytics capabilities — from data modeling to interactive business intelligence reporting — tailored for the hospitality industry.

---

## 📊 Dashboard Preview

![Hospitality Analytics Dashboard](./Screenshot_2026-04-26_010126.png)

---

## 🎯 Project Overview

This dashboard provides a 360° view of hotel chain performance, enabling stakeholders to monitor occupancy, revenue, cancellations, and booking trends in real time. It is designed to support data-driven decisions in hotel management and revenue optimization.

---

## 📌 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| **Total Bookings** | 135K |
| **Total Revenue** | ₹1,709M |
| **Occupancy Rate** | 57.87% |
| **RevPAR** (Revenue Per Available Room) | ₹7.35K |
| **Cancellation Rate** | 24.83% |
| **ADR** (Average Daily Rate) | ₹12.70K |

---

## 📈 Visualizations Included

### 1. Revenue by Hotel (Horizontal Bar Chart)
Compares total revenue across 7 properties in the Shodwe hotel chain:
- **Shodwe Exotica** — ₹320M (top performer)
- **Shodwe Palace** — ₹304M
- **Shodwe City** — ₹286M
- **Shodwe Blu** — ₹261M
- **Shodwe Bay** — ₹260M
- **Shodwe Grands** — ₹212M
- **Shodwe Seasons** — ₹66M

### 2. Booking Status Breakdown (Bar Chart)
Tracks the distribution of reservation outcomes:
- **Checked Out:** 94K bookings
- **Cancelled:** 33K bookings
- **No Show:** 7K bookings

### 3. Revenue by Room Class (Donut Chart)
Reveals revenue contribution across four room tiers:
- **Elite** — ₹560M
- **Presidential** — ₹377M
- **Premium** — ₹462M
- **Standard** — ₹310M

### 4. Revenue by Week (Line Chart)
Tracks weekly revenue trends across 14 weeks (W19–W32), highlighting a significant revenue drop in week W32 (₹21M), useful for identifying seasonality and operational anomalies.

### 5. Total Revenue by City (Bar Chart)
Breaks down performance across 4 major Indian cities:
- **Mumbai** — ₹669M (highest)
- **Bangalore** — ₹420M
- **Hyderabad** — ₹325M
- **Delhi** — ₹295M

---

## 🔍 Filters & Interactivity

The dashboard includes dynamic slicers for granular analysis:
- **City** — Filter by specific city
- **Room Class** — Standard, Premium, Elite, Presidential
- **Day Type** — Weekday vs. Weekend
- **Date** — Custom date range selection

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **DAX** | Custom measures and KPI calculations |
| **Power Query (M)** | Data transformation and cleaning |
| **Excel / CSV** | Source data format |

---

## 💡 Key Insights

- **Mumbai** generates the highest revenue, contributing ~39% of total chain revenue
- **Elite rooms** are the top revenue-generating class, suggesting strong demand for premium accommodation
- The **cancellation rate of 24.83%** presents a significant revenue leakage opportunity
- Weekly revenue is fairly consistent (~₹115M–₹140M) until a sharp dip in **Week 32**, indicating potential data gaps or a strong seasonal effect
- **Shodwe Seasons** significantly underperforms relative to other properties — a candidate for targeted improvement strategies

---

## 📂 Project Structure

```
hospitality-analytics-dashboard/
│
├── README.md
├── HospitalityDashboard.pbix        # Power BI report file
├── data/
│   └── hospitality_data.csv         # Source dataset
└── screenshots/
    └── dashboard_preview.png        # Dashboard screenshot
```

---

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/hospitality-analytics-dashboard.git
   ```
2. Open `HospitalityDashboard.pbix` in **Power BI Desktop**
3. Refresh the data source if needed (connect to your local CSV path)
4. Use the slicers on the left panel to explore different views

---

## 🧠 Skills Demonstrated

- Business Intelligence (BI) Dashboard Design
- Data Modeling and Relationship Management in Power BI
- DAX Measures (RevPAR, ADR, Occupancy Rate, Cancellation Rate)
- Data Cleaning & Transformation with Power Query
- KPI tracking and storytelling through data visualization
- Hospitality domain knowledge (RevPAR, ADR, booking lifecycle)

