
# 📊 Customer Complaint Analysis Dashboard (Tableau)

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview
This interactive **Customer Complaint Dashboard** built in Tableau provides a comprehensive analysis of **72,431 customer complaints** received across various financial product groups between **2011 and 2020**. The dashboard is designed to help stakeholders identify high-volume complaint areas, track historical trends, analyze submission channels, and pinpoint geographical hotspots across the United States.

*(Tip: Replace the link below with a screenshot of your final dashboard stored in your repository, e.g., `./assets/dashboard_preview.png`)*
> 🖼️ **[View Dashboard Preview / Tableau Public Link](#)**

---

## 🎯 Key Performance Indicators (KPIs)
At the top of the dashboard, dynamic KPI cards and progress bars break down the **72,431 Total Complaints** into five core product groups:

| Product Group | Total Complaints | % of Total |
| :--- | :---: | :---: |
| **Others** | 19,721 | 27.23% |
| **Credit Card** | 18,910 | 26.11% |
| **Checking / Services** | 12,192 | 16.83% |
| **Mortgage** | 11,918 | 16.45% |
| **Bank Services** | 9,690 | 13.38% |

---

## 🛠️ Interactive Features & Parameters
To enhance user exploration and self-service analytics, the dashboard incorporates dynamic Tableau parameters:
* **`Select Prod..` (Product Group Parameter):** Dynamically highlights and filters the selected product category (e.g., *Credit Card*, *Mortgage*, *Bank Services*, *Checking/Services*, *Others*) across the stacked bar chart, request type breakdown, and yearly area trend.
* **`Select Map` (View Switcher Parameter):** Allows users to seamlessly toggle between a traditional **Filled Geographic Map** and a clean **US Tile Map** for state-by-state comparisons without geographic size bias.

---

## 📈 Dashboard Visualizations & Insights

### 1. Complaints per Year (Stacked Bar Chart)
* **Description:** Displays the annual percentage distribution of total complaints from **2011 to 2020**, comparing the selected product group against the rest of the dataset.
* **Key Insight:** Overall complaint volume peaked in **2018 (14.60%)** and **2019 (12.87%)**. For the *Credit Card* segment specifically, complaint share remained steady between ~4.3% and ~5.5% from 2012 to 2016 before tapering off in 2017.

### 2. State-wise Complaints (Geographic & Tile Maps)
* **Description:** Visualizes the geographic concentration of complaints across all US states and DC using color intensity and exact complaint counts.
* **Key Insight:** Complaint volume is heavily concentrated in high-population states, led by:
  1. **California (CA):** 2,786 complaints
  2. **New York (NY):** 1,716 complaints
  3. **Florida (FL):** 1,602 complaints
  4. **Texas (TX):** 1,369 complaints
  *(Lowest volume observed in Wyoming with 12 complaints).*

### 3. Request Type / Submission Channel (Horizontal Bar Chart)
* **Description:** Breaks down how customers submit their complaints for the selected product category.
* **Key Insight (Credit Card Segment):** **Web** is overwhelmingly the primary channel with **11,545 complaints (~61%)**, followed by **Referral** (4,088), **Phone** (1,592), **Postal Mail** (1,435), **Fax** (247), and **Email** (3).

### 4. Product Year Trend (Area Chart)
* **Description:** Tracks the absolute volume trajectory of the selected product group over time.
* **Key Insight (Credit Card Segment):** Complaints surged from **295 in 2011** to **3,711 in 2012**, hitting an all-time high of **3,977 in 2014** before declining sharply to **1,150 in 2017**.

---

## 📂 Repository Structure
```text
├── Customer Complaints Dashboard.pdf   # Exported PDF views of dashboard states & sheets
├── Customer_Complaints.twbx            # Tableau Packaged Workbook (if uploaded)
└── README.md                           # Project documentation
```

---

## 🚀 How to Use
1. Clone this repository or download the `.twbx` Tableau workbook.
2. Open the file using **Tableau Desktop** or **Tableau Public**.
3. Use the **Select Prod..** dropdown in the top header to isolate specific financial products.
4. Use the **Select Map** dropdown to switch between the **Map** view and **Tile** chart view.

---

## 💡 Future Enhancements
* Add **Company Response** and **Timely Response Rate** KPIs to measure customer service efficiency.
* Include a **Sub-Issue / Complaint Narrative** drill-down tooltip for deeper root-cause analysis.
* Fix minor title typos on the canvas (e.g., *"Complaints per ywar"* $\rightarrow$ *"Complaints per Year"* and *"Title Chart"* $\rightarrow$ *"Tile Chart"*).
