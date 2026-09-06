# 🚕 Uber Trip Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-8A2BE2?style=flat)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## 01. 📌 Project Overview

The **Uber Trip Analysis** project is an interactive Power BI analytics solution built using **150,000 Uber trip records**.

The dashboard evaluates booking performance, revenue, vehicle performance, ride distance, cancellations, locations, and customer/driver ratings.

**Workflow:**

**Raw Data → Power Query → Data Modeling → DAX → Power BI Dashboard → Insights → Recommendations**

---

## 02. 🎯 Business Problem

The analysis is designed to understand Uber's operational performance and identify opportunities across booking conversion, revenue, vehicle types, cancellations, locations, distance, and customer experience.

### Key Business Questions

- How many bookings are completed vs lost?
- Which vehicle types contribute the most revenue?
- How does revenue change over time?
- Which pickup and drop-off locations are most active?
- How significant are customer and driver cancellations?
- What is the typical ride distance?
- How do customer and driver ratings compare?

---

## 03. 📂 Dataset

The dataset contains **150,000 Uber trip records and 19 attributes** covering:

- Booking status
- Customers
- Vehicle types
- Locations
- Customer cancellations
- Driver cancellations
- Incomplete rides
- Booking value
- Ride distance
- Customer ratings
- Driver ratings
- Payment methods

---

## 04. 🧹 Data Preparation

Power Query was used to prepare the raw Excel data for analysis.

### Key Activities

- Loaded the source dataset into Power BI
- Organized and prepared source fields
- Created a dedicated Calendar table
- Prepared supporting vehicle image data
- Organized DAX measures in a dedicated measures table

---

## 05. 🧩 Data Model

The model uses:

- **UBER** — main trip and booking data
- **Calendar** — date, month, and quarter analysis
- **IMG** — vehicle-type image data
- **_Measures** — organized DAX calculations

---

## 06. 🧮 DAX & Measures

DAX measures were developed for:

- Booking Count
- Completed Bookings
- Lost Bookings
- Average Distance
- Total Revenue
- Booking Status calculations
- Time-based analysis

Keeping measures in a dedicated `_Measures` table improves organization and maintainability of the Power BI model.

---

## 07. 📊 Dashboard

The dashboard includes:

- Completed bookings
- Lost bookings
- Total revenue
- Total distance
- Average distance
- Revenue by vehicle type
- Monthly booking trends
- Quarterly revenue
- Top pickup location
- Top drop-off location
- Customer ratings
- Driver ratings
- Booking-status analysis
- Vehicle-type selection

![Uber Trip Analysis Dashboard](images/uber_dashboard.png)

---

## 08. 📌 Dashboard Snapshot

| Metric | Value |
|---|---:|
| Completed Bookings | 93K |
| Lost Bookings | 57K |
| Revenue | $52M |
| Total Distance | 3M |
| Average Distance | 24.64 |
| Average Customer Rating | 4.40 |
| Average Driver Rating | 4.23 |

---

## 09. 💡 Key Insights

### 1. Booking Loss Is Significant

The dashboard shows approximately **93K completed bookings compared with 57K lost bookings**, highlighting a meaningful opportunity to understand and reduce booking losses.

### 2. Auto Leads Vehicle Revenue

**Auto generated approximately $13M**, making it the highest-revenue vehicle type in the dashboard.

### 3. Revenue Is Relatively Consistent Across Quarters

Quarterly revenue remains relatively consistent, with each quarter contributing around **$13M**.

### 4. Average Ride Distance

The average ride distance is approximately **24.64**, providing a benchmark for typical trip length.

### 5. Customer Ratings Are Slightly Higher

The average customer rating is **4.40**, compared with an average driver rating of **4.23**.

### 6. Location Performance Matters

The dashboard highlights the most active pickup and drop-off locations, helping identify areas with stronger ride demand.

---

## 10. 💼 Business Recommendations

### Reduce Booking Losses

With roughly **57K lost bookings**, the business should prioritize analysis of the underlying cancellation and loss reasons to identify the highest-impact operational drivers.

### Protect High-Performing Vehicle Segments

Auto contributes approximately **$13M** in revenue. The business could evaluate whether fleet availability, demand, or pricing patterns explain this stronger performance.

### Use Demand Hotspots for Resource Allocation

High-activity pickup and drop-off locations can be used to inform driver positioning and supply allocation strategies.

### Monitor Customer and Driver Experience

The difference between average customer and driver ratings can be monitored over time to identify emerging experience gaps and support targeted operational improvements.

> These recommendations are proposed actions based on the observed dashboard findings; they are not measured business outcomes.

---

## 11. 🧠 Skills Demonstrated

| Area | Skills |
|---|---|
| Data Preparation | Power Query, data organization, date preparation |
| Data Modeling | Calendar table, supporting tables, relationships |
| DAX | KPI measures, booking metrics, time-based calculations |
| Operational Analytics | Booking, revenue, vehicle, location analysis |
| Customer Analytics | Ratings and customer experience |
| Visualization | KPI cards, trends, comparisons, interactive filtering |
| Business Analysis | Operational findings and recommendations |

---

## 12. 📂 Project Files

```text
Uber-Trip-Analysis/
│
├── data/
│   └── uber.xlsx
│
├── Power BI/
│   └── Uber Dashboard.pbix
│
├── images/
│   ├── uber_dataset.png
│   ├── uber_data_model.png
│   ├── uber_home.png
│   └── uber_dashboard.png
│
└── README.md
```

---

## 13. ⚙️ How to Explore

1. Open the Power BI report using **Power BI Desktop**.
2. Update the Excel data source path if required.
3. Refresh the dataset.
4. Use the dashboard filters to explore booking, vehicle, location, and customer/driver performance.

---

## 14. 🎓 Key Takeaway

This project demonstrates how Power BI, Power Query, data modeling, and DAX can be combined to convert operational trip data into an interactive decision-support dashboard.

---

## 👨‍💻 Author

**Adithya Ruby**

Computer Science Graduate | Data Analytics
