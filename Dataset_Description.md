# 📂 Dataset Description

## Overview

The EV Charging Station Analytics Dashboard is built using multiple related datasets that represent different aspects of EV charging operations. These datasets were imported into Power BI, cleaned using Power Query, and connected through relationships to support interactive reporting and business analysis.

---

# Dataset Tables

## 1. Charging Stations

**Purpose**

Stores information about EV charging station locations and station details.

**Typical Columns**

- Station ID
- Station Name
- City
- State
- Latitude
- Longitude
- Installation Date
- Station Status

---

## 2. Chargers

**Purpose**

Contains information about charger types and charger specifications installed at each station.

**Typical Columns**

- Charger ID
- Charger Type
- Power Rating
- Connector Type
- Station ID

---

## 3. Charging Sessions

**Purpose**

Acts as the primary transactional dataset containing every charging session performed by customers.

**Typical Columns**

- Session ID
- Customer ID
- Charger ID
- Station ID
- Start Time
- End Time
- Energy Consumed (kWh)
- Revenue
- Session Duration

---

## 4. Customers

**Purpose**

Contains customer information used for customer-level analysis.

**Typical Columns**

- Customer ID
- Customer Name
- Vehicle Type
- Registration Date
- Membership Type

---

## 5. Calendar

**Purpose**

Provides date intelligence for time-based analysis and trend reporting.

**Typical Columns**

- Date
- Day
- Month
- Quarter
- Year
- Month Name
- Week Number

---

# Data Relationships

The project uses a relational data model where tables are connected using one-to-many relationships.

The relationships enable:

- Customer-wise analysis
- Station-wise reporting
- Charger performance analysis
- Revenue analysis
- Time-based reporting

---

# Data Cleaning & Transformation

The following preprocessing steps were performed using Power Query:

- Removed duplicate records
- Corrected data types
- Renamed columns for consistency
- Removed unnecessary columns
- Checked for missing values
- Created calculated columns where required
- Applied data validation rules

---

# Dataset Summary

| Dataset | Description |
|----------|-------------|
| Charging Stations | Station information and location details |
| Chargers | Charger specifications and types |
| Charging Sessions | Transactional charging session data |
| Customers | Customer information |
| Calendar | Date dimension for reporting |

---

# Data Quality

The datasets were validated before dashboard development to ensure:

- Accurate relationships
- Consistent data types
- No duplicate records
- Reliable KPI calculations

---

# Business Value

The integrated datasets provide a comprehensive view of EV charging operations and enable users to analyze:

- Revenue generation
- Energy consumption
- Charging trends
- Station utilization
- Customer activity
- Vehicle usage
- Geographic performance

These datasets form the foundation of the interactive Power BI dashboard and support effective business decision-making.