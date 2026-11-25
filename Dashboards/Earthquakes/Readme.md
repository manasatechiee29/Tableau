# 🌍 Global Earthquake Analysis Dashboard (Tableau)

An interactive Tableau data visualization project analyzing historical global seismic activity, earthquake magnitudes, focal depths, and recording station telemetry across nearly a century of recorded events.

---

## 📊 Key Performance Indicators (KPIs)

The dashboard opens with high-level summary cards highlighting overall dataset metrics:

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Earthquakes** | `7,408`[cite: 1] | Total number of recorded seismic events in the dataset |
| **Average Magnitude / Depth** | `78.01 km`[cite: 5] | Mean focal depth of recorded earthquakes[cite: 5] |
| **Average Dmin** | `4.264`[cite: 2] | Mean horizontal distance from the epicenter to the nearest station (in degrees) |
| **Average Gap** | `30.42°`[cite: 3] | Mean largest azimuthal gap between azimuthally adjacent stations |
| **Max Gap** | `30.42°`[cite: 7] | Maximum azimuthal gap metric displayed in the summary panel |
| **Average Nst** | `275.0`[cite: 4] | Mean total number of seismic stations used to determine earthquake location |
| **Average RMS** | `1.008`[cite: 6] | Mean root-mean-square travel time residual (in seconds) |

---

## 📈 Dashboard Visualizations & Insights

### 1. Temporal Trends
* **Total Earthquakes by Year:** Tracks long-term seismic activity trends over the decades (spanning from the 1920s onward), segmented by magnitude measurement scales (`mb`, `ms`, `mw`, `mwb`, `mwc`, `mwp`, `mwr`, `mww`, `Mt`, `uk`, and `Null`)[cite: 8].
* **Total Earthquakes by Month & Magnitude Type:** A stacked bar chart comparing monthly seismic frequency from January through December[cite: 9, 10]. Surface-wave magnitude (`ms`) and moment magnitude (`mw`) represent the dominant measurement classifications across all months[cite: 9, 10].

### 2. Distributions & Correlations
* **Magnitude Histogram:** Displays the frequency distribution of earthquake magnitudes (ranging from `6.0` up to `9.6`), showing the highest concentration of events in the `6.0 – 6.4` range (`2,775` events) and tapering sharply at major/great earthquake thresholds (`8.0+`)[cite: 11, 13].
* **Depth in km Histogram:** Illustrates the distribution of focal depths from shallow crustal quakes (`0–20 km`, accounting for `5,313` events) down to deep-focus subduction zone events (`600+ km`)[cite: 12].
* **Relationship Between Depth and Magnitude:** A scatter plot analyzing the correlation between focal depth (`km`) and earthquake magnitude (`6.0` to `9.6`), highlighting that the highest-magnitude mega-quakes (`8.5+`) predominantly occur at shallower depths[cite: 13].

### 3. Geospatial & Event-Level Exploration
* **Total Earthquakes by Places (Interactive Map):** Powered by Mapbox & OpenStreetMap, plotting global epicenters sized/colored by event count (`Count of Id`, peaking at `322` in top seismic zones) along major tectonic plate boundaries such as the Pacific Ring of Fire[cite: 14].
* **Earthquake Details Table:** A granular tabular view listing **Date**, **Place**, **Magnitude (`Mag`)**, **Depth (`km`)**, and station count indicator (`Total Nst`) for individual historical events (e.g., the `9.6` magnitude earthquake in Araucania, Chile on May 22, 1960; the `9.2` Southern Alaska earthquake on March 28, 1964)[cite: 15, 58, 64].

---

## 🛠️ Tools & Technologies
* **Visualization:** Tableau Desktop / Tableau Public
* **Mapping:** Mapbox & OpenStreetMap integration[cite: 14]
* **Data Export:** PDF Dashboard Report (`Earthquake Dashboard.pdf`)

---

## 🚀 How to Use
1. Clone this repository or download the `.twbx` / `.pdf` files.
2. Open the workbook in **Tableau Desktop** or **Tableau Public** to interact with filters by **Year**, **Month**, **Magnitude Type**, and **Geographic Region**.
3. Hover over map markers or bar segments to inspect exact station telemetry (`Dmin`, `Gap`, `Nst`, `RMS`) and event details.
