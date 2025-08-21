# 📊 Maxitel Call Center Performance Dashboards  

This project showcases the use of Power BI to transform raw call center data into fully interactive dashboards that drive insights across operational, team, and executive levels.  

---

## 1. MaxiTel Call Center Insights Dashboard (2022–2024)  

An executive-level dashboard providing a **comprehensive, big-picture summary** of the call center's performance.  

**Year-over-Year KPIs**  
- Large, prominent KPI cards at the top of the report use DAX to compare current metrics to the previous year, providing a high-level performance summary.
  
**Call Type Breakdown**  
- 📊 Donut chart showing distribution of calls by type.  
- Example: *General Inquiry = 48.06% of all calls*.  

**Historical Trends**  
Two separate combination charts track key metrics over time:
- **AHT vs. Abandoned %** – Handling speed vs. lost calls.  
- **AHT vs. Actual/Forecast %** – Performance against business goals.  

**Dynamic Storytelling (DAX)**  
A dynamic text box, powered by DAX measures, provides a narrative summary of the data. For example, it automatically calls out:
- Automatically generated insights, e.g.:  
  - “01-Jul-23 had the highest AHT: 654 seconds.”  
  - “03-Jul-23 had the highest Abandoned Calls %: 7.2%.”  

---

## 2. Daily Contact Center Performance  

This dashboard is a high-impact operational tool for frontline managers, offering a detailed daily view of call center activity. It provides clear insights into call volumes, service levels, and performance trends for effective real-time decision-making.  

**Calls Answered by Interval**  
- A detailed table breaks down the number of calls answered by specific time intervals throughout the day.  
- Helps managers quickly identify peak hours and make immediate staffing adjustments.  

**KPIs & Trends** 
Two combination charts are used to track key performance indicators:
- 📈 **AHT vs. Actual/Forecast %** – Compares Average Handle Time (AHT) against forecasted service levels.  
- 📉 **AHT vs. Abandoned %** – Highlights the relationship between handling time and call abandonment.  

Together, these visuals help managers monitor performance against targets in real time and balance efficiency with service quality.  

**Totals Table**  
- A formatted summary consolidates the day’s key metrics.  
- Example: On **15-Feb-2023**, the dashboard confirms **451 calls answered** with an **AHT of 644.80 seconds**, offering a reliable daily snapshot of overall performance.  

---

## 3. Agent Performance & Quality Dashboard  

This dashboard is an interactive performance management tool for team leads, enabling analysis at both the team and individual agent levels. It helps supervisors track efficiency, service quality, and customer satisfaction over time.

**KPI Cards**  
- Four KPI cards highlight critical measures: AHT, Surveys Completed, NPS, and CSAT, each benchmarked against the same period in the previous year using DAX time intelligence (SAMEPERIODLASTYEAR).  
- Benchmarked against the same period in the previous year using **SAMEPERIODLASTYEAR (DAX)**.  

**Performance Trends**  
- Four line charts for **AHT, CSAT, NPS, Transfer %**.  
- Helps link performance shifts to coaching, process changes, or external factors.  

**Interactive Filters**  
- Slicers for Agent ID, Department, and Month.  
- Year/Month hierarchy slicer for fast drill-down.  

---

## 4.⚙️ Power BI Toolkit:
Built entirely on Microsoft Power BI, leveraging:

Power Query – for data cleansing and transformation.

DAX – for custom measures and time intelligence functions.

Conditional Formatting – for instant visual cues.

Interactive Features – including slicers, bookmarks, and dynamic text for a smooth user experience.---

## 5. Screenshots / Demos
Show what the dashboard looks like. 
(https://github.com/sese334/Call-Center-Performance-Dashboard/blob/main/Snapshot%20of%20the%20Dahbaord.png
https://github.com/sese334/Call-Center-Performance-Dashboard/blob/main/Snapshot%20%202%20.png.png
https://github.com/sese334/Call-Center-Performance-Dashboard/blob/main/Snapshot%203.png.png)


---
