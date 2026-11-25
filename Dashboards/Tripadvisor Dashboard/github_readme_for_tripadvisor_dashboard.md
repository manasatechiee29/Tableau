# 📊 Tripadvisor Hotel & User Analytics Dashboard

An interactive Tableau dashboard analyzing hotel amenities, capacity, star ratings, and user demographics based on Tripadvisor review data (primarily focusing on major Las Vegas resorts).

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [Dashboard Visualizations & Insights](#-dashboard-visualizations--insights)
- [Dataset Overview](#-dataset-overview)
- [Tools Used](#-tools-used)
- [How to View](#-how-to-view)

---

## 🎯 Project Overview
The goal of this project is to uncover patterns in hotel offerings and traveler behavior using Tripadvisor review data. By visualizing key metrics such as room capacity, hotel amenities, user origin, travel seasons, and traveler types, this dashboard provides actionable insights into the hospitality landscape.

---

## 📈 Key Performance Indicators (KPIs)
At the top of the dashboard, four high-level KPI cards summarize the dataset:
* **Total Hotels:** `21`
* **Average Number of Rooms:** `2,196`
* **Average Review Score:** `4.123 / 5.0`
* **User's Average Reviews:** `48.13` (average total reviews contributed per user on Tripadvisor)

---

## 🔍 Dashboard Visualizations & Insights

### 1. **Top 10 Hotels by Total Rooms** *(Horizontal Bar Chart)*
Highlights the largest properties in the dataset by room capacity.
* **Top 3 Largest Properties:**
  1. **The Venetian Las Vegas Hotel:** 4,027 rooms
  2. **Excalibur Hotel & Casino:** 3,981 rooms
  3. **Bellagio Las Vegas:** 3,933 rooms

### 2. **Total Hotels by Additional Services** *(Highlight Table / Matrix)*
Breaks down the availability of key amenities (**Exercise Room**, **Free Wi-Fi**, **Club**, and **Basketball Court**) across the 21 hotels.
* **Key Takeaway:** The vast majority of hotels (**17 out of 21**) offer a combination of an Exercise Room, Free Wi-Fi, and a Club (13 without a Basketball Court, and 4 with all four amenities).

### 3. **Total Hotels by Stars** *(Bar Chart)*
Displays the distribution of hotel star ratings across the analyzed properties:
* **5.0 Stars:** 8 hotels
* **4.0 Stars:** 5 hotels
* **3.0 Stars:** 4 hotels
* **4.5 Stars:** 3 hotels
* **3.5 Stars:** 1 hotel

### 4. **Total Users by Continent** *(Horizontal Bar Chart)*
Shows the geographic distribution of reviewers (504 total reviews analyzed):
* **North America:** 295 users (58.5%)
* **Europe:** 118 users (23.4%)
* **Oceania:** 41 users (8.1%)
* **Asia:** 36 users (7.1%)
* **South America:** 7 users (1.4%)
* **Africa:** 7 users (1.4%)

### 5. **Traveler Type** *(Treemap)*
Categorizes visitors based on who they traveled with:
* **Couples:** 214 (42.5%)
* **Families:** 110 (21.8%)
* **Friends:** 82 (16.3%)
* **Business:** 74 (14.7%)
* **Solo:** 24 (4.8%)

### 6. **Users by Period of Stay** *(Packed Bubble Chart)*
Demonstrates consistent year-round travel demand across all four quarters:
* **Mar–May (Spring):** 128 users
* **Jun–Aug (Summer):** 126 users
* **Sep–Nov (Fall):** 126 users
* **Dec–Feb (Winter):** 124 users

---

## 🗂️ Dataset Overview
The underlying dataset is the classic **Tripadvisor Las Vegas Strip Dataset** (504 user reviews across 21 hotels), containing attributes across three dimensions:
* **Hotel Attributes:** Hotel name, star rating, total rooms, and boolean flags for amenities (Pool, Exercise Room, Tennis Court, Spa, Casino, Free Internet, Club, Basketball Court).
* **User Attributes:** User country, continent, total Tripadvisor reviews, and helpful votes.
* **Review Attributes:** Review score (1–5), period of stay, and traveler type.

---

## 🛠️ Tools Used
* **Tableau Desktop / Tableau Public:** Data visualization, KPI cards, and interactive dashboard layout.
* **Excel / CSV:** Initial data inspection and structuring.

---

## 🚀 How to View
1. **Tableau Public:** *[Insert your Tableau Public Dashboard Link here]*
2. **Local Viewing:** Download the `.twbx` (Tableau Packaged Workbook) file from this repository and open it using **Tableau Desktop** or the free **Tableau Reader**.
3. **Static Preview:** Refer to the exported PDF/images included in this repository.