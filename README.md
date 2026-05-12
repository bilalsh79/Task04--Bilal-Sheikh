# Task04--Bilal-Sheikh
# Executive E-Commerce Performance Dashboard 📊

## Overview
This project features an interactive, single-page executive dashboard designed to translate raw e-commerce data into a compelling business narrative. Built as part of the **DecodeLabs Data Analytics** training (Project 4: Data Visualization), this dashboard shifts the focus from simple metrics reporting to strategic data storytelling. 

While top-line revenue appears strong ($1.26M), this dashboard was specifically engineered to highlight a critical business emergency: severe operational leakage, with over 41% of all orders resulting in cancellations or returns. 

![Dashboard Preview](Project%204/dashboard.png)
## The "So What?" (Core Business Insight)
The primary objective of this visualization is to guide executive action. The dashboard successfully communicates that while the company is highly effective at top-of-funnel marketing and capturing high-ticket sales (AOV: $1,054), post-purchase friction is heavily suppressing realized revenue. The data suggests that next quarter's priority should pivot from acquisition to investigating supply chain and product quality.

## Features & Visualizations
* **KPI Highlights:** Clean, immediate visibility into Total Revenue, Total Orders, and Average Order Value (AOV).
* **Revenue Trend Analysis:** A 12-month line chart tracking revenue velocity and seasonal peaks.
* **Portfolio Performance:** Horizontal bar charts breaking down revenue by product category and sales volume by unit.
* **The Action Item (Order Status):** A focused donut chart purposefully highlighting the 'Cancelled' and 'Returned' metrics to draw attention to operational leakage.
* **Marketing Attribution:** Bar charts analyzing revenue distribution across referral sources and coupon usage.

## Tech Stack
* **Structure & Styling:** HTML5, Custom CSS (using DM Sans and DM Serif Display for a clean, corporate aesthetic).
* **Data Visualization:** JavaScript & [Chart.js](https://www.chartjs.org/) for rendering lightweight, interactive, and responsive canvas-based charts.

## How to Run Locally
Since this is a client-side HTML file, you do not need a complex build environment to view it.

**Option 1: Direct Browser Viewing**
1. Clone this repository or download the files.
2. Double-click `ecommerce_executive_dashboard.html` to open it directly in your default web browser.

**Option 2: Live Server (Recommended for Editing)**
If you wish to modify the code and see real-time updates:
1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `ecommerce_executive_dashboard.html` and select **"Open with Live Server"**.

## Design Philosophy
This dashboard was designed adhering to strict data-ink ratio principles:
* **The Architect:** Purposeful selection of charts matching the specific business questions.
* **The Editor:** Eradication of chartjunk (removed unnecessary gridlines, borders, and complex legends).
* **The Storyteller:** Definitive, action-oriented structural layouts designed for a boardroom presentation.
