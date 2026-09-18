# Blinkit-Sales-Analysis-Dashboard-Adv.Excel
📊 Blinkit Sales Analysis — End-To-End Excel Analytics Project Turning ~8,500 Raw Retail Records Into An Interactive Dashboard With Pivottables, SUMIFS, And Slicers. 🎯 Tracks $1.20M In Sales Across Categories, Outlets &amp; Locations To Surface Actionable Business Insights. 🛠️ Built With Excel • Pivottables • Data Visualization.


# 🛒 Blinkit Sales Performance Analysis — Interactive Excel Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-FF6F00?style=for-the-badge&logo=tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-4682B4?style=for-the-badge&logo=chartdotjs&logoColor=white)

---

## 📌 Executive Summary

This project delivers an **end-to-end sales performance intelligence dashboard** for **Blinkit** (India's leading quick-commerce platform), built entirely within **Microsoft Excel**. The project transforms raw multi-tier retail transaction data into actionable operational strategies to optimize inventory, identify key high-revenue demographics, and improve store-level efficiency across various outlet formats and city tiers.

By leveraging advanced Excel functionality—including **PivotTables, dynamic PivotCharts, advanced logical and lookup formulas, custom KPI card visual design, and linked interactive Slicers**—this project establishes a centralized operational view of sales, item performance, customer feedback, and regional revenue drivers.

---

## 📈 Executive Performance Snapshot (Key KPIs)

| Metric | Recorded Value | Strategic Significance |
| :--- | :--- | :--- |
| **Total Revenue (Sales)** | **\$1.20M** | High transaction volume driven by quick-commerce adoption across diverse outlet sizes. |
| **Average Sale per Item** | **\$141** | Consistent item basket size indicating optimal item pricing and bundling opportunities. |
| **Total Items Sold** | **8,523 units** | High SKU velocity requiring streamlined inventory forecasting and stock availability. |
| **Average Customer Rating** | **4.0 / 5.0** | Strong overall consumer satisfaction, with localized room for service enhancement. |

---

## 🖼️ Interactive Excel Dashboard View

The single-page interactive dashboard provides instant dynamic filtering by **Outlet Size**, **Outlet Location Tier**, **Fat Content**, and **Item Category**.

![Blinkit Interactive Excel Dashboard]<img width="1751" height="898" alt="Dashboard PNG Final" src="https://github.com/user-attachments/assets/e43c9e6e-6fc9-4b49-8710-9a1f42d7489e" />


---

## 🎯 Business Problem & Core Objectives

Quick-commerce businesses operate under tight delivery timelines and volatile localized demand. Blinkit faces key operational questions across its multi-format outlet network:

1. **Product Mix & Health Preferences:** How does consumer demand split between **Low Fat** and **Regular** products across different city tiers?
2. **Channel & Outlet Performance:** Which store format (Supermarket vs. Grocery Store) generates optimal sales density and throughput?
3. **Geographic Demographics:** How do Tier 1, Tier 2, and Tier 3 cities compare in total revenue contribution and average order value?
4. **Historical Maturity:** Does establishment age correlate directly with higher operational revenue and store efficiency?

---

## 🛠️ Technical Stack & Excel Toolkit Used

This end-to-end project was built **100% inside Microsoft Excel** using a disciplined data analytics pipeline:

```
┌─────────────────┐     ┌──────────────────────┐     ┌────────────────────────┐     ┌───────────────────────┐
│ Raw Data Clean  │ ──> │ Formulas & Logic     │ ──> │ PivotTables & Data     │ ──> │ Interactive Dashboard │
│ & Preprocessing │     │ (XLOOKUP, IF, SUMIFS)│     │ Modeling               │     │ (Slicers & Charts)    │
└─────────────────┘     └──────────────────────┘     └────────────────────────┘     └───────────────────────┘
```

* **Data Wrangling & Cleaning:** Standardized inconsistent category values (e.g., merging `LF`, `low fat` into `Low Fat` and `reg` into `Regular`), imputed missing weight records, and handled blank field values using standard data sanitization protocols.
* **Advanced Excel Formulas:**
  * `XLOOKUP` / `VLOOKUP` for dynamic record mapping and category classification.
  * `SUMIFS` / `COUNTIFS` / `AVERAGEIFS` for custom KPI aggregations and multi-condition summary cards.
  * `IF` & Nested Logical Statements for custom bucket creation (e.g., item pricing tiers, establishment age brackets).
  * `TEXT` functions for date parsing and time-series extraction.
* **Data Modeling & Analytics:** Built optimized **PivotTables** linked directly to raw data arrays to perform dynamic, slice-and-dice operations.
* **Data Visualization & UI/UX Design:**
  * Integrated linked **Slicers & Timeline Controls** connected across multiple PivotTables via Report Connections for unified filtering.
  * Custom visual hierarchy using visual KPI cards, dynamic **PivotCharts** (Bar, Line, Donut, Column), gridline management, and **Conditional Formatting** color scales.

---

## 📊 Deep-Dive Business Insights

### 1. Consumer Dietary Preference (Fat Content Distribution)
* **Low Fat Products:** Generate **\$776.32K (\~65%)** of total sales across **5,000+ units sold**.
* **Regular Fat Products:** Represent **\$425.36K (\~35%)** of total sales across **3,000+ units sold**.
* **Takeaway:** Quick-commerce consumers show a decisive lean toward health-conscious and dietary-friendly food options, making Low Fat items prime candidates for top-shelf placement and promotional priority.

### 2. Product Category Revenue Breakdown
The catalog spans multiple categories, with fresh produce and quick snacks dominating volume:
* **Top Revenue Drivers:**
  * **Fruits & Vegetables:** **\$178.1K**
  * **Snack Foods:** **\$175.4K**
  * **Household Items:** **\$135.9K**
  * **Frozen Foods:** **\$118.6K**
* **Takeaway:** Perishable items (*Fruits & Vegetables*) and impulse purchases (*Snack Foods*) account for nearly 30% of total company revenue, highlighting the critical need for ultra-efficient cold chain management and inventory reordering.

### 3. Geographic Outlet Demographics
* **Tier 3 Cities:** Lead all geographic tiers with **\$472.1K** in total revenue.
* **Tier 2 Cities:** Contribute **\$393.1K** in sales with steady basket sizes.
* **Tier 1 Cities:** Account for **\$336.4K** in revenue.
* **Takeaway:** Tier 3 markets represent the largest quick-commerce revenue footprint, disproving the assumption that quick-commerce success is restricted purely to Tier 1 metro regions.

### 4. Outlet Format & Establishment Trends
* **Supermarket Type 1:** Generates the lion's share of revenue at **\$787.5K**, serving as the operational backbone of Blinkit's fulfillment network.
* **Grocery Stores:** Generate **\$151.9K** in overall revenue, functioning primarily as localized micro-fulfillment hubs.
* **Maturity Peak:** Outlets established around **2018** reached optimal operational capacity, contributing peak historical revenue due to matured local delivery routes and strong customer retention.

---

## 💡 Strategic Business Recommendations

1. **Targeted Stocking by Region:** Prioritize supply chain availability for top categories (*Fruits & Vegetables* and *Snack Foods*) in **Tier 3 cities** to capitalize on high consumer demand.
2. **Health & Wellness Marketing:** Expand the **Low Fat** product lineup in high-performing store formats, as health-conscious items drive nearly two-thirds of overall revenue.
3. **Grocery Store Optimization:** Utilize smaller **Grocery Stores** primarily as localized micro-fulfillment hubs for high-frequency, small-basket orders to lower delivery turnaround times.
4. **Replenishment Strategy:** Implement auto-replenishment logic for outlets established post-2018 to mirror the supply chain efficiency achieved by mature 2018-era hubs.

---

## 📁 Repository Structure

```
├── 📂 Dataset/
│   └── Blinkit_Sales_Data.csv           # Raw transactional retail dataset
├── 📂 Dashboard/
│   └── Blinkit_Sales_Analysis.xlsx      # Master Interactive Excel Dashboard (.xlsx)
├── 📂 Assets/
│   └── dashboard.png                    # High-resolution dashboard screenshot
└── README.md                            # Comprehensive project documentation
```

---

## 👨‍💻 Author & Contact Information

**Aditya Vishwakarma**  
*Data & Business Intelligence Analyst*

* 💼 **LinkedIn:** [linkedin.com/in/analystaditya09](https://linkedin.com/in/analystaditya09)
* 📁 **GitHub:** [github.com/analystaditya09](https://github.com/analystaditya09)
* 📧 **Email:** [aditya.analyst09@gmail.com](mailto:aditya.analyst09@gmail.com)

---
*⭐ If you found this project insightful, feel free to star this repository!*
