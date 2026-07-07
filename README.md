# 🏏 Cricket Performance Analytics Dashboard

An interactive **Power BI dashboard** for analyzing cricket player performance using batting and bowling statistics. The dashboard enables users to explore player performance across different match formats and years through interactive filters, KPIs, and visualizations.

---

## 📌 Overview

This project provides a comprehensive analysis of cricket players by combining batting and bowling data into a single interactive Power BI report.

Users can:

* Analyze individual player performance
* Filter statistics by year and match type
* Compare batting and bowling performances
* Explore player statistics using interactive charts and KPI cards

---

## 📂 Dataset Information

The dashboard is built using three structured cricket datasets that capture player batting, bowling, and match information.

| Dataset       | Description                                                                                                                                        |    Records |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------: |
| **bat.csv**   | Individual batting statistics including runs, balls faced, strike rate, fours, sixes, batting average, dismissal details, and innings information. | **52,492** |
| **ball.csv**  | Bowling statistics including wickets, overs, maidens, economy rate, bowling average, strike rate, and runs conceded.                               | **36,149** |
| **match.csv** | Match-level information including match date, match type, series, scorecard ID, venue, and match results.                                          |  **6,199** |

---

## 🚀 Features

### 📄 Dashboard 1 – Overall Performance

* Total Batting Runs
* Total Balls Faced
* Batting Strike Rate
* Batting Innings
* Half Centuries (50s)
* Centuries (100s)
* Runs by Year
* Runs by Match Type
* Runs by Opposition
* Fours vs Sixes Comparison
* Batting Performance Summary

---

### 📄 Dashboard 2 – Bowling Performance

* Total Wickets
* Bowling Economy
* Bowling Average
* Bowling Strike Rate
* Maiden Overs
* Bowling Innings
* Wickets by Year
* Wickets by Match Type
* Wickets by Opposition
* Economy Trend

---

### 📄 Dashboard 3 – Player Analysis

* Dynamic Player Selection
* Year Filter
* Match Type Filter
* Player Profile (Photo, Role, Country)
* Total Runs
* Highest Score
* Strike Rate
* Half Centuries
* Centuries
* Wickets
* Best Bowling Figures
* Batting Performance Charts
* Bowling Performance Charts
* Performance Summary Table

---

## 📊 Visualizations

* KPI Cards
* Line Charts
* Clustered Column Charts
* Bar Charts
* Donut Charts
* Slicers
* Tables
* Dynamic Player Profile

---

## 📂 Data Model

The report is built using a star-schema style model consisting of:

* **bat** – Batting statistics
* **ball** – Bowling statistics
* **match** – Match details
* **DimDate** – Date dimension
* **DimPlayer** – Player dimension
* **IndiaPlayers** – Indian player lookup
* **MainIndiaPlayers** – Selected featured Indian players
* **PlayerInfo** – Player profile information

---

## 📈 Key Metrics

### Batting

* Total Runs
* Highest Score
* Batting Average
* Strike Rate
* Innings
* 50s
* 100s
* Fours
* Sixes

### Bowling

* Wickets
* Economy Rate
* Bowling Average
* Bowling Strike Rate
* Best Bowling Figures
* Maiden Overs

---

## 🛠 Technologies Used

* Microsoft Power BI Desktop
* Power Query
* DAX
* Data Modeling
* Git & GitHub

---

## 📁 Project Structure

```text
Cricket-Performance-Analytics-Dashboard/
│
├── Cricket_Performance_Analytics_Dashboard.pbix
├── Dataset/
│   ├── bat.csv
│   ├── ball.csv
│   └── match.csv
├── Images/
└── README.md
```

---

## 💡 Key Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Measure Development
* Interactive Dashboard Design
* Sports Analytics
* Business Intelligence
* Data Visualization

---

## 🎯 Future Improvements

* IPL Player Analysis
* Team Comparison Dashboard
* Venue Analysis
* Partnership Analysis
* Live Cricket API Integration
* Predictive Performance Analytics

---

## 👨‍💻 Author

**Matta Prashanth Reddy**

* GitHub: https://github.com/mattapr
* LinkedIn: https://www.linkedin.com/in/prashanth-reddy-matta-771971324

---

## ⭐ If you found this project useful

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub. Your support is greatly appreciated and helps others discover the project.
