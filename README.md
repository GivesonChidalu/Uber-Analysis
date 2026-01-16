# 🚖 Uber Trip Analysis Dashboard (Power BI)

## 📌 Project Overview
This project analyzes **Uber trip data** for the month of june 2024 using **Power BI** to uncover insights into **ride bookings, revenue performance, trip efficiency, time-based demand patterns, and location trends**.

The goal is to support **data-driven decision-making** for stakeholders by identifying operational patterns, customer behavior, and optimization opportunities in pricing, driver allocation, and service delivery.

---

## 📂 Dataset Description
This project uses a structured Uber trip dataset consisting of two primary tables:

### Trip Table
Contains detailed trip-level information such as:
- Pickup and drop-off timestamps  
- Passenger count  
- Trip distance  
- Fare amount  
- Surge fee  
- Vehicle type  
- Payment method  

### Location Table
A lookup table mapping:
- Pickup location IDs  
- Drop-off location IDs  
to their corresponding **locations and cities**.


## 🎯 Business Objectives
- Understand booking and revenue trends over time  
- Evaluate trip efficiency based on distance and duration  
- Identify peak demand periods by time and location  
- Analyze customer preferences across vehicle and payment types  
- Enable stakeholders to interactively explore insights using dynamic visuals  

---

## 📊 Key Performance Indicators (KPIs)
The dashboard tracks the following core metrics:

- **Total Bookings** – Total number of Uber trips booked  
- **Total Booking Value** – Total revenue generated  
- **Average Booking Value** – Revenue per booking  
- **Total Trip Distance** – Cumulative distance covered  
- **Average Trip Distance** – Average distance traveled per trip  
- **Average Trip Time** – Average trip duration  

---

## 📈 Dashboard Structure

### 🧩 Dashboard 1: Overview Analysis
This dashboard provides a high-level summary of Uber trip performance.

#### Insights Delivered
- Overall booking and revenue trends  
- Trip efficiency analysis (distance and duration)  
- Comparison of performance across time periods  

#### Visual Analysis
- Dynamic KPIs (Total Bookings, Revenue, Distance)  
- Bookings by **Payment Type** (Card, Cash, Wallet, etc.)  
- Bookings by **Trip Type** (Day vs Night)  

#### Advanced Power BI Features
- **Dynamic Measure Selector** (Disconnected Table)  
  - Total Bookings  
  - Total Booking Value  
  - Total Trip Distance  
- **Dynamic Titles** that change based on selected measure  
- **Interactive Slicers** (Date, City, etc.)  
- **Custom Tooltips** showing additional metrics  

---

#### 🚗 Vehicle Type Analysis
A detailed grid-style analysis to compare performance across vehicle categories.

#### Metrics by Vehicle Type
- Total Bookings  
- Total Booking Value  
- Average Booking Value  
- Total Trip Distance  

#### Enhancements
- Conditional formatting to highlight high/low performers  
- Sorting and filtering for deeper insights  

---

#### 📅 Total Bookings by Day
This analysis focuses on daily booking behavior.

#### Business Use Cases
- Identify peak and off-peak demand days  
- Detect booking fluctuations and trends  
- Support pricing and driver allocation strategies  
- Assess impact of external factors (events, holidays, weather)  

---

#### 📍 Location Analysis
Location-based insights help optimize ride distribution and demand forecasting.

#### Key Analyses
- **Most Frequent Pickup Locations**  
- **Most Frequent Drop-off Locations**  
  - Implemented using an **inactive relationship** activated in DAX  
- **Farthest Trip Analysis**  
- **Top 5 Booking Locations**  
- **Most Preferred Vehicle by Pickup Location**  
---
### KEY INSIGHTS FOR DASHBOARD 1
- Total bookings by day revealed that weekends had low bookings compared to other weekdays, this is expected since human movenment is low during weekends
- The vehicle type analysis revealed that UberX had the highest total bookings and total booking value
- For the location analysis, the top pickup location was penn station/madison sq west


---
### ⏱️ Dashboard 2: Time Analysis
This dashboard explores **time-based trip patterns** to improve operational efficiency.

#### Global Dynamic Measure
A single measure selector dynamically updates **all visuals**:
- Total Bookings  
- Total Booking Value  
- Total Trip Distance  

#### Visualizationsbook
- **Pickup Time (10-Minute Intervals)** – Area chart  
- **Bookings by Day Name** – Line chart  
- **Hour vs Day Heatmap**
  - Rows: Hours (0–23)  
  - Columns: Days (Mon–Sun)  
  - Values: Selected Dynamic Measure  

---

### 🔍 Dashboard 3: Details (Drill-Through Tab)
This dashboard allows in-depth data exploration.

#### Features
- Detailed grid table of trip-level records  
- Drill-through functionality from charts and heatmaps  
- **“View Full Data” bookmark** to toggle filtered vs full dataset  

---

## ⚙️ Additional Dashboard Enhancements
- **Data Details Bookmark** – Explains KPIs, tables, and data sources  
- **Clear Filters Button** – One-click slicer reset using bookmarks  
- **Download Raw Data Button** – Export data for offline analysis  

---

## 🛠️ Tools & Technologies
- Power BI  
- DAX (Measures, Disconnected Tables, Dynamic Calculations)  
- Data Modeling (Active & Inactive Relationships)  
- Interactive Dashboards & Bookmarks  

---

## 📌 INSIGHTS
- Identified peak demand periods across time and locations  
- Analyzed revenue and trip efficiency patterns  
- Highlighted customer preferences by vehicle and payment types  
- Delivered a business-ready Power BI dashboard  


---

## ✅ Why This Project Matters
This project demonstrates:
- Business-focused analytics thinking  
- Strong Power BI and DAX skills  
- Real-world dashboard design for stakeholders  
- End-to-end BI project execution  
