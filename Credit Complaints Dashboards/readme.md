# 💳 Credit Card Complaints Dashboard (Tableau)

An interactive Tableau dashboard analyzing **86,893** consumer credit card complaints from **2015 to 2021**. This project provides actionable insights into complaint volume trends, geographical distribution, common customer pain points, and company resolution efficiency.

---

## 📊 Executive Summary & Key KPIs

* **Total Complaints:** `86,893`
* **Rolling 12 Months Complaints:** `20,202`
* **Timely Responses:** `85,934` (`98.90%` closed rate)
* **In Progress Complaints:** `329`
* **Average Monthly Volume:** `1,337` complaints/month (Peaking at `2,175` in 2020)

---

## 📈 Dashboard Visualizations & Insights

### 1. KPI Summary Cards (Top Banner)
* **Total Complaints:** Displays overall complaint volume alongside a sparkline trend and a Rolling 12-Month metric (`20,202`).
* **Timely Response:** Tracks resolution SLA performance, highlighting a **`98.90%`** timely closure rate via a custom progress bar.
* **In Progress:** Monitors active, unresolved cases (`329`) with an area trend chart.

### 2. Monthly Trend Analysis
* An area chart illustrating complaint fluctuations between **2015 and 2021** against a benchmark reference line (`Avg: 1,337`).
* **Key Insight:** Complaint volumes remained relatively stable between 2016 and 2018 before surging significantly in 2019–2020, reaching an all-time monthly high of **2,175** complaints.

### 3. State-Wise Complaints (Density Heatmap)
* A dark-mode geospatial density map powered by Mapbox/OpenStreetMap identifying regional complaint hotspots across the United States.
* **Key Insight:** High concentrations of complaints originate from densely populated regions, particularly along the **Northeast corridor (NY/NJ/PA)**, **California**, **Florida**, and **Texas**.

### 4. Top Customer Issues
* A horizontal bar chart ranking the most frequent complaint categories:
  1. **Billing disputes:** `14,688`
  2. **Other:** `9,049`
  3. **Identity theft / Fraud / Embezzlement:** `8,244`
  4. **Closing/Cancelling account:** `6,230`
  5. **APR or interest rate:** `5,426`
  6. **Late fee:** `3,550`
  7. **Customer service / Customer relations:** `3,424`
  8. **Delinquent account:** `3,135`
  9. **Credit determination:** `2,976`
  10. **Advertising and marketing:** `2,861`

### 5. Company Response Breakdown
* A tabular summary detailing how complaints were resolved:
  * **Closed with explanation:** `51,873` (`59.92%`)
  * **Closed with monetary relief:** `17,942` (`20.73%`)
  * **Closed with non-monetary relief:** `9,215` (`10.65%`)
  * **Closed without relief:** `4,246` (`4.91%`)
  * **Closed with relief:** `2,500` (`2.89%`)
  * **Closed:** `649` (`0.75%`)
  * **Untimely response:** `139` (`0.16%`)

### 6. Daily Complaints Calendar Heatmap
* A calendar-style heatmap tracking daily complaint intensity across specific months (e.g., *January 2019*), helping identify weekday vs. weekend submission patterns.

### 7. Submission Channels *(Supporting Worksheet)*
* Tracks how consumers submit their complaints:
  * **Web:** `68.92%`
  * **Referral:** `16.58%`
  * **Phone:** `7.48%`
  * **Postal mail:** `5.96%`
  * **Fax:** `1.00%`
  * **Email:** `0.05%`

---

## 🛠️ Tools & Techniques Used
* **Tool:** Tableau Desktop / Tableau Public
* **Key Features Implemented:**
  * Custom KPI Cards with Sparklines & Progress Bars (`AVG(1)` placeholder technique)
  * Dynamic Parameter/Filter Controls (*Trend Period selector*)
  * Reference Lines for Monthly Averages
  * Mapbox Geospatial Density Mapping
  * Calendar Heatmap Date Calculations

---

## 🚀 How to Use
1. Clone this repository or download the `.twbx` (Tableau Packaged Workbook) file.
2. Open the workbook using **Tableau Desktop** or **Tableau Public**.
3. Use the interactive filters (such as the **Trend** dropdown or clicking on specific states/issues) to dynamically filter the dashboard views.

---

## 📷 Dashboard Preview
> *Tip: Upload a screenshot of your full dashboard (`Page 15` of your PDF) to your repository (e.g., `assets/dashboard_preview.png`) and link it below:*

```markdown
![Credit Card Complaints Dashboard](assets/dashboard_preview.png)
```
