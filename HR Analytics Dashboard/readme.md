# 📊 HR Analytics Dashboard — Tableau

![Tableau](https://img.shields.io/badge/Tableau-Desktop%20%2F%20Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Domain-HR%20Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview

This repository contains an interactive **HR Analytics Dashboard** built in **Tableau**. The dashboard provides Human Resources teams and organizational leadership with actionable insights into workforce demographics, employee attrition trends, department-level turnover, and job satisfaction ratings.

> **Note:** The dashboard supports dynamic filtering by **Department** (`HR`, `R&D`, `Sales`), allowing stakeholders to drill down into specific segments of the organization.

---

## 🎯 Key Performance Indicators (KPIs)

At the top of the dashboard, high-level KPI cards summarize the current workforce snapshot (shown below for the **HR Department** filter view):

| KPI Metric | Value (HR Filter) | Description |
| :--- | :---: | :--- |
| **Employee Count** | `63` | Total number of employees in the selected segment |
| **Attrition Count** | `12` | Total number of employees who have left the organization |
| **Avg. Age** | `38` | Average age of employees in the selected segment |
| **Active Employees** | `51` | Total number of currently active employees (`Employee Count - Attrition Count`) |
| **Attrition Rate** | `19.05%` | Percentage of total employees who left (`Attrition Count / Employee Count`) |

---

## 📈 Dashboard Visualizations & Insights

The dashboard is structured into six core visual components:

1. **Attrition by Gender (Lollipop Chart)**
   * Compares total attrition across Male and Female employees.
   * *Insight (HR View):* Attrition is evenly split between **Female (`6`)** and **Male (`6`)** employees.

2. **Department-wise Attrition (Pie Chart with Interactive Filter)**
   * Displays the overall distribution of attrition across the three primary departments:
     * **R&D:** `133` (`56.12%`)
     * **Sales:** `92` (`38.82%`)
     * **HR:** `12` (`5.06%`)
   * Includes interactive checkboxes (`HR`, `R&D`, `Sales`) to dynamically update the dashboard.

3. **No. of Employees by Age Group (Histogram / Bar Chart)**
   * Visualizes employee headcount distribution across age bins (configurable **Bin Size**, set to `3`).
   * Highlights workforce concentration in the mid-career bracket (ages `33` to `42`), peaking at age `36` (`9` employees).

4. **Job Satisfaction Rating (Highlight Table / Heatmap)**
   * Cross-tabulates **Job Role** (`Human Resources`, `Manager`) against **Job Satisfaction Ratings** (`1` = Lowest to `4` = Highest) with grand totals.
   * Helps identify roles experiencing lower morale (e.g., `16` HR employees rated satisfaction at level `2`).

5. **Education Field-wise Attrition (Horizontal Bar Chart)**
   * Breaks down employee turnover by educational background (`Human Resources`, `Technical Degree`, `Medical`, `Life Sciences`, `Other`).
   * *Insight (HR View):* Employees with a **Human Resources** education background account for the highest attrition (`7`), followed by **Technical Degree** (`2`) and **Medical** (`2`).

6. **Attrition Rate by Gender for Different Age Groups (Donut Charts)**
   * Segments attrition counts and percentages across five standard age brackets (`Under 25`, `25–34`, `35–44`, `45–54`, `Over 55`) broken down by gender.
   * *Insight (HR View):* The **25–34** age group experiences the highest turnover (`8` total: `6` Female [`50.00%`] and `2` Male [`16.67%`]), while zero attrition occurs in employees aged `45` and above.

---

## 🛠️ Tools & Features Used

* **Tableau Desktop / Tableau Public**
* **Calculated Fields:** Attrition Rate (`%`), Active Employees, Dynamic Age Groupings
* **Parameters:** Dynamic Bin Size selector for Age Distribution
* **Visual Techniques:** KPI Cards, Lollipop Charts, Donut Charts, Highlight Tables, Interactive Action & Dimension Filters

---

## 🚀 How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. **Open in Tableau:**
   * Open the `.twbx` (Tableau Packaged Workbook) file using **Tableau Desktop** or the free **Tableau Public** desktop client.
3. **Explore:**
   * Use the **Department** filter checkboxes on the left panel to slice the KPIs and charts by `HR`, `R&D`, or `Sales`, or adjust the **Bin Size** parameter to inspect age distributions at different granularities.

---

## 🖼️ Dashboard Preview

*(Tip: Upload a screenshot of your dashboard to a folder like `assets/dashboard_preview.png` in your repo and update the link below)*

```markdown
![HR Analytics Dashboard Preview](assets/dashboard_preview.png)
```
