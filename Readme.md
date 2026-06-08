# 📊 Data Jobs Dashboard
 
A comprehensive Power BI dashboard project analyzing data job market trends, salary distributions, job platform postings, and geographic availability across multiple job titles.
 
 ![Dashboard Data Page] (/images/DataJobDashboard.png)
 
## 📌 Overview
 
This project provides an interactive, multi-page Power BI dashboard that enables users to explore the data job market at both a high level and a granular, job-title-specific level. It covers salary benchmarks, job availability, remote work options, health insurance offerings, and monthly posting trends throughout 2024.

---
 
## 📁 Dashboard Pages
 
### 1. 🌐 Data Jobs Dashboard (Main Overview)
The landing page provides a bird's-eye view of the entire data job market.
 
| KPI | Value |
|-----|-------|
| Total Job Count | 478,895K |
| Salary Rating | ⭐⭐⭐☆☆ |
| Overall Annual Salary | $113.25K |
| Overall Hourly Salary | $47.620 |
 
**Visuals included:**
- **Data Job Trends Per Month** – A table showing job demand, hourly & annual earnings, and monthly sparkline trends by job title
- **Job Trending Across 2024** – A line chart tracking monthly job postings (Jan–Dec 2024)
- **Median Hourly & Annual Salary by Job Title** – A combo bar/line chart comparing salary medians
- **Hour vs. Year Salary Relationship** – A scatter plot mapping hourly vs. annual salary medians per job title
---
 
### 2. 🔍 Job Title Detail Page (e.g., Business Analyst)
A drill-through page that surfaces in-depth metrics for a selected job title.
 
**Visuals included:**
- **Hourly & Annual Salary Gauges** – Dial charts showing average salary vs. the overall range
- **Degree Requirement Breakdown** – Donut chart (67.48% do not require a degree)
- **Remote Job Availability** – Donut chart (13.15% remote)
- **Health Insurance Availability** – Donut chart (13.15% with health insurance)
- **Job Platform Posting** – Horizontal bar chart ranking platforms (LinkedIn, BeBee, Indeed, ZipRecruiter, Jooble, GrabJobs, Recrui…, Indeed)
- **Type of Modality** – Bar chart showing employment type distribution (Full-time, Contractor, Internship, etc.)
- **Job Title Locations Map** – Esri-powered bubble map showing geographic job concentration worldwide
---
 
## 📊 Key Metrics at a Glance
 
| Job Title | Job Demand | Hourly Avg | Annual Avg |
|-----------|-----------|------------|------------|
| Senior Data Scientist | 21,731K | $49,895 | $155,500 |
| Senior Data Engineer | 30,608K | $58,680 | $146,500 |
| Data Engineer | 128,994K | $59,160 | $126,268 |
| Data Scientist | 97,664K | $43,035 | $125,000 |
| Senior Data Analyst | 15,347K | $39,450 | $107,310 |
| Data (Analyst/Other) | 112,866K | $32,500 | $90,000 |
| **Total** | **407,210K** | **$47,620** | **$113,750** |
 
---
 
## 🛠 Tools & Technologies
 
| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development and data modeling |
| **Esri / ArcGIS Maps** | Geographic job location visualization |
| **DAX** | Calculated measures (salary averages, medians, KPIs) |
| **Power Query (M)** | Data transformation and cleaning |

---
 
## 📂 Data Sources
 
The dataset includes job postings scraped/aggregated from multiple platforms:
- LinkedIn
- BeBee
- Indeed
- ZipRecruiter
- Jooble
- GrabJobs
- Recrui…
> Data covers job postings from **January 2024 to December 2024**.
 
---
 
## 🔎 Filters & Slicers
 
- **Job Title Slicer** – Filter all visuals by a specific job title (or view All)
- **Clear All Slicers** button – Resets all active filters at once
- **Drill-through** – Click any job title to navigate to its dedicated detail page
---
 
## 📈 Key Insights
 
1. **Data Engineers** have the highest job demand (~129K postings) with strong hourly pay ($59.16/hr).
2. **Machine Learning Engineers** and **Senior Data Scientists** command the highest annual salaries ($150K+).
3. Job postings peaked in **February 2024** (55,336 postings) and hit their lowest in **November 2024** (13,779 postings).
4. Only **13.15%** of Business Analyst roles offer remote work; **86.85%** require on-site presence.
5. The majority (**67.48%**) of Business Analyst postings do **not** require a formal degree.
6. **LinkedIn** dominates job platform postings, followed by BeBee and Indeed.
---
 
## 🚀 Getting Started
 
1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Refresh the data source if prompted (update credentials or file path as needed).
4. Use the **Job Title slicer** at the top to explore individual roles.
5. Click any row in the trend table to drill through to the job-title detail page.
---
 
## 📋 Requirements
 
- Power BI Desktop (latest version recommended)
- Internet connection for Esri map tiles (optional — map will render in offline mode with limited tiles)
---
 
## 📄 License
 
This project is for educational and portfolio purposes. Data sourced from publicly available job board aggregations.
 
---
 
## 🙋 Author
 
> Built as part of a data analytics portfolio project showcasing Power BI dashboard design, DAX modeling, and labor market analysis.