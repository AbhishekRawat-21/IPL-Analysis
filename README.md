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

i) Match-Level Analysis

The match-level dataset was used to analyze:

- Number of matches played in each IPL season
- Total wins by each team
- Winning percentage by team
- Toss decisions
- Toss winner vs match winner
- Team performance after choosing to bat or field
- Player of the Match awards
- Most frequently used venues

ii) Ball-by-Ball Analysis

The delivery-level dataset was used to analyze:

- Top run scorers
- Top wicket takers
- Players with the most sixes
- Total runs scored by each team
- Highest team innings scores
- Average runs per match by team

---

## 📈 Exploratory Data Analysis & Visualizations

## 📈 Visualizations

1. **Matches Played per Season**

   ![Matches Played per Season](graph/Matches%20playes%20per%20Season.png)

2. **Total Wins by Team**

   ![Total Wins by Team](graph/Total%20Wins%20by%20Team.png)

3. **Winning Percentage by Team**

   ![Winning Percentage by Team](graph/Winning%20Percentage%20by%20Team.png)

4. **Most Used Venues**

   ![Most Used Venues](graph/Most%20used%20Venues.png)

5. **Top 5 Players of the Match**

   ![Top 5 Players of the Match](graph/Top%205%20player%20of%20the%20Match.png)

6. **Toss Winner vs Match Winner**

   ![Toss Winner vs Match Winner](graph/Toss%20Winner%20vs%20Match%20Winner.png)

7. **Top 10 Run Scorers in IPL**

   ![Top 10 Run Scorers](graph/Top%2010%20run%20scorers%20in%20IPL%20%282008-2020%29.png)

8. **Top 10 Wicket Takers**

    ![Top 10 Wicket Takers](graph/Top%2010%20wicket%20takers.png)

9. **Top 10 Players with Most Sixes**

    ![Top 10 Players with Most Sixes](graph/Top%2010%20Players%20with%20Most%20Sixes.png)

10. **Average Runs per Match by Team**

     ![Average Runs per Match by Team](graph/Average%20Runs%20per%20Match%20by%20Team.png)

---

## 💡 Key Insights**

The analysis produced several notable findings from the 2008–2020 IPL data:
- Mumbai Indians recorded the highest number of wins with 120 victories during the analyzed period.
- V Kohli recorded the highest total runs with 5,878, followed by SK Raina with 5,368 runs.
- SL Malinga recorded the highest number of wickets with 188, followed by DJ Bravo with 175 wickets.
- CH Gayle recorded the highest number of sixes with 349.
- The toss winner won 418 out of 816 matches (51.23%), while losing 398 matches (48.77%). This indicates only a small difference between winning and losing after winning the toss.
- Teams chose to field first in 496 matches (60.78%), compared with 320 matches (39.22%) where they chose to bat first.
- Eden Gardens hosted 77 matches, making it the most frequently used venue in the analyzed dataset.
- The highest individual team innings score in the analysis was 263 runs by Royal Challengers Bangalore.
- Gujarat Lions recorded the highest average runs per match at approximately 161.87, based on the analyzed data.

---

## 🎯 Conclusion

This project demonstrates how Python and SQL can be used to analyze real-world sports data and extract meaningful insights.

The project involved:

- Cleaning and validating match and ball-by-ball datasets.
- Performing feature engineering by extracting the IPL season.
- Conducting match-level and delivery-level Exploratory Data Analysis.
- Using Pandas and SQL to answer analytical questions.
- Creating visualizations using Matplotlib.
- Comparing team and player performance using multiple metrics.
- Communicating findings through data-driven insights.
- 
Overall, the project provided practical experience in data cleaning, exploratory data analysis, SQL, Python, data visualization, and analytical thinking while working with a real-world sports dataset.

---

## 📬 Contact

If you have any suggestions or feedback regarding this project, feel free to connect with me on LinkedIn.
Abhishek Rawat
- LinkedIn: https://www.linkedin.com/in/abhishek-rawat-790132380/
- GitHub: https://github.com/AbhishekRawat-21
