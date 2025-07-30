# Building Footprint Analysis

This project visualizes the geospatial building footprint data to uncover patterns in structure type, elevation, and roof design. It combines Python for data cleaning, AWS Redshift for SQL querying, and Tableau for interactive dashboards.

---

## What I Did

- Cleaned raw footprint data using Python (`datacleaning.py`)
- Stored cleaned data in Amazon S3 and loaded it into Redshift using SQL
- Wrote SQL queries to explore footprint type, elevation, and extrusion
- Connected Tableau to Redshift for live data visualization
- Built a dashboard with filters, KPIs, and charts to analyze structure patterns

---

## Tech Stack

- Python (Pandas, JSON)
- AWS (S3, Redshift, IAM)
- SQL (Redshift)
- Tableau

---

## Dashboard Preview

[![Dashboard](buildingfootprints%20dashboard.png)](https://public.tableau.com/app/profile/shristi.tuladhar6499/viz/BuildingFootprintsAnalysis/BuildingFootprintAnalysis)

> Click the image above to view the live dashboard on Tableau Public.

File: `Building Footprints Dashboards.twbx`  
Data: `buildingfootprints.csv` (cleaned) from `building footprints dataset.csv`

---

## Key Insights

- Flat roofs are the most common design
- Hip roofs tend to appear at higher elevations
- Majority of footprint types are labeled as "Structure"
- Extrusion values vary depending on roof and footprint combination

---

## Files Included

1. `building footprints dataset.csv` - Raw dataset (original source)
2. `datacleaning.py` - Python script for data cleaning
3. `buildingfootprints.csv` - Cleaned dataset for analysis
4. `Building Footprints Dashboards.twbx` - Tableau dashboard (open with Tableau Public)
5. `buildingfootprints dashboard.png` - Static image preview of the dashboard
6. `buildingfootprints documentation.docx` - Full project setup, SQL, AWS steps, and notes

---

