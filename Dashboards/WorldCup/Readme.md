# 🏆 FIFA World Cup Results Dashboard (1930–2014)

An interactive Tableau dashboard analyzing historical FIFA World Cup data from the inaugural tournament in 1930 through 2014[cite: 15, 16]. This project explores team performance, tournament growth, host nations, stadium venues, and global attendance metrics[cite: 1, 6, 9, 11, 14].

---

## 📊 Dashboard Overview

The dashboard features a dark-themed UI with green and orange highlights[cite: 7, 17] and is structured into **7 core visual modules**[cite: 17]:

1. **Countries That Won the World Cup**[cite: 1, 2, 17]
   - Displays total championship titles by nation[cite: 1, 2].
   - **Highlights:** Brazil leads with **5 titles**[cite: 1], followed by Italy (**4**)[cite: 1], Germany FR (**3**)[cite: 1], Uruguay (**2**)[cite: 1], Argentina (**2**)[cite: 1], and single titles for England, France, Germany, and Spain[cite: 2].

2. **Countries That Hosted the World Cup**[cite: 6, 17]
   - A packed bubble/circle view mapping host nations alongside the specific years they hosted the tournament[cite: 6, 17].
   - **Multi-time Hosts:** Mexico (1970, 1986), Italy (1934, 1990), Germany (1974, 2006), France (1938, 1998), and Brazil (1950, 2014)[cite: 6, 17].

3. **Teams by Total Finals and Semi-Finals**[cite: 3, 4, 5, 17]
   - A butterfly (diverging bar) chart comparing each nation's appearances in World Cup Finals versus Semi-Finals[cite: 17].
   - **Highlights:** Brazil leads in total semi-final appearances (**9**)[cite: 17], while Italy, Germany FR, Brazil, and Argentina each reached **6 finals** (excluding unified Germany's additional 3 finals)[cite: 17].

4. **Competitions Stats by Year**[cite: 9, 10, 17]
   - A stacked bar chart tracking three key tournament expansion metrics across every edition from 1930 to 2014[cite: 9, 10]:
     - **Goals Scored**[cite: 9, 10]
     - **Matches Played**[cite: 9, 10]
     - **Qualified Teams**[cite: 9, 10]

5. **Countries Qualified to World Cup**[cite: 7, 8, 17]
   - A horizontal bar chart ranking all participating nations by the distinct count of World Cup years they qualified for[cite: 7, 8].
   - **Top Qualifiers:** Brazil (**20** appearances—the only nation to qualify for every tournament in this span), Italy (**18**), Argentina (**16**), Mexico (**15**), and Spain, France, and England (**14** each)[cite: 7].

6. **Map: Audience by Country and Year**[cite: 14, 17]
   - A choropleth world map visualizing total tournament attendance across host countries, ranging from early tournaments (~363k–590k) up to the record **3.58 million** attendance in the USA (1994)[cite: 14].

7. **Winners and Top Teams by World Cup Year and Finals Stadium**[cite: 11, 12, 13, 17]
   - A detailed tabular breakdown listing every tournament year grouped by the winning nation, alongside the **Runners-Up**, **Third Place**, **Fourth Place**, **Hosting Country**, and the **Finals Stadium** (e.g., *Estadio Centenario*, *Wembley Stadium*, *Estadio Azteca*, *Rose Bowl*, *Estadio do Maracanã*)[cite: 11].

---

## 🛠️ Tools & Technologies

- **Data Visualization:** Tableau Desktop / Tableau Public[cite: 7, 17]
- **Mapping:** Mapbox & OpenStreetMap integration[cite: 14, 17]
- **Dataset:** Historical FIFA World Cup Results (1930–2014)[cite: 15, 16]

---

## 🚀 How to View / Use

1. **Tableau Workbook (`.twbx` / `.twb`):** Download the workbook file from this repository and open it using **Tableau Desktop** or **Tableau Public**.
2. **Static Preview:** Refer to `WorldCup Dashboard.pdf` in the repository for high-resolution exports of the full dashboard and individual worksheets.
3. **Interactivity:** Click on any country, year, or bar within the dashboard to cross-filter related charts (e.g., selecting *Uruguay* highlights its 1930 host year, 1 final, 4 semi-finals, and 12 tournament appearances)[cite: 6, 7, 17].

---

## 📁 Repository Structure

```text
├── WorldCup Dashboard.pdf        # Exported PDF of the dashboard and individual sheets
├── WorldCup_Dashboard.twbx       # Packaged Tableau workbook (if included)
└── README.md                     # Project documentation
