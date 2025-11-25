# Excel-Project

# Stock Market Analytics & Interactive Excel Dashboard

*A Comprehensive Analytical Project (2020–2025)*

## Overview

This project presents a complete **stock market analytics workflow** built using Excel, focusing on daily historical data for five of India’s most influential banking companies.
It demonstrates the full lifecycle of analytics — **data cleaning, transformation, feature engineering, KPIs, pivot tables, and dashboard creation** — resulting in a fully interactive and insight-driven Excel dashboard.

The analysis covers the five major banks shown across the dataset (page 4–8) :

* **HDFC Bank**
* **ICICI Bank**
* **State Bank of India (SBI)**
* **Kotak Mahindra Bank**
* **Axis Bank**

The dashboard enables users to explore stock performance across a **five-year period (2020–2025)** through slicers, KPIs, and dynamic charts.

---

## Dataset Description

The dataset contains **daily historical OHLC data** for each bank:

* **Date**
* **Open, High, Low, Close Price**
* **Volume**
* **% Change**

Additional calculated fields were engineered :

* Daily Price Change
* Daily % Change
* High–Low Range & High–Low %
* Previous Close
* Daily Return %
* Volume % Change
* Month/Year (MMM-YYYY)

This enriched dataset supports deeper trend, volatility, and return analysis.

---

## Data Cleaning & Preparation

The project includes a detailed cleaning workflow (pages 11–14) :

* Standardized date formats
* Normalized volume values (e.g., M → millions)
* Converted percentages to numeric values
* Removed duplicates
* Sorted data chronologically
* Ensured numeric precision across OHLC and return metrics
* Handled missing values logically

Clean data serves as the foundation for accurate KPIs and dashboard insights.

---

## Feature Engineering

Several transformation fields were created to enhance analytical depth (pages 15–18) :

* **Daily Returns & % Change**
* **Volatility Metrics (High–Low % Range)**
* **Volume % Change**
* **Moving Averages (optional extension)**
* **Time-based grouping (Month/Year)**

These engineered features support trend detection, volatility tracking, and comparative analysis.

---

## KPIs & Pivot Table Metrics

Key performance indicators built using PivotTables (page 19–23) :

* **Highest Close Price**
* **Lowest Close Price**
* **Average Daily Return %**
* **Highest Volume Day**
* **Total Volume Traded**
* **Average Daily Volume**

These KPIs update dynamically based on user selections in the dashboard.

---

## Dashboard Visuals & Interactivity

As outlined in the report (page 20–24) , the dashboard integrates:

### Filters & Slicers:

* Stock
* Year
* Month
* Timeline
  These allow multi-level exploration: daily, monthly, yearly, or full range (2020–2025).

### Visual Components:

* Trendlines
* Volume-price correlations
* Volatility charts
* Monthly return patterns
* KPI panels
* Moving average comparisons

The dashboard mimics professional BI tools like Power BI or Tableau but built entirely in Excel.

---

## Insights Discovered

Based on the insights section :

### **1. Volume surges often indicate high-volatility days**

Strong correlation observed between high trading volume and sharp price movements.

### **2. Monthly returns reveal cyclical and seasonal patterns**

March and earnings-period months show noticeable volatility.

### **3. Negative return days cluster during macroeconomic uncertainty**

Events like RBI rate changes and geopolitical tensions show clear multi-day downturn patterns.

### **4. Price–volume correlations reflect strong sentiment reactions**

High volume accompanying extreme price changes signals event-driven market sentiment.

---

## Conclusion

The Stock Market Analytics Dashboard demonstrates how Excel can function as a **powerful financial analytics tool**, offering:

* End-to-end data processing
* Interactive BI-style dashboarding
* Multi-dimensional market insights
* Technical, temporal, and sentiment-driven analysis

It provides a comprehensive view of stock behavior across five major Indian banks, supporting data-driven financial decisions and insights into market dynamics (page 28) .

---
