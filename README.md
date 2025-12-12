# English Premier League Performance Analysis (2018–2023)

All rights reserved to Team Hanen Hosam.
This is our graduation project from the DEPI program.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Proposed Solution](#proposed-solution)
- [Objectives](#objectives)
- [Data Sources](#data-sources)
- [Methodology / Approach](#methodology--approach)
- [Tools & Technologies](#tools--technologies)
- [Results / Findings](#results--findings)
- [Challenges & Solutions](#challenges--solutions)
- [Conclusion & Recommendations](#conclusion--recommendations)
---

## Project Overview
This project analyzes English Premier League (EPL) performance data from 2018 to 2023. The goal is to extract meaningful KPIs, trends, and insights to support decision-making for coaches, analysts, and sporting directors. The project focuses on both player and team performance, comparing offensive and defensive metrics across seasons.

The final deliverables include **interactive dashboards** and **comprehensive reports** summarizing key findings and actionable recommendations.

---

## Business Problem
The team’s management lacks a clear understanding of how player performance has evolved over the seasons. They need data-driven insights to support decisions regarding player transfers, training focus, and performance evaluation.

---

## Proposed Solution
- Compare player performance season by season  
- Identify top scorers, key playmakers, and consistent defenders  
- Track performance trends across positions and clubs  
- Deliver interactive dashboards summarizing key insights for decision-makers

---

## Objectives
- Collect and clean Premier League player and team data (2018–2023)  
- Build season-by-season comparisons to identify performance changes  
- Extract and visualize top scorers, assist leaders, and best defensive teams  
- Develop interactive dashboards for club-level and player-level performance  
- Generate actionable insights for decision-makers

---

## Data Sources
The data was collected from **[FBref](https://fbref.com/)** using a **Python-based web scraping pipeline**.

**Data Collection Details:**
- Player and team stats for six EPL seasons (2018–2023)  
- Offensive, defensive, and match-level metrics  
- Tools used: Python (Requests, BeautifulSoup, Pandas) for scraping and preprocessing

**Data Storage:**
- CSV files for raw and cleaned datasets  
- Excel for manual review  
- SQL for structured querying

---

## Methodology / Approach
1. **Data Collection** – Scraping and storing EPL data from FBref  
2. **Data Cleaning & Preprocessing** – Handling missing values, duplicates, and formatting inconsistencies  
3. **Exploratory Data Analysis (EDA)** – Identifying patterns, anomalies, and trends  
4. **Business Question Mapping** – Linking KPIs and metrics to management objectives  
5. **KPI Development** – Calculating goals, assists, clean sheets, player rankings, and team metrics  
6. **Trend & Performance Analysis** – Comparing performance season-to-season and across positions/clubs  
7. **Dashboard Design** – Building interactive visualizations with Power BI / Tableau  
8. **Reporting & Documentation** – Summarizing findings, recommendations, and methodology

---

## Tools & Technologies
- **Python:** Requests, BeautifulSoup, Pandas, NumPy  
- **Excel / CSV / SQL:** Data storage and management  
- **Power BI / Tableau:** Dashboards and interactive visualizations  
- **Matplotlib / Seaborn:** Exploratory data analysis  
- **DAX:** KPI calculations in Power BI  
- **GitHub:** Version control and collaboration

---

## Results / Findings
- Identified top scorers, assist leaders, and consistent defenders across seasons  
- Tracked team performance trends and ranked clubs based on offensive and defensive KPIs  
- Positional analysis revealed key patterns among forwards, midfielders, and defenders  
- Dashboards provide an intuitive interface for season-over-season performance comparisons

---

## Challenges & Solutions
- **Inconsistent data formats:** Standardized column names and merged datasets  
- **Missing or incomplete data:** Cleaned and validated datasets  
- **Large multi-season data:** Optimized storage and automated processing pipelines  
- **Dashboard usability:** Designed intuitive, fast-loading visualizations

---

## Conclusion & Recommendations
- Provides actionable insights for player recruitment, training, and performance evaluation  
- Recommended continuous monitoring and annual updates of dashboards  
- Suggested integrating advanced metrics (e.g., xG, expected assists) for deeper analysis
