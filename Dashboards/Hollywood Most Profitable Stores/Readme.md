# 🎬 Hollywood Stories — Tableau Dashboard

An interactive Tableau data visualization project exploring box office performance, studio profitability, critic vs. audience reception, and genre trends across 74 Hollywood films released between **2007 and 2011**[cite: 2, 9, 10].

---

## 📊 Executive Summary & Key KPIs

The dashboard tracks the following core metrics across the dataset[cite: 2, 3, 4, 5, 6, 7]:

| Metric | Value |
| :--- | :--- |
| **Total Films** | 74[cite: 2] |
| **Total Lead Studios** | 13[cite: 3] |
| **Total Genres** | 6 *(Action, Animation, Comedy, Drama, Fantasy, Romance)*[cite: 4, 8] |
| **Average Audience Score** | 64.14%[cite: 5] |
| **Average Rotten Tomatoes Score** | 47.36%[cite: 6] |
| **Average Worldwide Gross** | $136.4M[cite: 7] |

---

## 📈 Dashboard Visualizations & Components

1. **Profitability by Genre and Lead Studio (Stacked Bar Chart)**
   * Compares cumulative profitability across 13 studios broken down by genre[cite: 8].
   * **Top Performers:** *Independent* leads overall profitability (driven heavily by Drama at 17.73)[cite: 8], followed by *Summit* (led by Romance at 10.18 and Drama at 8.84)[cite: 8], *Sony*[cite: 8], and *Disney* (led by Comedy at 11.60)[cite: 8].
2. **Total Films by Year and Genre (Stacked Column Chart)**
   * Tracks annual release volume from **2007 to 2011** segmented by genre[cite: 9, 10].
   * **Release Peaks:** **2008** (19 films, dominated by 12 Comedies)[cite: 9] and **2010** (19 films, dominated by 15 Comedies)[cite: 10] saw the highest output, while **2011** shifted toward Romance (8 of 13 releases)[cite: 10].
3. **Films by Genre (Donut Chart)**
   * Displays the percentage share of the 74 films across genres[cite: 2, 11].
   * **Comedy** makes up the majority of the dataset at **55.41%** (41 films), followed by **Drama** at **20.27%** and **Romance** at **17.57%**[cite: 11].
4. **Films by Lead Studio (Donut Chart)**
   * Shows market share by studio production count[cite: 13].
   * **Independent** productions account for the largest single share at **25.68%** (19 films), followed by **Warner Bros.** at **16.22%**[cite: 13].
5. **Audience Score vs. Rotten Tomatoes % (Scatter Plot)**
   * Evaluates alignment and divergence between general moviegoers and film critics[cite: 15].
   * **Universal Acclaim:** *WALL-E* (96% RT / 89% Audience), *Midnight in Paris* (93% RT / 84% Audience), and *Tangled* (89% RT / 88% Audience)[cite: 15, 19, 20, 21].
   * **Audience Favorites / Critic Misses:** *P.S. I Love You* (21% RT vs. 82% Audience) and *The Twilight Saga: New Moon* (27% RT vs. 78% Audience)[cite: 15, 19, 21].
6. **Worldwide Gross vs. Rotten Tomatoes % (Scatter Plot)**
   * Analyzes whether critical acclaim translates to global box office revenue[cite: 16].
   * **Box Office Outliers:** *The Twilight Saga: New Moon* ($709.8M gross with 27% RT) and *Twilight: Breaking Dawn* (~$702M gross with 26% RT) topped the box office despite low critic scores, whereas *Mamma Mia!* ($609.5M, 53% RT) and *WALL-E* ($521.3M, 96% RT) paired strong commercial returns with higher critical reception[cite: 16, 17, 21].
7. **Film Details (Interactive Table & Bar Matrix)**
   * Provides granular, filterable records for every film, including **Lead Studio**, **Genre**, **Release Year**, **Audience Score %**, **Profitability**, **Rotten Tomatoes %**, and **Worldwide Gross**[cite: 17].

---

## 🔍 Key Analytical Insights

* **Critics Don't Dictate Box Office Success:** High-grossing franchises (*Twilight*, *Sex and the City*) achieved massive worldwide grosses ($375M–$710M) despite below-average Rotten Tomatoes scores (<50%)[cite: 16, 20, 21].
* **Audience vs. Critic Gap:** On average, audiences rated films **~16.8 percentage points higher** (64.14%) than Rotten Tomatoes critics (47.36%)[cite: 5, 6].
* **Genre Dominance:** Comedy, Drama, and Romance together represent **93.25%** of all releases in the dataset[cite: 11], with Independent studios leading both total film volume and cumulative profitability[cite: 8, 13].

---

## 🛠️ Tools & Files

* **Visualization Tool:** Tableau Desktop / Tableau Public
* **Repository Contents:**
  * `Hollywood Stories.twbx` / `.twb` — Packaged Tableau Workbook
  * `Hollywood Stories Dashboard.pdf` — Exported dashboard views and individual worksheet breakdowns[cite: 1, 22]

---

## 🚀 How to Use

1. Clone this repository or download the `.twbx` workbook file.
2. Open the file in **Tableau Desktop** or **Tableau Public**.
3. Use the interactive filters (Genre, Lead Studio, Year) and hover tooltips across the scatter plots and **Film Details** table to explore individual movie metrics[cite: 17, 22].
