# 📊 Executive Sales Dashboard

An interactive Power BI **Executive Sales Dashboard** designed to track revenue, gross profit, order volume, and product performance across European markets and sales channels.

## 🎯 Project Overview
This business intelligence solution transforms raw retail sales data into an executive-level overview. It enables leadership and sales teams to evaluate overall profitability, compare country-level revenue, analyze channel distribution, and filter performance across time periods and product lines.

### Key Performance Indicators (KPIs)
* **Total Revenue:** 645.22K
* **Total Gross Profit:** 296.38K
* **Gross Margin:** 0.46 (46%)
* **Total Quantity Sold:** 6,698 units
* **Total Orders:** 2,707 orders

---

## ✨ Dashboard Features & Visuals

### 1. Interactive Slicers (Top Bar)
* **Quarter:** Filter metrics by fiscal quarter.
* **Month Name:** Drill down into specific months.
* **Product Category:** Isolate performance by outdoor and fitness lines.
* **Country:** Analyze individual European regional markets.

### 2. Core Visualizations
* **Month-wise Revenue and Profit (Line Chart):** Tracks monthly revenue and gross profit trajectories side by side, sorted from highest-performing months (**June: 70K revenue / 32K profit**) to lowest (**February: 36K revenue / 16.6K profit**).
* **Top 5 Country by Revenue (Horizontal Bar Chart):** Highlights leading European markets—**United Kingdom (74K)**, **Germany (70K)**, **France (55K)**, **Italy (50K)**, and **Spain (47K)**.
* **Bottom 5 Country by Revenue (Horizontal Bar Chart):** Identifies lower-performing markets requiring growth strategies—**Belgium (26K)**, **Switzerland (25K)**, **Finland (24K)**, **Czechia (23K)**, and **Ireland (17K)**.
* **Sales Channel Revenue Comparison (Pie Chart):** Breaks down revenue share across **Online Store (40.34%)**, **Corporate (27.84%)**, **Retail Partners (17.43%)**, and **Marketplace (14.39%)**.
* **Product Category by Revenue (Donut Chart):** Displays revenue contribution across **Hiking (29%)**, **Camping (28%)**, **Travel (19%)**, **Cycling (16%)**, and **Fitness (9%)**.

---

## 💡 Key Business Insights
* **Strong Overall Profitability:** The business maintains a healthy **46% gross margin**, generating **296.38K** in gross profit from **645.22K** in revenue.
* **Top Market Concentration:** The **United Kingdom (74K)** and **Germany (70K)** lead all territories, generating more than four times the revenue of the lowest-performing market (**Ireland at 17K**).
* **Digital & B2B Dominance:** **Online Store (40.34%)** and **Corporate (27.84%)** channels together account for **68.18%** of total revenue.
* **Core Product Drivers:** **Hiking (29%)** and **Camping (28%)** represent over half (**57%**) of total category revenue, while **Fitness (9%)** has the smallest footprint.
* **Seasonal Peaks:** Summer months (**June at 70K** and **July at 66K**) deliver peak revenue, whereas winter months (**January at 39K** and **February at 36K**) experience the lowest sales volume.

---

## 🛠️ Tech Stack & Tools
* **BI & Visualization:** Microsoft Power BI Desktop
* **Data Modeling & Calculations:** DAX (Measures for Total Revenue, Total Gross Profit, Gross Margin, Total Quantity, and Total Orders)
* **Data Preparation:** Power Query (ETL, data cleaning, and type formatting)
* **Data Source:** Kaggle

---

## 📂 Repository Structure
```text
├── data/
│   └── [sales_data.csv]                  # Raw dataset used for the dashboard
├── dashboard/
│   └── Executive_Sales_Dashboard.pbix    # Power BI Desktop report file
├── assets/
│   └── executive-sales-dashboard.png     # Dashboard preview image
└── README.md                             # Project documentation
```

---

## 🚀 How to Use
1. **Clone the repository:**
   ```bash
   git clone https://github.com[your-username]/[your-repo-name].git
   cd [your-repo-name]
   ```
2. **Open the Power BI file:**
   * Launch **Microsoft Power BI Desktop**.
   * Open `dashboard/Executive_Sales_Dashboard.pbix`.
3. **Refresh the data (if needed):**
   * Go to **Home > Transform data > Data source settings**, point the file path to your local `data/` folder, and click **Refresh**.

---

## 📬 Contact
**Srushti Badukale**  
LinkedIn: (https://linkedin.com/in/srushti-badukale-15941720a) | GitHub: (https://github.com/srushtib08) | Email: srushtibadukaleworks@gmail.com
