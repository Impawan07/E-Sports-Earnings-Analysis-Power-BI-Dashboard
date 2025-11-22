# **E-Sports Earnings Analysis – Power BI Dashboard**

A complete, end-to-end analytics project exploring global esports prize pools, player participation, tournament activity, and country-level performance using Power BI (Web Version).

---

##  **Project Overview**

This project analyzes **94,000+ esports records** covering games, countries, tournaments, and players.  
 All visuals were created **without DAX** using **Power BI Service (Browser Version)**, making the project accessible to beginners and compatible with online-only BI workflows.

The dashboard consists of **6 interactive pages**, each focused on a key dimension of global esports analytics.

---

##  **Dataset Summary**

**Dataset Used:** `ESport_Earnings`  
 **Rows:** 94,116  
 **Columns:** 9

| Column | Description |
| ----- | ----- |
| GameName | Name of the esports game |
| Genre | Game genre (MOBA, FPS, Battle Royale…) |
| IdNo | Unique row identifier |
| PlayerNo | Total number of players |
| Releaseyear | Game's release year |
| Top\_Country | Country contributing the most prize money |
| Top\_Country\_Earnings | Prize money contributed by top country |
| TotalMoney | Total prize pool awarded by game |
| TournamentNo | Number of tournaments conducted |

---

##  **Dashboard Structure (6 Pages)**

###  **Page 1 – Global Overview**

* KPI cards: Total Earnings, Total Players, Total Games, Total Tournaments

* Donut: Country-wise prize distribution

* Bar Chart: Top-earning games

* Slicers: Game, Country, Year

**Insights**

* USA, China, and Korea dominate the prize pools

* Top 10 games hold over 70% of global earnings

---

###  **Page 2 – Yearly Trends**

* Total earnings trend

* Games released per year

* Player participation trend

* Tournaments per year

* Year slicer

**Insights**

* Esports growth accelerates post-2015

* Tournament activity drives player participation

---

###  **Page 3 – Player-Level Analysis**

* Top 10 players by earnings

* Players by country

* Earnings leaderboard table

**Insights**

* Earnings highly concentrated among elite players

* USA, China, Denmark lead in producing top athletes

---

###  **Page 4 – Game & Tournament Insights**

* Scatter chart: Tournament count vs earnings vs avg prize

* Bar: Top games by tournament count

* Heatmap: Game prize pools by year

* Table: Top tournaments by prize money

**Insights**

* Dota 2 & CS:GO dominate global earnings

* Peak prize years: 2015–2020

---

###  **Page 5 – Country Analysis**

* Treemap: Country-wise earnings

* Bar chart: Player participation

* Donut: Country share of prize pool

* Insight box

**Insights**

* USA remains \#1 in players & earnings

* Emerging esports markets: Brazil, Vietnam, Saudi Arabia

---

###  **Page 6 – Summary & Recommendations**

Includes 4 text sections:

* Project Overview

* Key Insights Summary

* Recommendations

* Conclusion

**Key Recommendations**

* Invest in top-performing games (Dota 2, CS:GO, LoL)

* Expand tournaments in emerging regions

* Use year-wise trend analysis to optimize event calendars

---

##  **Key Takeaways**

* **Prize pools are highly concentrated** among top games & regions

* **Yearly growth trends** reveal the maturing esports ecosystem

* **Tournament frequency correlates strongly** with earnings

* **Country-level disparities** highlight strategic expansion areas

* **Player participation mirrors industry growth cycles**

---

##  **Tools Used**

* Power BI Service (web)

* Power Query (basic usage)

* CSV dataset (Kaggle/ESports dataset)

* No DAX or calculated tables used

---

## 

## 

## 

##  **Project Goal**

This interactive dashboard helps:

* Analysts  
* Esports organizations

* Publishers

* Investors

* Data science learners

…gain actionable insights into global esports performance.

---

##  **Files Included**

 E-SPORTS-POWER-BI  
│  
├── README.md         (This file)  
├── dashboard.pdf     (Exported Power BI PDF)  
├── screenshots/      (Dashboard snapshots)  
└── dataset.csv       (Dataset used in the model)

