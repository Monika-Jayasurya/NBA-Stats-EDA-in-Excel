🏀 NBA Player Stats – Exploratory Data Analysis

📌 Project Overview

This project explores an NBA Player Statistics dataset from Kaggle using Google Sheets. The analysis includes Exploratory Data Analysis (EDA), data visualization, and advanced analytics to uncover player performance trends, team comparisons, and key insights into offensive/defensive efficiency.

📂 Dataset Overview

The dataset contains player-level information with the following fields:

Player Info: Name, Team, Position, Age, Games Played (GP), Minutes per Game (MPG)
Performance Stats: PPG (Points per Game), RPG (Rebounds per Game), APG (Assists per Game), SPG (Steals), BPG (Blocks), TO% (Turnovers)
Shooting Stats: FT%, 2P%, 3P%, eFG%, TS%
Advanced Metrics: USG% (Usage %), ORtg (Offensive Rating), DRtg (Defensive Rating), VI (Versatility Index), P+R+A (Points + Rebounds + Assists)

🔎 Exploratory Data Analysis

Team Composition
Teams with most players: BOS, MIN, ORL (15 players each).

Team Averages
Calculated team-wise averages for PPG, RPG, APG.
Example: LAL had one of the highest averages – 11.83 PPG, 4.58 RPG, 2.72 APG.

High-Impact Players
Identified players with PPG > 20 and APG > 5.

Key players: LeBron James, Luka Dončić, Nikola Jokić, Joel Embiid, Jayson Tatum, Shai Gilgeous-Alexander, Jalen Brunson, etc.
Usage Percentage (USG%)
Highest: Indiana Pacers (23.54)
Lowest: Boston Celtics (15.57)

📊 Data Visualization

Player Distribution per Team – Bar chart of roster sizes.

[![Alt text]([[image-url](https://github.com/Monika-Jayasurya/NBA-Stats-EDA-in-Excel/issues/1)](https://private-user-images.githubusercontent.com/202952510/489501744-25073fd8-cad9-4f1f-b981-f0df24437a08.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTc5Mzc2NzcsIm5iZiI6MTc1NzkzNzM3NywicGF0aCI6Ii8yMDI5NTI1MTAvNDg5NTAxNzQ0LTI1MDczZmQ4LWNhZDktNGYxZi1iOTgxLWYwZGYyNDQzN2EwOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwOTE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDkxNVQxMTU2MTdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NGY3NTM1NWY2MTU3Y2VmOGRhNjE5YzlmODk3MzJjYTBiMGM2NTMwZWZiYjdiNTUxM2JmNzdjNGFkODE1MGRiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.ZAQyXLbGAwW8hvgxyagI-Ml2hXtd2Hb1FDJ7YBmOx5o))](https://private-user-images.githubusercontent.com/202952510/489501744-25073fd8-cad9-4f1f-b981-f0df24437a08.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTc5ODg5MzAsIm5iZiI6MTc1Nzk4ODYzMCwicGF0aCI6Ii8yMDI5NTI1MTAvNDg5NTAxNzQ0LTI1MDczZmQ4LWNhZDktNGYxZi1iOTgxLWYwZGYyNDQzN2EwOC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwOTE2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDkxNlQwMjEwMzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wNWFhZmIyZTNjNjRkMTE0ZWM5YjYxZWFkZjlmZGY4YzliZWViMWRmOGU1NGFkZDFjYjJjYzU2M2JmNGU1MGI5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.X_Ion5KXqmZhMOcK9pHrp7hzw-K9fZMNEOd1ENea-sk)

Position Distribution – Count of Guards, Forwards, and Centers.
Team Performance Comparison – Average PPG, RPG, APG across teams.
Scoring Efficiency – Scatter plot of PPG vs MPG to analyze scoring impact relative to playing time.

📈 Advanced Data Analytics

Offensive & Defensive Rating
Calculated average ORtg and DRtg per team.
Example: NYK had highest ORtg (113.39), CLE had highest DRtg (108.73).

Impact of Age on Performance
Analyzed PPG, RPG, APG across age groups.
Found peak performances in ages 25–29 and veterans like LeBron James (age 38–39) still showing elite output.
Top Combined Performer (P+R+A)
Nikola Jokić – 50.8 combined average (Points + Rebounds + Assists).

Top Players by Position (based on PPG)

Center: Joel Embiid – 33 PPG
Forward: LeBron James – 27.8 PPG
Guard: Jalen Brunson – 32.4 PPG

🚀 Key Insights

Teams differ significantly in usage style (IND vs BOS).
Nikola Jokić dominates all-around metrics, confirming his MVP-level impact.
Young stars (23–26) deliver high scoring bursts, while veterans (30+) still maintain elite performance.
Team-level analysis shows how roster composition and playstyle reflect in metrics like ORtg, DRtg, and USG%.

🛠️ Tools Used

Google Sheets – Data cleaning, pivot tables, visualization

Excel – Cross-verification and charting

(Future scope: Tableau, Power BI, Python for deeper analytics)
