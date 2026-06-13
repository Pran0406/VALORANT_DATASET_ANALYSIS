# 🎮 VALORANT Data Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing **VALORANT player and match data** to uncover insights about player performance, agent selection, win rates, map statistics, combat efficiency, and overall gameplay trends.

The objective of this project is to demonstrate data analytics skills including:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Data Modeling
* Dashboard Development
* Data Visualization
* KPI Analysis

---

# 🎯 Business Problem

Competitive games generate a large amount of data. Understanding player performance and gameplay trends can help players improve their strategies and make better decisions.

This project answers questions such as:

* Which agents are selected most frequently?
* Which agents have the highest win rates?
* Which maps produce the highest number of kills?
* What factors influence match victories?
* Which players have the highest combat scores?
* How do K/D ratios impact overall performance?

---

# 📊 Dataset Information

The dataset contains VALORANT match and player statistics.

### Dataset Features

| Column         | Description             |
| -------------- | ----------------------- |
| Match ID       | Unique Match Identifier |
| Player Name    | Name of Player          |
| Agent          | Selected Agent          |
| Map            | Match Map               |
| Kills          | Total Kills             |
| Deaths         | Total Deaths            |
| Assists        | Total Assists           |
| Combat Score   | Average Combat Score    |
| Headshots      | Total Headshots         |
| Damage         | Damage Dealt            |
| Match Result   | Win / Loss              |
| Rank           | Player Rank             |
| Team           | Team Name               |
| Match Duration | Duration of Match       |

---

# 🛠 Tools & Technologies Used

| Tool       | Purpose                   |
| ---------- | ------------------------- |
| Excel      | Initial Data Cleaning     |
| SQL        | Data Querying             |
| Python     | Data Analysis             |
| Pandas     | Data Transformation       |
| NumPy      | Numerical Operations      |
| Matplotlib | Visualization             |
| Seaborn    | Statistical Visualization |
| Power BI   | Dashboard Development     |
| GitHub     | Version Control           |

---

# 📂 Project Workflow

## 1️⃣ Data Collection

* Imported raw VALORANT match data.
* Verified data consistency.
* Identified missing values.

---

## 2️⃣ Data Cleaning

Performed:

* Null Value Treatment
* Duplicate Removal
* Data Type Conversion
* Outlier Detection
* Standardization of Agent Names
* Standardization of Map Names

---

## 3️⃣ Data Transformation

Created additional metrics:

### Kill Death Ratio

K/D Ratio = Kills ÷ Deaths

### Headshot Percentage

Headshot % = (Headshots ÷ Total Shots) × 100

### Win Rate

Win Rate = (Wins ÷ Total Matches) × 100

### Average Combat Score

ACS = Total Combat Score ÷ Matches Played

---

## 4️⃣ Exploratory Data Analysis (EDA)

Analyzed:

### Player Performance

* Top Kill Leaders
* Highest ACS Players
* Best K/D Ratios
* Most Valuable Players

### Agent Analysis

* Most Picked Agents
* Highest Win Rate Agents
* Agent Role Distribution

### Map Analysis

* Most Played Maps
* Highest Win Rate Maps
* Average Kills by Map

### Team Analysis

* Team Win Percentage
* Team Combat Score
* Match Outcomes

---

# 📈 Key Performance Indicators (KPIs)

### Player KPIs

✅ Total Matches

✅ Total Kills

✅ Total Deaths

✅ Total Assists

✅ Average Combat Score

✅ K/D Ratio

✅ Headshot %

---

### Match KPIs

✅ Win Rate

✅ Loss Rate

✅ Average Match Duration

✅ Total Damage Dealt

✅ Total Rounds Won

---

# 📊 Dashboard Features

The dashboard includes:

### Executive Summary

* Total Matches
* Total Players
* Total Wins
* Overall Win Rate

### Player Analysis Page

* Top Players
* K/D Ratio Rankings
* ACS Rankings
* Headshot Analysis

### Agent Analysis Page

* Agent Pick Rate
* Agent Win Rate
* Agent Performance Comparison

### Map Analysis Page

* Map Popularity
* Map Win Rates
* Map Performance Metrics

### Match Analysis Page

* Match Trends
* Win/Loss Distribution
* Combat Score Distribution

---

# 📷 Dashboard Preview

Add screenshots here:

```markdown
![Dashboard Overview](images/dashboard_overview.png)

![Player Analysis](images/player_analysis.png)

![Agent Analysis](images/agent_analysis.png)

![Map Analysis](images/map_analysis.png)
```

---

# 📌 Insights Discovered

### Agent Insights

* Duelists were selected most frequently.
* Certain Controllers showed higher win percentages.
* Sentinel agents contributed to longer match durations.

### Map Insights

* Some maps consistently produced higher average kills.
* Specific maps had significantly higher win rates.

### Player Insights

* Higher ACS generally correlated with winning matches.
* Players with strong K/D ratios often maintained higher win percentages.
* Headshot percentage positively impacted overall performance.

---

# 🚀 Future Improvements

* Real-Time Match Tracking
* Riot API Integration
* Rank Progression Analysis
* Predictive Win Probability Models
* Machine Learning Player Performance Prediction
* Automated Dashboard Refresh

---

# 📁 Project Structure

```bash
VALORANT-Data-Analysis/
│
├── Dataset/
│   ├── valorant_matches.csv
│
├── SQL/
│   ├── analysis_queries.sql
│
├── Python/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│
├── PowerBI/
│   ├── valorant_dashboard.pbix
│
├── Images/
│   ├── dashboard_overview.png
│
├── README.md
│
└── Requirements.txt
```

---

# 💡 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Data Visualization
* Dashboard Design
* Statistical Analysis
* KPI Development
* SQL Querying
* Python Programming
* Business Intelligence
* Storytelling with Data

---

# 👨‍💻 Author

**Pranav Tryambake**

Data Analyst | Power BI | SQL | Python | Excel

### Connect With Me

* LinkedIn: Add Your LinkedIn URL
* GitHub: Add Your GitHub Profile URL

---

# ⭐ If you found this project useful, don't forget to Star the Repository!
