# South-African-Soccer-Dataset-SQL Player Analytics Dashboard ⚽

*Author:* Nomgqibelo Nkosi  
*Dataset:* ketro_sa_soccer_dataset_advanced  
*Tools Used:* SQL Server • Power BI • Miro  

A complete data analytics project that turns raw PSL player data into actionable insights for coaches, scouts, journalists, and fans.

## Project Goal
Answer real-world football questions using data:
- Who is leading the Golden Boot race?
- Which team has the youngest/oldest squad?
- Which players give the highest goal contribution?
- How do teams compare in attack, squad size, and experience?

## Repository Contents
 ├── sql/ │   └── sa_psl_analysis.sql              ← 20+ clean, commented SQL queries ├── visuals/ │   ├── PSL_Dashboard.pbix               ← Interactive Power BI file │   └── screenshots/                     ← PNG exports of all visuals ├── planning/ │   └── Miro_Board_Link.txt              ← Public Miro planning board ├── data/ │   └── dataset_description.md           ← Full column explanations └── README.md                            ← This file
 ## Key SQL Queries (inside sql/sa_psl_analysis.sql)
- Total players & unique teams
- Players per team (squad sizes)
- Top 10 goal scorers + goals-per-game
- Team total goals ranking
- Average age per team
- Veterans (>35) and wonderkids (<20)
- Goal contribution leaders (goals + assists)

## Data Visualisations (Power BI)
Open visuals/PSL_Dashboard.pbix → instant interactive dashboard!

*Dashboard Pages:*
1. League Overview  
2. Golden Boot Race  
3. Team Comparison (radar chart)  
4. Age & Experience Analysis  
5. Position Heatmap  

Static images also available in /visuals/screenshots

## Miro Planning Board
Full project planning (public link)

Contains:
- Dashboard wireframes

(Link also saved in /planning/Miro_Board_Link.txt)

## How to Run
1. *SQL Queries*  
   → Open in SSMS   
   → Database: Soccer_analysis_Db1  
   → Execute any query instantly

2. *Power BI Dashboard*  
   → Open .pbix file  
   → Refresh → everything updates live

## Dataset Columns (Key ones)
| Column           | Description                  |
|------------------|------------------------------|
| player_name      | Player full name             |
| team             | PSL club                     |
| position         | GK / DEF / MID / FWD         |
| age              | Player age                   |
| goals            | Total goals                  |
| assists          | Total assists                |
| matches_played   | Appearances                  |
| minutes_played   | Minutes on pitch             |

## Let’s Connect
- LinkedIn: [linkedin.com/in/nomgqibelonkosi](https://linkedin.com/in/nomgqibelonkosi)  
  

Feel free to fork, star, and build on this project!  
#PSL #SouthAfricanFootball #DataAnalytics #SportsAnalytic
