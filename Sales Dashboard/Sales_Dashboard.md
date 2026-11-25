# 📊 Sales Performance & Executive Overview Dashboard (Tableau)

An interactive **Sales Dashboard** built in Tableau to analyze Current Year (CY - 2022) vs. Prior Year (PY - 2021) business performance across key metrics, customer segments, geographic locations, and regional managers.

---

## 📌 Project Overview

This dashboard provides stakeholders and leadership with an executive-level view of sales health, profitability, and order volume. Designed with dynamic filtering and comparative sparklines, it enables users to quickly identify Year-over-Year (YoY) growth trends, seasonal peaks, underperforming states, and top-performing regions.

### 🔗 Live Dashboard & Preview
* **Tableau Public Link:** `[Insert your Tableau Public URL here]`
* **Dashboard Preview:**  
  ![Sales Dashboard Overview](./assets/dashboard_preview.png) *(Replace with the actual path to your screenshot)*

---

## 🎯 Key Performance Indicators (KPIs)

The top banner highlights primary business metrics comparing **2022 (CY)** against **2021 (PY)**, complete with monthly trend sparklines denoting minimum and maximum performance points:

| Metric | Current Year (2022) | YoY Growth | Monthly Min | Monthly Max |
| :--- | :---: | :---: | :---: | :---: |
| **Total Sales** | **$733K** | 📈 `+20.36%` | $20,301 | $118,448 |
| **Total Profit** | **$93K** | 📈 `+20.36%` | $933 | $14,752 |
| **Total Quantity** | **12K Units** | 📈 `+26.83%` | 363 | 1,840 |

---

## 📈 Dashboard Components & Insights

### 1. KPI Trend Overview (CY vs. PY Sparklines)
* **Visuals:** Dual-line sparklines comparing monthly performance for 2022 (Gold) vs. 2021 (Dark Grey).
* **Highlights:** Automatically flags the **Max Month** (Dark Blue dot) and **Min Month** (Light Blue dot) for Sales, Profit, and Quantity to spotlight seasonal highs and lows.

### 2. Geographic Distribution & State Benchmarking
* **Sales & Profit by State (Filled & Symbol Map):** Visualizes state-level sales volume (`$78` to `$146,388`) alongside profitability (`-$8,839` to `$29,366`), making it easy to spot high-revenue states experiencing negative profit margins.
* **States Above & Below U.S. Average:**
  * **Sales Benchmark:** Tracks the count of states performing above vs. below the national sales average (**17 Above** vs. **30 Below**).
  * **Profit Benchmark:** Tracks the count of states performing above vs. below the national profit average (**14 Above** vs. **33 Below**).

### 3. Monthly Sales by Customer Segment
* **Visuals:** Area charts segmented by **Consumer**, **Corporate**, and **Home Office** with average reference lines and peak month callouts:
  * **Consumer:** Peak monthly sales of **$50.23K** (Average: **$27.66K**).
  * **Corporate:** Peak monthly sales of **$44.64K** (Average: **$20.15K**).
  * **Home Office:** Peak monthly sales of **$29.71K** (Average: **$13.29K**).

### 4. Regional & Manager Performance
* **Total Sales by Location & Regional Manager:** Horizontal bar charts breaking down total revenue across U.S. regions and their respective leads:
  * **West** *(Sadie Pawthorne)*: **$250K**
  * **East** *(Chuck Magee)*: **$213K**
  * **Central** *(Roxanne Rodriguez)*: **$147K**
  * **South** *(Fred Suzuki)*: **$123K**

---

## 🎛️ Interactive Features & Filters

Users can dynamically slice and explore the data using global filters located at the top of the dashboard:
* **Category:** Filter across Product Categories (e.g., Furniture, Office Supplies, Technology).
* **Region:** Isolate metrics by Central, East, South, or West.
* **Ship Mode:** Analyze performance by shipping tier (e.g., Standard Class, Second Class, First Class, Same Day).

---

## 🛠️ Tools & Techniques Used

* **Visualization Tool:** Tableau Desktop / Tableau Public
* **Data Modeling & Calculations:**
  * YoY % Change Calculations (`(CY - PY) / PY`)
  * Dynamic Min/Max LOD (Level of Detail) expressions for sparkline markers
  * Conditional formatting & reference lines for national state averages
* **Dataset:** Superstore Sales Dataset (2021–2022)

---

## 📂 Repository Structure

```text
├── README.md                  # Project documentation
├── Sales_Dashboard.twbx       # Packaged Tableau Workbook
├── Sales Dashboard.pdf        # Exported PDF sheets & dashboard views
└── assets/
    └── dashboard_preview.png  # High-resolution screenshot of the main dashboard
```

---

## 🚀 How to Use

1. Clone this repository or download `Sales_Dashboard.twbx`.
2. Open the workbook using **Tableau Desktop** or **Tableau Reader** (free).
3. Use the top filter controls (**Category**, **Region**, **Ship Mode**) or click directly on states/regions to cross-filter the dashboard.

---

*If you found this dashboard helpful or insightful, feel free to ⭐ star this repository!*