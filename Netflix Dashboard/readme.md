# 🎬 Netflix Content Analysis Dashboard (Tableau)

An interactive Tableau dashboard analyzing Netflix's catalog of movies and TV shows[cite: 5]. Built with a Netflix-inspired dark theme, this visualization explores content distribution, release trends, geographical reach, maturity ratings, and top genres across **6,234 total titles**[cite: 5, 6, 7].

---

## 📊 Dashboard Overview

### 1. Interactive Title Explorer (Top KPI Banner)
Users can filter by **Type** (`Movie` or `TV Show`) and **Title** to dynamically inspect metadata for any specific entry in the catalog[cite: 5]:
* **Rating** (e.g., `TV-14`)[cite: 5, 16]
* **Duration** (e.g., `1 Season` or runtime in minutes)[cite: 5, 14]
* **Release Year** (e.g., `2009`)[cite: 5, 18]
* **Date Added** (e.g., `2016`)[cite: 5, 12]
* **Genre** (e.g., `International TV Shows, Romantic TV Shows, TV Comedies`)[cite: 5, 20]
* **Description** (Full plot synopsis)[cite: 5, 10]

---

### 2. Key Visualizations & Insights

* **Movies & TV Shows Distribution (Packed Bubble Chart)**[cite: 5]
  * **Movies:** 4,265 titles (**68.42%**)[cite: 5, 6]
  * **TV Shows:** 1,969 titles (**31.58%**)[cite: 5, 7]
  * Movies make up more than two-thirds of the catalog[cite: 6].

* **Total Movies and TV Shows by Years (Area Chart: 2008 – 2020)**[cite: 1, 2, 5]
  * Tracks the distinct count of titles added over time[cite: 1, 2].
  * Content additions remained minimal between 2008 and 2014 before experiencing exponential growth starting in 2015[cite: 1], peaking in **2019** (~2,350+ total titles added, led heavily by Movies)[cite: 2].

* **Total Movies & TV Shows by Country (Choropleth Map)**[cite: 3, 5]
  * Visualizes global content production density using a distinct count of `Show Id` (ranging from 1 up to 2,032 titles per country)[cite: 3, 5].

* **Ratings Breakdown (Vertical Bar Chart)**[cite: 5, 8, 9]
  * **TV-MA** leads the catalog with **2,027** titles, followed by **TV-14** (**1,698**) and **TV-PG** (**701**)[cite: 8].
  * Other notable ratings include **R** (508), **PG-13** (286), **NR** (218), **PG** (184), **TV-Y7** (169), **TV-G** (149), **TV-Y** (143), **TV-Y7-FV** (95), **G** (37), **Null** (10), **UR** (7), and **NC-17** (2)[cite: 8, 9].
  * Demonstrates a strong concentration toward mature and teen audiences (`TV-MA` and `TV-14` combined represent nearly 60% of the library)[cite: 6, 7, 8].

* **Top 10 Genres (Horizontal Bar Chart)**[cite: 4, 5]
  1. **Documentaries** — 299[cite: 4]
  2. **Stand-Up Comedy** — 273[cite: 4]
  3. **Dramas, International Movies** — 248[cite: 4]
  4. **Dramas, Independent Movies, International Movies** — 186[cite: 4]
  5. **Comedies, Dramas, International Movies** — 174[cite: 4]
  6. **Kids' TV** — 159[cite: 4]
  7. **Documentaries, International Movies** — 150[cite: 4]
  8. **Children & Family Movies, Comedies** — 129[cite: 4]
  9. **Comedies, International Movies** — 120[cite: 4]
  10. **Children & Family Movies** — 120[cite: 4]

---

## 🛠️ Tools & Features Used
* **Tool:** Tableau Desktop / Tableau Public
* **Charts Used:** Choropleth Map, Packed Bubble Chart, Area Chart, Vertical & Horizontal Bar Charts, Dynamic KPI Cards[cite: 5].
* **Interactivity:** Global filters for **Type** and **Title** linked across metadata KPI cards[cite: 5].

---

## 🚀 How to Use
1. Download the `.twbx` (Tableau Packaged Workbook) file from this repository.
2. Open it using **Tableau Desktop** or the free **Tableau Reader** / **Tableau Public** app.
3. Use the **Type** and **Title** dropdown filters on the dashboard to explore details for individual movies or series[cite: 5].
