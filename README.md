# Healthcare Patient Waiting List Analytics Dashboard

## Project Overview
This project presents an end-to-end **Power BI analytics solution** built to analyze and monitor **patient waiting lists** across healthcare services.  
The dashboard enables stakeholders to track current waiting list status, analyze historical trends, and perform granular analysis by specialty, age profile, and case type.

The solution follows a structured **business intelligence workflow**, covering data ingestion, transformation, modeling, KPI development, and dashboard design.

---

## Business Objectives
The dashboard was designed to address the following objectives:

- Track the **current status of patient waiting lists**
- Analyze **historical monthly trends** for inpatient and outpatient categories
- Perform **specialty-level and age-profile analysis**
- Compare performance across **case types and time bands**
- Enable interactive and intuitive exploration of healthcare waiting list data

---

## Dataset Description
- **Domain:** Healthcare
- **Data Type:** Publicly available patient waiting list data
- **Categories:**
  - Inpatient
  - Outpatient
- **Time Period:** 2018 – 2021
- **Granularity:** Monthly records by specialty, age profile, and time band

---

## Tools & Technologies
- **Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – KPI and dynamic measure development
- **Data Modeling** – Relationship management and analytical structure

---

## Data Preparation & Modeling
Key data preparation steps included:

- Importing multiple yearly files using the **Folder connector**
- Standardizing column names and formats
- Handling missing values and inconsistent categories
- Appending inpatient and outpatient datasets into a unified table
- Creating a **specialty mapping table** to group specialties into logical buckets
- Building relationships to support accurate filtering and analysis

The final model supports efficient slicing across time, specialty, age profile, and case type.

---

## Key Metrics & KPIs
The dashboard computes and analyzes the following metrics:

- **Total Waiting List Count**
- **Average Waiting List**
- **Median Waiting List**
- **Latest Month Waiting List**
- **Same Month Previous Year Comparison**
- **Trend Analysis (Month-over-Month)**

A dynamic toggle allows users to switch between **Average** and **Median** metrics to handle outliers effectively.

---

## Dashboard Structure

### 1. Summary View
Provides a high-level overview including:
- Current month vs previous year waiting list comparison
- Distribution by case type (Inpatient, Day Case, Outpatient)
- Age profile vs time band analysis
- Top 5 specialties by waiting list
- Monthly trend analysis by case type

### 2. Detailed View
Enables granular analysis with:
- Drill-down table using a matrix layout
- Filters for specialty, age profile, time band, and case type
- Enhanced visibility into detailed waiting list patterns

---

## Interactivity & UX Features
- Dynamic metric selection (Average / Median)
- Cross-filtering and controlled visual interactions
- Custom tooltips for contextual insights
- Navigation between summary and detailed views
- Clean, consistent layout designed for usability

---

## Key Insights Enabled
- Identification of high-impact specialties contributing to long wait times
- Understanding age group and time band distribution patterns
- Comparison of inpatient vs outpatient waiting trends
- Detection of historical performance shifts over time

---

## Project Outcomes
- Demonstrates an **industry-style Power BI development workflow**
- Showcases strong skills in **data modeling, DAX, and dashboard design**
- Emphasizes **business-oriented analytics and decision support**
- Suitable for **portfolio, internship, and entry-level data analyst roles**

---



---

## Author
**Prashant Gautam**  
Data Analytics & Business Intelligence Enthusiast  

---

## Disclaimer
This project was developed as a **hands-on analytics implementation** to practice real-world Power BI dashboard development and healthcare data analysis workflows.
