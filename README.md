# 🏏 IPL 2008–2022 — Match & Ball-by-Ball Analysis | Power BI Dashboard

<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Cricket_Analytics-0078D4?style=for-the-badge&logo=cricket&logoColor=white" />
  <img src="https://img.shields.io/badge/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</p>

A 5-page interactive Power BI dashboard analyzing **15 seasons of IPL cricket** (2008–2022) across **950 matches** and **225,954 deliveries**. Built on two datasets — match-level and ball-by-ball — the report delivers season-filtered general summaries, venue analytics, batting and bowling deep-dives, and Player of the Match tracking across the full history of the tournament.

---

## 📸 Dashboard Preview

### 🔹 General Summary
![General Summary](./screenshots/General_Summary.png)

### 🔹 Season Statistics — Stadiums & Player of the Match
![Season Statistics](./screenshots/Season_Statistics.png)

### 🔹 Batsmen Statistics
![Batsmen Statistics](./screenshots/Batsmen_Statistics.png)

### 🔹 Bowler Statistics
![Bowler Statistics](./screenshots/Bowler_Statistics.png)

> 📌 **To add screenshots:** Open the `.pbix` file → navigate to each page → export or screenshot → save as `.png` inside a `/screenshots` folder in the repo root.

---

## 🔢 Tournament-Wide KPIs (2008–2022)

| Metric | Value |
|---|---|
| 🏟️ Total Matches | 950 |
| 🎯 Total Deliveries | 2,25,954 |
| 🏃 Total Runs Scored | 2,80,979 |
| 🎳 Total Wickets Taken | 11,151 |
| 6️⃣ Total Sixes | 10,666 |
| 4️⃣ Total Fours | 25,500 |
| 📅 Seasons Covered | 15 (2007/08 – 2022) |
| 🏟️ Unique Venues | 49 |
| 🏙️ Cities | 33 |
| 🏆 Teams (incl. defunct) | 18 |

---

## 📋 Dashboard Pages

| Page | Description |
|---|---|
| **1. Title Page** | Branded cover page for the IPL Data Analysis report |
| **2. General Summary** | Season-filtered view — Title Winner, Orange Cap, Purple Cap, 6s, 4s, toss analysis, win-by-type, team wins, venue wins |
| **3. Season Statistics** | Stadium match count by season, Super Over toss decisions, Player of the Match treemap |
| **4. Batsmen Statistics** | Top 10 run-scorers (all-time), dismissal type breakdown, percentage contribution of Top 4 |
| **5. Bowler Statistics** | Top 5 wicket-takers (all-time), extra runs conceded, treemap and pie chart comparisons |

---

## 📊 Visuals & Charts

### Page 2 — General Summary *(Season Filter: 2008–2022)*

**KPI Cards (Season-Filtered)**
Five headline cards show the Title Winner, Orange Cap holder (most runs), Purple Cap holder (most wickets), total Tournament 6's, and total Tournament 4's — all updating dynamically when a season is selected.

**Matches Win Based on Toss — Donut Chart**
Across all seasons, toss winners who chose to **field first** dominated: 599 of 950 (63.05%) toss decisions were to field — confirming chasing is the preferred and statistically stronger strategy in T20 cricket.

**Matches Win by Result Type — Donut Chart**
| Result Type | Count | Share |
|---|---|---|
| Won by Wickets | 509 | 53.58% |
| Won by Runs | 423 | 44.53% |
| Super Over | 14 | 1.47% |
| No Result | 4 | 0.42% |

**Total Wins by Team for a Season — Bar Chart**
Season-specific team wins leaderboard. In 2016 (example): SRH 11, Gujarat Lions 9, RCB 9, KKR 8, DD 7, MI 7.

**Matches Win by Venue — Stacked Bar Chart**
Venue-wise breakdown of wins by runs vs wickets — identifying home-ground advantages and pitch behaviour patterns.

---

### Page 3 — Season Statistics

**Count of Matches by Stadium/Season — Bar Chart**
M Chinnaswamy Stadium (Bengaluru) leads with 9 matches in 2016, followed by Eden Gardens, Feroz Shah Kotla, Punjab Cricket Association, and Rajiv Gandhi International Stadium at 7 each.

**Super Over by Toss Decision — Matrix**
Tracks how often teams winning the toss chose to field vs bat in Super Over situations. In 2016: field 49 instances, bat 11.

**Player of the Match by Season — Treemap**
Visual treemap showing Player of the Match award frequency per season. V Kohli leads with 5 awards in 2016, followed by AB de Villiers (4), RG Sharma (4), AD Russell (3), DA Warner (3).

**All-Time Player of the Match Leaders:**
| Player | Awards |
|---|---|
| AB de Villiers | 25 |
| CH Gayle | 22 |
| DA Warner | 18 |
| RG Sharma | 18 |
| MS Dhoni | 17 |

---

### Page 4 — Batsmen Statistics *(All-Time 2008–2022)*

**Runs Scored by Top 10 Batsmen — Bar Chart**
| Batsman | Total Runs |
|---|---|
| V Kohli | 6,634 |
| S Dhawan | 6,244 |
| DA Warner | 5,883 |
| RG Sharma | 5,881 |
| SK Raina | 5,536 |
| AB de Villiers | 5,181 |
| CH Gayle | 4,997 |
| MS Dhoni | 4,978 |
| RV Uthappa | 4,954 |
| KD Karthik | 4,377 |

**Percentage of Runs by Top 4 — Donut Chart**
Among the Top 4 batsmen's combined total:
| Batsman | Share |
|---|---|
| V Kohli | 27.76% |
| S Dhawan | 26.49% |
| RG Sharma | 24.56% |
| RV Uthappa | 21.18% |

**Count of Top 10 Batsmen by Dismissal Type — Stacked Bar Chart**
Breaks down how each of the top 10 batsmen was dismissed — caught, bowled, caught & bowled, lbw, hit wicket — revealing vulnerability patterns. *Caught* is the dominant dismissal type across all batsmen.

---

### Page 5 — Bowler Statistics *(All-Time 2008–2022)*

**Wickets Taken by Top 5 Bowlers — Treemap + Pie Chart**
| Bowler | Wickets |
|---|---|
| DJ Bravo | 207 |
| SL Malinga | 188 |
| A Mishra | 175 |
| R Ashwin | 174 |
| YS Chahal | 172 |

**Sum of Extra Runs by Top 5 Bowlers — Bar Chart**
| Bowler | Extra Runs Conceded |
|---|---|
| SL Malinga | 292 |
| DJ Bravo | 258 |
| R Ashwin | 209 |
| YS Chahal | 175 |
| A Mishra | 125 |

---

## 💡 Key Insights

**1. V Kohli is the all-time leading run-scorer with 6,634 runs across 15 seasons**
Kohli's consistency is unmatched — nearly 600 more runs than the second-placed Shikhar Dhawan (6,244). He also led Player of the Match awards in 2016 with 5 in a single season.

**2. DJ Bravo leads all bowlers with 207 wickets — but concedes the second-most extras**
Bravo's wicket-taking ability (207) edges SL Malinga (188), but Malinga concedes the most extra runs (292), suggesting aggression comes with control trade-offs.

**3. Teams choosing to field first win significantly more often**
63.05% of toss-winning captains chose to field, and the match results validate this strategy — 53.58% of matches were won by wickets (chasing), vs 44.53% by runs (defending).

**4. 10,666 sixes hit across 15 seasons — averaging 11.2 sixes per match**
The sheer volume of boundaries (25,500 fours + 10,666 sixes) underscores the explosive nature of T20 cricket and the premium on boundary-hitting batsmen.

**5. AB de Villiers is the most impactful match-winner in IPL history**
With 25 Player of the Match awards — 3 more than the next best (CH Gayle at 22) — de Villiers consistently delivered in crunch situations.

**6. Caught dismissals dominate across all top batsmen**
The dismissal type analysis reveals that across all top 10 batsmen, being caught is by far the most common mode of dismissal — a key insight for bowling and fielding strategy.

---

## 🗂️ Dataset Overview

### Dataset 1: `ipl_matches_2008_2022.csv`
**950 matches · 18 columns**

| Category | Columns |
|---|---|
| Match Info | id, match_date, season, match_number, venue, city |
| Teams | team1, team2, toss_winner, toss_decision, winning_team |
| Result | won_by, margin, method, superover |
| Awards | player_of_match |
| Officials | umpire1, umpire2 |

### Dataset 2: `ipl_ball_by_ball_2008_2022.csv`
**2,25,954 deliveries · 17 columns**

| Category | Columns |
|---|---|
| Match Reference | id, innings, overs, ball_number |
| Batting | batter, non_striker, batsman_run, batting_team |
| Bowling | bowler, extras_run, extra_type, total_run, non_boundary |
| Wickets | iswicket_delivery, player_out, dismisal_kind, fielders_involved |

---

## ⚙️ DAX Measures Used

```dax
-- Total Runs
Total Runs = SUM('ball_by_ball'[batsman_run])

-- Total Wickets
Total Wickets = SUM('ball_by_ball'[iswicket_delivery])

-- Total Sixes
Total Sixes = COUNTROWS(FILTER('ball_by_ball', 'ball_by_ball'[batsman_run] = 6))

-- Total Fours
Total Fours = COUNTROWS(FILTER('ball_by_ball', 'ball_by_ball'[batsman_run] = 4))

-- Orange Cap (Season Top Scorer)
-- Achieved via TOP N filter on batter grouped by season

-- Purple Cap (Season Top Wicket-Taker)
-- Achieved via TOP N filter on bowler grouped by season
```

---

## 🏆 IPL Title Winners (2008–2022)

| Season | Champion |
|---|---|
| 2008 | Rajasthan Royals |
| 2009 | Deccan Chargers |
| 2010 | Chennai Super Kings |
| 2011 | Chennai Super Kings |
| 2012 | Kolkata Knight Riders |
| 2013 | Mumbai Indians |
| 2014 | Kolkata Knight Riders |
| 2015 | Mumbai Indians |
| 2016 | Sunrisers Hyderabad |
| 2017 | Mumbai Indians |
| 2018 | Chennai Super Kings |
| 2019 | Mumbai Indians |
| 2020 | Mumbai Indians |
| 2021 | Chennai Super Kings |
| 2022 | Gujarat Titans |

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, data modeling, 5-page report |
| **DAX** | Season-filtered KPIs, rankings, custom measures |
| **Power Query (M)** | Data cleaning, relationship setup between both datasets |
| **CSV (2 files)** | Match-level + ball-by-ball source data |

---

## 📁 File Structure

```
IPL-2008-2022-Match-Ball-by-Ball-Analysis-Power-BI-Dashboard/
│
├── IPL_Analysis_Final.pbix              # Power BI report file (5 pages)
├── ipl_matches_2008_2022.csv            # Match-level dataset (950 rows, 18 cols)
├── ipl_ball_by_ball_2008_2022.csv       # Ball-by-ball dataset (225,954 rows, 17 cols)
│
├── screenshots/
│   ├── General_Summary.png              # Page 2 screenshot
│   ├── Season_Statistics.png            # Page 3 screenshot
│   ├── Batsmen_Statistics.png           # Page 4 screenshot
│   └── Bowler_Statistics.png            # Page 5 screenshot
│
└── README.md                            # Project documentation
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `IPL_Analysis_Final.pbix` in **Power BI Desktop**
3. If prompted, reconnect both CSVs (`ipl_matches_2008_2022.csv` and `ipl_ball_by_ball_2008_2022.csv`) as data sources
4. Use the **Season slicer** on the General Summary page to filter all KPIs by year
5. Navigate across the 5 pages using the tabs at the bottom of Power BI Desktop

---

## 👤 Author

**Sanidhya Rajguru** — Data Analyst | Power BI Developer | MIS Analyst

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white)](YOUR_PORTFOLIO_URL_HERE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL_HERE)
[![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sanidhya572)
