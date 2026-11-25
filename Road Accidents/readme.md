# 🚗 Road Accident Analysis Dashboard (Tableau)

An interactive Tableau dashboard analyzing UK road accident and casualty trends across years, vehicle types, weather conditions, road surfaces, and geographic locations[cite: 21].

---

## 📊 Dashboard Preview

![Road Accident Dashboard](assets/road_accident_dashboard.png)

> *Note: Replace the image path above with the screenshot file path in your repository.*

---

## 🎯 Project Overview

This dashboard provides a comparative Year-over-Year (YoY) view of road accidents and casualties (comparing **Current Year: 2020** vs. **Previous Year: 2019** by default)[cite: 21]. It enables stakeholders, transport authorities, and analysts to identify high-risk vehicle categories, environmental conditions, road types, and geographic hotspots[cite: 21].

---

## 📈 Key Performance Indicators (KPIs)

Each primary metric card displays the **Current Year (CY)** total, **Year-over-Year (YoY) percentage change**, and a **monthly sparkline** comparing CY vs. PY trends (January–December)[cite: 11, 12, 21]:

| Metric | CY Total (2020) | YoY Change | Description |
| :--- | :---: | :---: | :--- |
| **Total Accidents** | `170,591`[cite: 21] | `6.33% YoY`[cite: 1, 21] | Total recorded road traffic accidents[cite: 21] |
| **Total Casualties** | — | `6.81% YoY`[cite: 3, 21] | Combined count of all injury severities |
| **Fatal Casualties** | `4,398`[cite: 21] | `17.81% YoY`[cite: 5, 21] | Accidents resulting in fatalities |
| **Serious Casualties** | `33,987`[cite: 21] | `5.84% YoY`[cite: 7, 21] | Accidents resulting in severe injuries |
| **Slight Casualties** | `192,520`[cite: 21] | `6.69% YoY`[cite: 9, 21] | Accidents resulting in minor injuries |

---

## 🧩 Dashboard Components & Visuals

1. **Interactive Filters (Top Header)**[cite: 21]
   * **Current Year (`2020`)** & **Previous Year (`2019`)** parameters/filters for dynamic YoY benchmarking[cite: 21].
   * **Select Accident Severity** (`Fatal`, `Serious`, `Slight`) dynamically updates downstream breakdowns[cite: 24, 25].

2. **Casualties by Vehicle Type (KPI Banner with Custom Icons)**
   * Breaks down selected severity casualties across grouped vehicle categories (showing exact count and % share)[cite: 21, 24]:
     * **Car:** `3,374` (`15.08%`)[cite: 21]
     * **Van:** `387` (`28.20%`)[cite: 21]
     * **Motorcycle:** `320` (`31.62%`)[cite: 21]
     * **Bus:** `268` (`18.04%`)[cite: 21]
     * **Others:** `41` (`36.67%`)[cite: 21]
     * **Agricultural Vehicle:** `8` (`42.86%`)[cite: 21]

3. **Casualties by Weather Conditions (Donut Chart)**[cite: 21, 26]
   * **Fine:** `83.63%`[cite: 21, 26]
   * **Rain:** `12.21%`[cite: 21, 26]
   * **Others:** `2.96%`[cite: 21, 26]
   * **Snow/Fog:** `1.21%`[cite: 21, 26]

4. **Casualties by Road Surface Conditions (Donut Chart)**[cite: 21, 28]
   * **Dry:** `63.82%`[cite: 21, 28]
   * **Wet:** `33.63%`[cite: 21, 28]
   * **Frost/Snow:** `2.52%`[cite: 21, 28]
   * **Unknown:** `0.02%`[cite: 21, 28]

5. **Casualties by Road Type (Horizontal Bar Chart)**[cite: 21]
   * **Single carriageway:** `3,318`[cite: 21]
   * **Dual carriageway:** `951`[cite: 21]
   * **Roundabout:** `49`[cite: 21]
   * **One way street:** `41`[cite: 21]
   * **Null / Unspecified:** `21`[cite: 21]
   * **Slip road:** `18`[cite: 21]

6. **Geospatial Hotspot Map (`Mapbox` / `OpenStreetMap`)**[cite: 21, 33]
   * Plots individual accident coordinates across the United Kingdom to highlight high-density urban and highway clusters[cite: 21, 33].

---

## 🛠️ Tools & Techniques Used

* **Tableau Desktop / Tableau Public**
* **Calculated Fields:** CY vs. PY aggregations, YoY `%` variance formulas, and dynamic severity filtering[cite: 11, 21, 24].
* **Data Grouping:** Consolidated raw vehicle types, weather events, and road surface categories into clean analytical groups[cite: 24, 26, 28].
* **Visual Design:** Dark-theme executive layout, dual-line/area monthly sparklines, custom shape KPIs, donut charts, and dark-mode Mapbox geospatial mapping[cite: 11, 21, 24, 26, 33].

---

## 📂 Repository Structure

```text
├── Road_Accidents.twbx          # Packaged Tableau Workbook
├── Road Accidents.pdf           # Exported PDF sheets & dashboard view
├── data/                        # Raw / cleaned dataset (if included)
├── assets/                      # Dashboard screenshots & custom vehicle icons
└── README.md                    # Project documentation
