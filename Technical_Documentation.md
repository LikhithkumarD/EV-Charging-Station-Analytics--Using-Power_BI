# ⚙️ Technical Documentation

# EV Charging Station Analytics Dashboard

## Project Information

**Project Name:** EV Charging Station Analytics Dashboard

**Tool Used:** Microsoft Power BI Desktop

**Data Source:** Excel Dataset

**Domain:** Electric Vehicle (EV) Infrastructure Analytics

---

# Project Objective

The objective of this project is to build an interactive Business Intelligence dashboard that enables stakeholders to monitor EV charging station performance, customer activity, energy consumption, and revenue generation. The dashboard provides meaningful insights that support operational monitoring and business decision-making.

---

# Technical Architecture

The solution follows a standard Business Intelligence workflow:

Excel Dataset
        │
        ▼
Power Query
(Data Cleaning & Transformation)
        │
        ▼
Data Model
(Relationships)
        │
        ▼
DAX Measures
(Calculations)
        │
        ▼
Interactive Dashboard
        │
        ▼
Business Insights

---

# Data Source

The dashboard is developed using multiple related datasets representing different business entities.

Dataset Tables

• Charging Stations

• Charging Sessions

• Customers

• Chargers

• Calendar

Each table serves a specific analytical purpose and is connected using appropriate relationships within the data model.

---

# Data Preparation

Data transformation was performed using Power Query Editor.

The following activities were completed:

✔ Removed duplicate records

✔ Renamed columns

✔ Corrected data types

✔ Removed unnecessary columns

✔ Validated missing values

✔ Created calculated columns where required

✔ Optimized dataset for reporting

---

# Data Modeling

The project uses a relational data model consisting of multiple related tables connected through one-to-many relationships.

The model enables:

• Cross-table filtering

• Interactive reporting

• Accurate DAX calculations

• Efficient dashboard navigation

---

# DAX Implementation

The dashboard uses DAX measures to calculate dynamic business metrics.

Examples include:

• Total Revenue

• Total Energy Consumed

• Total Customers

• Total Charging Sessions

• Total Stations

• Total Chargers

Additional DAX functions used include:

• SUM()

• COUNT()

• DISTINCTCOUNT()

• CALCULATE()

• RELATED()

• DIVIDE()

• IF()

• DATEDIFF()

• ABS()

• SEARCH()

---

# Dashboard Design

The report was designed following Business Intelligence dashboard best practices.

Features include:

✔ KPI Cards

✔ Interactive Slicers

✔ Column Charts

✔ Line Charts

✔ Bar Charts

✔ Donut Charts

✔ Geographic Map Visualization

✔ Consistent Dark Theme

✔ Responsive Layout

---

# Performance Optimization

The following practices were considered during dashboard development:

• Removed unnecessary columns

• Applied appropriate data types

• Minimized duplicate data

• Used measures instead of calculated columns where appropriate

• Established efficient table relationships

• Organized report layout for improved readability

---

# Business Value

The dashboard provides valuable insights for decision-makers by enabling them to:

• Monitor charging station performance

• Analyze revenue trends

• Evaluate customer activity

• Measure energy consumption

• Compare city-wise performance

• Track charger utilization

• Support strategic planning

---

# Skills Demonstrated

This project demonstrates practical knowledge of:

• Power BI Desktop

• Power Query

• Data Cleaning

• Data Modeling

• DAX

• Data Visualization

• Business Intelligence

• Dashboard Design

• Analytical Thinking

• Problem Solving

---

# Future Enhancements

Potential improvements include:

• Row-Level Security (RLS)

• Drill-through Reports

• Report Tooltips

• Bookmark Navigation

• Power BI Service Deployment

• Scheduled Refresh

• Incremental Refresh

• Performance Analyzer Optimization

• Mobile Layout Design

---

# Conclusion

The EV Charging Station Analytics Dashboard demonstrates an end-to-end Business Intelligence solution, starting from raw data preparation through interactive dashboard development. By combining Power Query, relational data modeling, DAX calculations, and effective visualization techniques, the project delivers actionable insights that support informed business decisions and operational efficiency.