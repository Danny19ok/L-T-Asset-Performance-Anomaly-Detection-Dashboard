# 📊 Performance & Anomaly Detection Dashboard

## Overview

This dashboard was built during an internship at **L&T Construction** to monitor **asset performance** and identify **anomalies** in operational data. It helps track key metrics and detect unusual patterns for better decision-making.

## Tools Used

- Power BI  
- Excel (for data preprocessing)  
- DAX (for calculations and logic)

## Features

- Summary KPIs (Work Done, Fuel Used, Anomaly Count, etc.)
- Anomaly Detection based on custom logic
- Interactive filters for date, asset code, and more
- Visualizations using cards, tables, slicers

## Anomaly Logic

Anomalies are detected based on conditions like:

- Fuel usage is negative  
- Work done is reported, but fuel usage is missing  
- IOT and operation data mismatch

DAX functions used include `CALCULATE`, `FILTER`, `RELATED`, etc.

## How to Use

1. Clone or download this repository  
2. Open the `.pbix` file in Power BI  
3. Load the sample data or connect your own  
4. Use filters and visuals to explore anomalies

