#  ODI Batting Performance Analysis – Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on conducting a comprehensive Exploratory Data Analysis (EDA) of *ODI (One Day International) batsmen performance data*.  
The main goal is to uncover meaningful patterns, trends, and insights that define player effectiveness and impact in limited-overs cricket.  
The analysis goes beyond surface-level statistics like total runs or averages and explores deeper performance indicators such as consistency, strike rate trends, and boundary frequency.

---

##  Data Collection
- Data was *web scraped* from *Cricbuzz* using Python scripts.  
- Extracted detailed information of *10,399 players* across different teams.  
- Focused specifically on *ODI career statistics* of players.

---

##  Data Cleaning & Preparation
- Removed *duplicates* and players with *0 matches* or *0 innings*.  
- Filtered data to include only players who played *50 or more matches* for meaningful insights.  
- Standardized and formatted columns for consistency.  
- Final dataset included columns such as:  
  Player Name, Team, Matches, Innings, Runs, Balls Faced, Strike Rate, Average, 100s, 50s, 200s, 4s, 6s, Highest Score, etc.

---

## Analysis Performed
### 🔸 Univariate Analysis
- Distribution of runs, strike rate, and averages.  
- Most consistent and top-performing batsmen.  
- Strike rate vs. runs comparison.

### 🔸 Bivariate Analysis
- Relationship between runs and strike rate.  
- Correlation between matches played and centuries scored.  
- Average vs. boundaries (4s & 6s) contribution.

### 🔸 Multivariate Analysis
- Impact of strike rate, matches, and consistency on total runs.  
- Identifying outliers and exceptional performances.

---

##  Key Insights
- Players with higher strike rates often contribute more impactful innings than those with higher averages alone.  
- Certain players maintain consistent scoring patterns even after long careers.  
- The number of matches played strongly correlates with the number of 100s and 50s scored.  
- Modern-era players show a trend of increasing strike rates over time.

---

##  Tools & Technologies
- *Python*
- *Pandas, **NumPy*
- *Matplotlib, **Seaborn*
- *BeautifulSoup / Requests* (for Web Scraping)
- *Jupyter Notebook*

---

## 🎯 Objective
To analyze ODI batting statistics and reveal data-driven insights into player effectiveness, highlighting key performance patterns and indicators that define success in limited-overs cricket.

---
