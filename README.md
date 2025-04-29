# Website Performance Analysis Dashboard

##  Project Overview

This project presents a comprehensive Website Performance Analysis Dashboard designed to help a digital agency understand and address user behavior challenges on their client websites. The goal was to uncover why users were leaving the sites quickly and not converting, using data-driven insights.

---

## Problem Statement

The digital agency faced the following issues:
- High bounce rates across several landing pages
- Short session durations, especially on mobile devices
- Lack of clarity on how users interacted with the websites
- Difficulty identifying which pages or devices were underperforming

These problems hindered user engagement and reduced overall conversion rates.

---

## Solution Strategy

To tackle the above challenges, a structured data analysis approach was implemented:

1. **Data Collection**  
   Aggregated user behavior and performance metrics from various data sources such as Google Analytics and web server logs.

2. **Data Cleaning & Processing**  
   Utilized Python with Pandas to clean, filter, and standardize session and device-level data.

3. **Data Integration**  
   Combined multiple data sources using SQL queries to create a unified dataset for analysis.

4. **Dashboard Development**  
   Created an interactive dashboard in Power BI to visualize key metrics including:
   - Bounce rates by device and page
   - Session duration trends
   - Top-performing and low-performing pages
   - Traffic sources and user flow

---

## Tools & Technologies Used

- **Python (Pandas)** – for data cleaning and transformation  
- **SQL** – for data integration and querying  
- **Power BI** – for data visualization and dashboard design  
- **Excel** – for supplementary analysis and validation  

---

## 📈 Project Impact

- Identified **low-performing pages** that were causing early exits
- Uncovered **device-specific performance issues**, especially on mobile
- Guided **content and design improvements**
- Resulted in:
  - **25% increase in session duration**
  - **Improved user retention**
  - **Better understanding of user flow and engagement**

---

##  Folder Structure

```text
website-performance-dashboard/
├── README.md
├── data/
│   ├── raw/           # Unprocessed original data
│   └── cleaned/       # Cleaned datasets after preprocessing
├── notebooks/         # Jupyter notebooks for data analysis
├── scripts/           # Python scripts for automation
├── sql/               # SQL scripts for data integration
├── dashboard/         # Power BI dashboard files (.pbix)
├── excel/             # Excel summaries or exported tables
├── images/            # Dashboard screenshots or visual assets
