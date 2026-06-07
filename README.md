# Power BI Sales Dashboard

## Overview

This project presents an interactive sales dashboard built with Power BI using the Superstore dataset.

The objective of this project was to explore, analyze and visualize sales performance through key performance indicators and interactive charts.

---

## Technologies Used

* Power BI
* DAX
* Python (Pandas)
* CSV dataset

---

## Dataset

Dataset used:

**ventes_clean.csv**

The dataset contains information about orders, customers, products, regions and sales.

Main variables used:

* `Order Date`
* `Region`
* `Segment`
* `Category`
* `Sub-Category`
* `Product Name`
* `Sales`

---

## Data Preparation

The dataset was cleaned and prepared using Python (Pandas).

The preparation process included:

* Handling missing values
* Data type conversion
* Dataset structuring
* Creation of additional time-related features (`month`, `year`, `month_year`)

These transformations facilitated the analysis and the construction of interactive visualizations in Power BI.

---

## Dashboard Content

The report consists of two pages:

### 1. Overview

#### Key Performance Indicators (KPIs)

* Total Sales
* Number of Orders
* Number of Products
* Average Basket Value

#### Visualizations

* Sales trend over time
* Sales by region
* Sales by category
* Sales distribution by customer segment

#### Interactive Filters

* Category
* Region
* Segment

---

### 2. Detailed Analysis

#### Visualizations

* Top 10 states by sales
* Top 10 products by sales
* Sales by category and segment
* Sales by sub-category

#### Interactive Filters

* Category
* Region
* Segment

---

## DAX Measures

Several measures were created to support the dashboard, including:

* Total Sales
* Number of Orders
* Number of Products
* Average Basket Value

---

## Dashboard Export

The complete Power BI report is available in:

* `dashboard/ventes_dashboards.pbix`

Dashboard screenshots are provided in the `images/` directory.

---

## Project Structure

```text
powerbi-sales-dashboard/
├── data/
│   └── ventes_clean.csv
├── dashboard/
│   └── ventes_dashboards.pbix
├── images/
│   ├── overview_page.png
│   └── detailed_analysis_page.png
└── README.md
```

---

## Learning Outcomes

Through this project, I practiced:

* Data cleaning and preparation with Pandas
* Exploratory data analysis
* KPI definition
* DAX measures creation
* Dashboard design with Power BI
* Interactive data visualization
* Business-oriented analysis
