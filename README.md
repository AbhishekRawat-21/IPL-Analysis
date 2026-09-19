# 🏏 IPL Data Analysis (2008–2020)

## 📌 Project Overview

The Indian Premier League (IPL) generates a large amount of match and ball-by-ball data that can be used to understand team performance, player achievements, match outcomes, toss decisions, scoring patterns, and venue distribution.

This project presents an exploratory data analysis of IPL data from **2008 to 2020** using **Python, Pandas, NumPy, Matplotlib, SQL, and SQLite**.

The analysis follows a structured Data Analytics workflow:

- Data Loading
- Data Understanding
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Match-Level Analysis
- Ball-by-Ball Analysis
- SQL Analysis
- Data Visualization
- Key Insights

The objective of this project is to transform raw IPL data into meaningful insights and identify patterns in team and player performance.

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Programming Language | Python, SQL |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Database | SQLite |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

---

## 📂 Dataset

This project uses two IPL datasets covering the **2008–2020 seasons**.

### 1. Match-Level Dataset

Contains information about individual IPL matches, including:

- Match ID
- Date
- City
- Venue
- Teams
- Toss Winner
- Toss Decision
- Match Winner
- Player of the Match
- Result
- Result Margin
- Umpires

### 2. Ball-by-Ball Dataset

Contains delivery-level information from IPL matches, including:

- Match ID
- Batting Team
- Bowling Team
- Batsman
- Bowler
- Runs scored by batsman
- Extra runs
- Total runs
- Wickets
- Dismissal information

These datasets were cleaned, transformed, and analyzed to perform match-level and ball-by-ball analysis.

---

## 🔄 Project Workflow

This project follows a structured Data Analytics workflow:

1. Import required Python libraries.
2. Load the match-level and ball-by-ball datasets.
3. Understand the structure, data types, missing values, and duplicates.
4. Remove empty rows and clean the datasets.
5. Correct data types and standardize team names.
6. Create the `Season` feature from match dates.
7. Perform match-level analysis.
8. Perform ball-by-ball analysis.
9. Perform SQL-based analysis using SQLite.
10. Create visualizations using Matplotlib.
11. Identify important patterns and insights.
12. Summarize the findings and conclusions.

---

## 📊 Analysis Performed

Match-Level Analysis

The match-level dataset was used to analyze:

- Number of matches played in each IPL season
- Total wins by each team
- Winning percentage by team
- Toss decisions
- Toss winner vs match winner
- Team performance after choosing to bat or field
- Player of the Match awards
- Most frequently used venues

Ball-by-Ball Analysis

The delivery-level dataset was used to analyze:

- Top run scorers
- Top wicket takers
- Players with the most sixes
- Total runs scored by each team
- Highest team innings scores
- Average runs per match by team


