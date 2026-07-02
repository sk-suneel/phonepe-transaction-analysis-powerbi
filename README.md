# PhonePe Transaction Analysis Dashboard

An interactive Power BI dashboard analyzing PhonePe digital payment transactions — covering transaction volume, value, success rates, user demographics, and service-type trends.

## Overview

This project explores PhonePe transaction data to uncover patterns in payment behavior, user activity, and service performance. The dashboard is built entirely in Power BI, using Power Query for data transformation and DAX for calculated measures.

## Dashboard Preview

<img width="1111" height="622" alt="Screenshot" src="https://github.com/user-attachments/assets/286cfb68-8aee-4946-a97c-3d08fcbfdf0e" />


## Key Metrics (KPIs)

- **Total Transaction Value**
- **Total Transactions**
- **Success Rate**
- **Total Users**
- **Month-over-Month Transaction Growth (%)**
- **Month-over-Month Transaction Value Growth (%)**

## Visualizations Included

- **Transaction Value Trend** — stacked area chart of value over time
- **Transactions by Service** — bar chart comparing services
- **Transactions by Service Type** — column charts
- **Age Segment Distribution** — donut chart of users by age group
- **Weekday vs. Weekend Transactions** — donut chart
- **Top Users by Transaction Count** — column chart
- **Success Rate Trend** — line chart over time
- **User Growth by Year** — line chart based on join date
- **Filters/Slicers** — by Month and Payment Status

## Data Model

The report is built on the following tables:

| Table | Description |
|---|---|
| `All_Transactions` | Transaction-level records (service, service type, payment status, amount, etc.) |
| `All_Users` | User details (user ID, name, age segment, join date) |
| `Date_Table` | Date dimension table for time-based analysis (month, weekend flag, etc.) |
| `Measures` | Centralized table holding all DAX measures used across the report |

## Tools & Skills Used

- **Power BI Desktop** — report building and data modeling
- **Power Query (M)** — data cleaning and transformation
- **DAX** — KPI and time-intelligence measures (MOM% growth, success rate, etc.)
- **Data Modeling** — star-schema relationships between fact and dimension tables

## Repository Structure

```
├── PhonePe_Analysis.pbix   # Power BI report file
└── README.md               # Project documentation
```

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/sk-suneel/<repo-name>.git
   ```
2. Open `PhonePe_Analysis.pbix` in **Power BI Desktop** (free download from Microsoft).
3. If prompted, update the data source connection to point to your local dataset.
4. Explore the dashboard using the Month and Payment Status filters.

## Key Insights

- Identified states with the highest digital transaction volume.
- Compared quarterly transaction growth.
- Analyzed transaction categories.
- Visualized payment trends over time.
- Created an interactive dashboard for business reporting.

## Author

**Suneel Kumar**
- LinkedIn: [linkedin.com/in/suneel-kumar-42a586257](https://linkedin.com/in/suneel-kumar-42a586257)
- GitHub: [github.com/sk-suneel](https://github.com/sk-suneel)

---
If you found this project useful, consider giving it a star!
