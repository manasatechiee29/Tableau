# 📊 Data Science Salaries — Interactive Tableau Dashboard

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-Analytics-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An interactive Tableau dashboard analyzing global compensation trends, company demographics, employment structures, and role-specific salaries across the Data Science industry.

---

## 🔗 Live Dashboard
👉 **[View Interactive Dashboard on Tableau Public](#)** *(Replace `#` with your Tableau Public link)*

---

## 🖼️ Dashboard Preview
![Dashboard Overview](assets/dashboard_overview.png)
*(Tip: Save a screenshot of your full dashboard as `assets/dashboard_overview.png` in your repo to display it here)*

---

## 🎯 Project Overview
The goal of this project is to uncover how compensation in Data Science varies across experience levels, job titles, employment types, company sizes, and geographic locations. Using a clean, dark-themed analytical layout, the dashboard enables recruiters, job seekers, and hiring managers to benchmark salaries and explore workforce distribution.

---

## 🧩 Dashboard Components & Visualizations

The dashboard is structured into **7 core analytical views** with interactive filtering capabilities (such as filtering by **Company Location** and **Job Title**):

1. **Total Companies by Size & Location (Donut Chart)**
   - Breaks down the employer landscape by organization size:
     - **Medium:** `61.41%`
     - **Large:** `29.86%`
     - **Small:** `8.73%`
2. **Employment Type Distribution (Donut Chart)**
   - Highlights the overwhelming dominance of standard full-time roles:
     - **Full-Time:** `97.46%`
     - **Freelance:** `0.85%`
     - **Part-Time:** `0.56%`
     - **Contract:** `~1.13%`
3. **Experience Level Breakdown (Donut Chart)**
   - Illustrates workforce seniority distribution:
     - **Senior:** `61.41%`
     - **Intermediate:** `25.35%`
     - **Entry Level:** `8.73%`
     - **Expert:** `~4.51%`
4. **Top 10 Employee Residence (Horizontal Bar Chart)**
   - Ranks countries by employee headcount, showing a heavy concentration in the **United States (US)** (~330+ employees), followed by **India (IN)**, **Brazil (BR)**, **Greece (GR)**, **France (FR)**, **Spain (ES)**, **Germany (DE)**, and **Canada (CA)**.
5. **Average Salary in USD by Experience Level & Employment Type (Grouped Bar Chart)**
   - Compares compensation across combinations of seniority (`Entry Level`, `Intermediate`, `Senior`, `Expert`) and work arrangement (`Contract`, `Freelance`, `Full-Time`, `Part-Time`), with averages reaching over **$400K+** in specialized senior/contract segments.
6. **Average Salary by Country (Choropleth Map)**
   - Interactive Mapbox geographic visualization displaying global average salaries in USD, ranging from **$4,000** up to **$157,500+**.
7. **Average Salary by Job Title & Experience Level (Detailed Matrix / Table)**
   - Granular breakdown of average USD compensation across 45+ Data Science, ML, AI, and Analytics roles segmented by seniority.

---

## 💡 Key Insights & Takeaways

- **Workforce Composition:** Over **61%** of the surveyed roles are at the **Senior** level, and **61.41%** of hiring organizations are **Medium-sized** companies.
- **Employment Stability:** Nearly **97.5%** of Data Science positions are **Full-Time**, making freelance and contract roles a small niche of the overall market.
- **Geographic Concentration:** The **US** dominates both employee residence volume and top-tier compensation brackets.
- **Highest-Earning Roles (by Average USD Salary):**
  - **Principal Data Engineer (Expert):** `$600,000`
  - **Financial Data Analyst (Intermediate):** `$450,000`
  - **Principal Data Scientist (Expert):** `$416,000`
  - **Data Analytics Lead (Senior):** `$405,000`
  - **Applied Data Scientist (Senior):** `$278,500`
  - **ML Engineer (Senior):** `$256,000`
  - **Data Engineer (Expert):** `$245,500`

---

## 🛠️ Tools & Technologies Used
- **Tableau Desktop / Tableau Public** — Data modeling, calculated fields, interactive filters, Mapbox integration, and dashboard UI design.
- **Dataset:** Global Data Science Salaries Dataset (`salary_in_usd`, `experience_level`, `employment_type`, `job_title`, `employee_residence`, `company_location`, `company_size`).

---

## 🚀 How to Use
1. Clone this repository or download the `.twbx` workbook file:
   ```bash
   git clone [https://github.com/your-username/data-science-salaries-tableau.git](https://github.com/your-username/data-science-salaries-tableau.git)
