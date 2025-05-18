🏏 IPL 2024 Season Statistics Dashboard – Power BI Mini Project

📌 Overview

This Power BI mini project presents a comprehensive dashboard summarizing the **IPL 2024 season**, combining both **batting** and **bowling** statistics. Designed to help cricket analysts, fans, and data enthusiasts uncover key insights, the dashboard includes metrics like **total runs, strike rate, boundaries, centuries, wickets, economy rates, and more**.

The project emphasizes **visual storytelling**, leveraging Power BI's interactivity and DAX for performance insights.

---

🧠 Key Features

- 🏏 Total team and player stats from IPL 2024 season
- 📈 Batting analysis: Runs, Strike Rate, 4s, 6s, Half-centuries, Centuries
- 🎯 Bowling analysis: Wickets, Economy Rate, Strike Rate, BBI, 4W, 5W
- 📊 Visual breakdown by team, player, and innings
- 💡 Interactive slicers for team and player filtering
- 🧮 DAX measures for Win Rate %, Minimum Economy Rate, and 5W Hauls

---

📊 Dashboard Highlights

|---------------------------|----------------|
| Total Runs (Batting)      | 25,000+        |
| Total Balls Faced         | 16,000+        |
| Total Players             | 167 (batting), 105 (bowling) |
| Total Sixes               | 1,260          |
| Total Boundaries          | 2,174          |
| Total Wickets             | 830            |
| 4-Wicket Hauls            | 10             |
| 5-Wicket Hauls            | 3              |
| Best Economy Rate         | 5.00           |

---

🛠️ Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **PDF Data Extraction**
- **Charts & Slicers**
- **Custom Measures & KPIs**

---

💻 DAX Measures Used

```DAX
-- Total 5W Hauls
Total 5W Hauls = SUM('seasonbowler2024'[5W])

-- Players with 5W
Players with 5W = CALCULATE(
    COUNTROWS('seasonbowler2024'),
    FILTER('seasonbowler2024', 'seasonbowler2024'[5W] >= 1)
)

-- Minimum Economy Rate
Min Econ = MIN('seasonbowler2024'[Econ])


---

📁 Files Included

📦 IPL-2024-PowerBI-Dashboard
 ┣ 📄 IPL 2024 Seasons Stat Summary.pdf
 ┣ 📄 seasonbowler2024.csv
 ┣ 📊 IPL_2024_Dashboard.pbix
 ┣ 📄 README.md

---


🚀 How to Use
Clone or download this repository.

Open the .pbix file in Power BI Desktop.

Explore visuals and filters to interact with the dataset.

Modify the visuals or add new ones using DAX measures.


---

📚 Learning Outcomes
Proficiency in using Power BI for sports data visualization

Hands-on experience in DAX calculations (percentage, min values, filters)

Understanding of interactive reporting using real-world cricket data


---

📷 Preview
Add screenshots of your Power BI dashboard here for visual reference.


---

📄 License
This project is licensed under the MIT License.


---

🙌 Acknowledgments
Special thanks to the Power BI community and cricket data enthusiasts whose insights inspired this dashboard.


---

🔗 Connect with Me
Feel free to connect and share feedback via LinkedIn.

#PowerBI #IPL2024 #DataAnalytics #MiniProject #SportsAnalytics #DAX #CricketStats #DashboardDesign #GitHubProjects


---

Let me know if you'd like a GitHub repo cover image, thumbnail, or screenshot layout guide to complete the project presentation!
