# T20 Cricket World Cup 2022 Data Analysis
![Cover](https://i.postimg.cc/43LVPQyx/T20-World-Cup-2022-Australia-England.jpg)

## Project Overview
This project aims to analyze data from the Men's T20 Cricket World Cup 2022 to identify the best 11 players based on performance and selection criteria. Additionally, a Power BI Dashboard was created to review and compare players' performances visually.

## Problem Statement

### Selection Criteria:
#### Team Performance:
- The team should be able to score at least 180 runs on average.
- The team should be able to defend 150 runs on average.

#### Player Roles and Criteria:
1. **Openers:**
   - Batting Average > 30
   - Strike Rate > 140
   - Innings Batted > 3
   - Boundary % > 50
   - Batting Position < 4

2. **Middle Order:**
   - Batting Average > 40
   - Strike Rate > 125
   - Innings Batted > 3
   - Avg. Balls Faced > 20
   - Batting Position > 2

3. **Finishers/Lower Order Anchors:**
   - Batting Average > 25
   - Strike Rate > 130
   - Innings Batted > 3
   - Avg. Balls Faced > 12
   - Batting Position > 2
   - Innings Bowled > 1

4. **All-Rounders:**
   - Batting Average > 15
   - Strike Rate > 140
   - Innings Batted > 2
   - Batting Position > 4
   - Innings Bowled > 2
   - Bowling Economy < 7
   - Bowling Strike Rate < 20

5. **Specialist Fast Bowlers:**
   - Innings Bowled > 4
   - Bowling Economy < 7
   - Bowling Strike Rate < 16
   - Bowling Style = "Fast"
   - Dot Ball % > 40

---

## Data Pipeline
### 1. **Data Source**
- **Website Scraped:** [ESPN Cricinfo](https://www.espncricinfo.com)
- **Player Career Data:** Scraped using BrightData

### 2. **Data Collection**
- Used **Beautiful Soup** library in Python for web scraping.
- Converted JSON files into DataFrames using **Jupyter Notebook**.
- Exported cleaned DataFrames to CSV files for further analysis in Power BI.

### 3. **Data Transformation**
- Initial data cleaning performed using **Pandas** (e.g., correcting player names, handling missing values, linking match IDs).
- Transformed the final data for dashboarding using **Power Query** in Power BI.

### 4. **Data Modelling**
- Connected datasets using primary keys (e.g., match IDs).
- Created measures, calculated columns, and parameters for analysis using **DAX**.

### 5. **Reports**
- ## Dashboard Overview
Here is a preview of the Power BI dashboard:
- Openers
![Openers](https://i.postimg.cc/NfzDGYB0/t20-wc-dashboard-page-0001.jpg)

- Middle Order
![Middle Order](https://i.postimg.cc/Hk82VKk9/t20-wc-dashboard-page-0002.jpg)

- Finisher
![Finisher](https://i.postimg.cc/fLDjqRj8/t20-wc-dashboard-page-0003.jpg)

- All Rounders
![All Rounders](https://i.postimg.cc/7hL1DtR7/t20-wc-dashboard-page-0004.jpg)

- Fast Bowlers
![Fast Bowlers](https://i.postimg.cc/d3S20mMf/t20-wc-dashboard-page-0005.jpg)

- Best 11
![Best 11](https://i.postimg.cc/bvjQdwMq/t20-wc-dashboard-page-0006.jpg)

- Player Details
![Player Details](https://i.postimg.cc/MT6Vbrq4/Screenshot-104.png)

---

## Tools, Software, and Libraries
1. **Jupyter Notebook**
2. **Python**
3. **Pandas**
4. **Web Scraping**
5. **Beautiful Soup**
6. **Power Query Editor**
7. **Power BI**
8. **Anaconda Navigator**

---

## Dashboard Highlights
1. **Key Performance Indicators (KPIs):** Metrics for batting and bowling performances.
2. **Role-Based Player Analysis:** Openers, middle-order, finishers, all-rounders, and bowlers.
3. **Team Comparisons:** Team strengths and weaknesses based on average scores and economy rates.
4. **Interactive Visuals:** Filters for player roles, teams, and matches.

---

## Project Insights
- **Selection Methodology:** Criteria for each role ensured the best players were chosen for a balanced team.
- **Key Findings:** 
   - Openers with high strike rates consistently provided strong starts.
   - All-rounders contributed significantly to both batting and bowling metrics.
   - Specialist bowlers played a critical role in defending low scores.

---

## Future Improvements
- Automate data scraping for real-time updates.
- Integrate advanced statistical models for performance prediction.
- Expand the dashboard to include historical comparisons.

---

## Author
Kazi Mahmudul Hasan 
- GitHub: [Kazi-Mahmudul](https://github.com/Kazi-Mahmudul)  

Feel free to explore the project and share your feedback!
