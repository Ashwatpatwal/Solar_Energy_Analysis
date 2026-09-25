# ☀️ Solar Energy Data Analysis & Reporting

**End-to-end analytics workflow using MySQL and Microsoft Power BI**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-yellow?style=for-the-badge)

---

## 📊 Overview

This project analyzes solar energy generation and performance data using **MySQL** as the backend database and **Power BI** for transformation, modeling, and visualization. The solar energy dataset was imported into MySQL, connected to Power BI, cleaned with Power Query, modeled for analysis, and turned into an interactive dashboard that surfaces trends and KPIs in solar energy performance.

The result is a complete pipeline — from raw CSV data to a polished, decision-ready report — showcasing a practical, business-oriented approach to sustainable energy analytics.

---

## 🎯 Objectives

- Store and manage solar energy data in a relational MySQL database
- Integrate MySQL with Power BI as a live data source
- Clean and transform data using Power Query
- Build a data model suited for analysis
- Develop DAX measures and KPIs
- Design an interactive, insight-driven Power BI dashboard
- Surface trends and patterns in solar energy generation and performance

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Database | MySQL, SQL |
| BI & Reporting | Power BI Desktop |
| Data Prep | Power Query |
| Calculations | DAX |
| Modeling | Data Modeling / Star Schema principles |
| Visualization | Power BI interactive charts & KPI cards |

---

## 🔄 Workflow

```
Solar Energy CSV Dataset
        ↓
      MySQL  →  Database creation & data import
        ↓
    Power BI  →  Connect to MySQL source
        ↓
   Power Query  →  Clean & transform data
        ↓
   Data Modeling  →  Structure relationships
        ↓
    DAX / KPIs  →  Build measures
        ↓
 Interactive Dashboard  →  Visualize
        ↓
   Data Insights  →  Sustainable energy trends
```

---

## 🗄️ MySQL Database Setup

A dedicated database was created to house the solar energy dataset:

```sql
CREATE DATABASE test1;
USE test1;
```

The solar energy CSV was then imported into this database and set as the live data source for the Power BI report.

---

## 📈 Power BI Dashboard

The dashboard delivers an interactive view into solar energy generation, performance, and trends — built for quick exploration and business-style insight generation.

### Dashboard Screenshots

*(Add screenshots here — see `dashboard/` folder)*

| | |
|---|---|
| ![Screenshot 1](dashboard/Screenshot%202026-09-25%20212738.png) | ![Screenshot 2](dashboard/Screenshot%202026-09-25%20212753.png) |
| ![Screenshot 3](dashboard/Screenshot%202026-09-25%20212804.png) | ![Screenshot 4](dashboard/Screenshot%202026-09-25%20212816.png) |
| ![Screenshot 5](dashboard/Screenshot%202026-09-25%20212826.png) | |

---

## 🔍 Key Analysis Areas

- Solar energy generation volumes
- Performance metrics over time
- Trend and pattern identification
- KPI tracking
- Comparative analysis across periods/segments
- Data-driven sustainability insights

---

## 💡 Skills Demonstrated

`MySQL` `SQL` `Data Import & Integration` `Power BI` `Power Query` `DAX`
`Data Transformation` `Data Modeling` `KPI Development` `Data Visualization`
`Interactive Reporting` `Business Analytics`

---

## 📂 Repository Structure

```
Solar_energy_Data_Analysis_PowerBI/
│
├── dashboard/
│   ├── Screenshot 2026-09-25 212738.png
│   ├── Screenshot 2026-09-25 212753.png
│   ├── Screenshot 2026-09-25 212804.png
│   ├── Screenshot 2026-09-25 212816.png
│   ├── Screenshot 2026-09-25 212826.png
│   └── SOLAR_ENERGY_POWERBI.pbix
│
├── Data/
│   └── Dataset files
│
├── SQL/
│   └── database_setup.sql
│
└── README.md
```

---

## 🚀 Getting Started

1. Clone or download this repository
2. Run the SQL script in `SQL/database_setup.sql` to create the MySQL database
3. Import the solar energy CSV dataset into MySQL
4. Open `SOLAR_ENERGY_POWERBI.pbix` in **Power BI Desktop**
5. Update the MySQL connection details if needed
6. Refresh the data to pull the latest values
7. Explore the interactive dashboard

---

## 📌 Outcome

This project demonstrates how to combine a relational database with a modern BI tool to turn raw solar energy data into an interactive, insight-rich report — covering the full pipeline of data integration, transformation, modeling, DAX, visualization, and business-oriented analysis.

---

### 🌱 Why Solar Energy Analytics?

As renewable energy adoption grows, being able to monitor generation trends, spot performance issues, and communicate insights clearly is increasingly valuable — this project is a hands-on demonstration of exactly that skill set.
