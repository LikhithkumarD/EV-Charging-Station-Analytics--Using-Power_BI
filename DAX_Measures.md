# 📊 DAX Measures Documentation

## Overview

DAX (Data Analysis Expressions) measures were created to calculate key business metrics used throughout the EV Charging Station Analytics Dashboard. These measures provide dynamic calculations that respond to report filters and slicers, enabling interactive analysis.

---

# Revenue Measures

## 1. Total Revenue

### Purpose

Calculates the total revenue generated from all charging sessions.

### Formula

```DAX
Total Revenue = SUM('Charging Sessions'[Revenue])
```

### Business Use

- Measures overall business revenue
- Used in KPI cards
- Supports revenue trend analysis

---

# Energy Measures

## 2. Total Energy Consumed

### Purpose

Calculates the total electricity consumed across all charging sessions.

### Formula

```DAX
Total Energy = SUM('Charging Sessions'[Energy Consumed])
```

### Business Use

- Tracks total energy usage
- Helps monitor charging demand
- Used in KPI cards

---

# Customer Measures

## 3. Total Customers

### Purpose

Counts the total number of unique customers.

### Formula

```DAX
Total Customers =
DISTINCTCOUNT(Customers[Customer ID])
```

### Business Use

- Measures customer base
- Supports customer growth analysis

---

# Charging Session Measures

## 4. Total Charging Sessions

### Purpose

Counts all charging sessions completed.

### Formula

```DAX
Total Sessions =
COUNT('Charging Sessions'[Session ID])
```

### Business Use

- Measures operational activity
- Indicates charging demand

---

# Charging Station Measures

## 5. Total Stations

### Purpose

Counts all charging stations.

### Formula

```DAX
Total Stations =
DISTINCTCOUNT('Charging Stations'[Station ID])
```

### Business Use

- Displays total available stations
- Used in KPI card

---

# Charger Measures

## 6. Total Chargers

### Purpose

Counts all installed chargers.

### Formula

```DAX
Total Chargers =
COUNT(Chargers[Charger ID])
```

### Business Use

- Indicates infrastructure capacity
- Used in dashboard KPI

---

# Time Intelligence

## Revenue by Day

### Purpose

Analyzes daily revenue trends.

### Business Use

- Detects seasonal patterns
- Identifies peak charging days

---

# City Analysis

## Revenue by City

### Purpose

Compares revenue generated across different cities.

### Business Use

- Identifies top-performing locations
- Supports expansion planning

---

# Vehicle Analysis

## Revenue by Vehicle Type

### Purpose

Analyzes revenue contribution by vehicle category.

### Business Use

- Understands customer preferences
- Supports marketing decisions

---

# Charger Performance

## Revenue by Charger Type

### Purpose

Compares charger performance.

### Business Use

- Determines most profitable charger types
- Assists infrastructure planning

---

# Dashboard KPIs

The following DAX measures are displayed as KPI cards:

- Total Revenue
- Total Energy Consumed
- Total Customers
- Total Charging Sessions
- Total Stations
- Total Chargers

---

# DAX Concepts Applied

This project demonstrates practical usage of:

- SUM()
- COUNT()
- DISTINCTCOUNT()
- CALCULATE()
- RELATED()
- DIVIDE()
- IF()
- DATEDIFF()
- ABS()
- SEARCH()
- FORMAT()
- Calendar Table
- Time Intelligence

---

# Business Benefits

The implemented DAX measures enable users to:

- Monitor operational performance
- Analyze customer activity
- Track revenue generation
- Measure charging demand
- Evaluate station performance
- Compare charger utilization
- Support business decision-making

---

# Conclusion

The DAX measures were designed to provide accurate, dynamic, and interactive business calculations that update automatically based on report filters and user selections. These measures form the analytical foundation of the EV Charging Station Analytics Dashboard.