# IPL-2008-2022-Match-Ball-by-Ball-Analysis-Power-BI-Dashboard
Comprehensive IPL data analysis dashboard built using match-level and ball-by-ball data (2008–2022), featuring player performance insights, team analysis, and advanced cricket statistics in Power BI.

# 🏏 IPL Data Analysis Dashboard (2008–2022)  
## Match & Ball-by-Ball Cricket Analytics | Power BI Project

---

## 🚀 Project Overview

This project provides a comprehensive analysis of Indian Premier League (IPL) data from 2008 to 2022 using Power BI.

Using both match-level and ball-by-ball datasets, this dashboard delivers deep insights into:

- Team performance trends  
- Player statistics  
- Match outcomes  
- Batting and bowling analysis  
- Season-wise comparisons  

The goal is to transform raw cricket data into structured analytical insights for performance evaluation and strategic understanding.

---

## 🧠 Business / Analytical Objective

Cricket analytics plays a key role in understanding team performance, player contributions, and match strategies.

This project answers key questions such as:

- Which teams have performed consistently across seasons?
- Who are the top run scorers and wicket-takers?
- How does performance vary by venue?
- What are the scoring patterns across overs?
- Which teams dominate head-to-head matchups?
- How do toss decisions influence match results?

The dashboard enables interactive exploration of 15+ years of IPL data.

---

## 📂 Dataset Description

### 1️⃣ Match-Level Dataset  
**File:** `ipl_matches_2008_2022.csv`

Contains:

- Match ID  
- Season  
- Date  
- Venue  
- Team1  
- Team2  
- Toss Winner  
- Toss Decision  
- Match Winner  
- Result Margin  

---

### 2️⃣ Ball-by-Ball Dataset  
**File:** `ipl_ball_by_ball_2008_2022.csv`

Contains:

- Match ID  
- Over  
- Ball  
- Batting Team  
- Bowling Team  
- Batsman  
- Bowler  
- Runs Scored  
- Extra Runs  
- Wicket Information  

This dataset enables granular performance analysis at delivery level.

---

## 🛠 Tools & Technologies Used

- **Power BI** – Data modeling and dashboard development  
- **Power Query** – Data cleaning & transformation  
- **DAX** – KPI calculations and advanced measures  
- **Relational Data Modeling** – Match ID-based relationship between datasets  
- **GitHub** – Documentation and version control  

---

## 📈 Key Measures Used in the Dashboard

The following KPIs and calculated measures were created:

- Total Matches Played  
- Total Runs Scored  
- Total Wickets  
- Top Run Scorers  
- Top Wicket Takers  
- Strike Rate Analysis  
- Economy Rate Analysis  
- Team Win Percentage  
- Toss Impact Analysis  
- Venue-wise Performance  
- Season-wise Trends  

These measures enable dynamic filtering and in-depth cricket analytics.

---

## 📊 Dashboard Features

### 1️⃣ Team Performance Analysis
- Matches Played
- Win Percentage
- Head-to-Head Comparison
- Season-wise Performance Trends

---

### 2️⃣ Batting Analysis
- Top Run Scorers
- Strike Rate Comparison
- Runs by Season
- Boundary Analysis

---

### 3️⃣ Bowling Analysis
- Leading Wicket Takers
- Economy Rate Analysis
- Bowling Performance by Over
- Wicket Distribution Patterns

---

### 4️⃣ Match Insights
- Toss Decision Impact
- Venue-Based Analysis
- Result Margin Trends
- Season Comparisons (2008–2022)

---

## 📸 Dashboard Preview

<img width="686" height="415" alt="image" src="https://github.com/user-attachments/assets/81f70a15-d925-49a8-9d7c-1777a2bb63ca" />


---

## 🏗 Data Model Architecture

```
ipl_matches_2008_2022.csv  
            │  
            │ (Match ID Relationship)  
            ▼  
ipl_ball_by_ball_2008_2022.csv  
            ↓  
Data Cleaning & Transformation  
            ↓  
KPI & Measure Creation  
            ↓  
Interactive Power BI Dashboard
```

The relationship between match-level and ball-by-ball data enables multi-dimensional analysis.

---

## 💡 Key Insights

- Certain teams show strong seasonal dominance patterns.
- Toss decisions have measurable impact on match outcomes.
- Strike rate and boundary frequency significantly influence match-winning innings.
- Specific venues demonstrate high-scoring trends.
- Consistent bowlers maintain low economy rates across seasons.

---

## 📁 Repository Structure

```
IPL-Data-Analysis-Dashboard
│
├── README.md
├── ipl_matches_2008_2022.csv
├── ipl_ball_by_ball_2008_2022.csv
├── IPL Analysis Final.pbix
└── screenshots/
```

---

## 🎯 Project Outcome

This project demonstrates:

- Multi-table relational data modeling  
- Sports analytics capability  
- Advanced KPI design  
- Large dataset handling  
- Interactive dashboard storytelling  
- Performance trend analysis over 15 seasons  

---

## 🔮 Future Enhancements

- Predictive match outcome modeling  
- Player performance forecasting  
- Advanced clustering for team comparison  
- Integration with live IPL data API  

---

## 📌 Conclusion

This IPL Data Analysis Dashboard provides a comprehensive analytical view of 15 seasons of cricket data.

It showcases how structured data modeling and visualization techniques can transform sports statistics into meaningful performance insights.
