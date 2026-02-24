# 🏀 Cleveland Cavaliers Ticket Sales Analytics: 2025 Hackathon

## 📌 Executive Summary
The objective was to analyze historical single-game ticket sales, define standard pacing curves, and build a predictive "Command Center" dashboard to alert executives when a game is in danger of missing its sales goals. 

Our target game for prediction: **Nov 2, 2025 - Cavaliers vs. Atlanta Hawks (Tier D)**.

## 📊 The Dashboard: Intervention Command Center
<img width="1361" height="762" alt="Dashboard" src="https://github.com/user-attachments/assets/ab3c82b3-b840-4f49-8789-c9127d53ab85" />

## 💡 Key Findings & The "Danger Zone"
By comparing historical "Winners" (games that hit the 2,500 ticket goal) against "Losers" (games that missed the goal), we identified critical intervention thresholds:
* **The Yellow Alert (45 Days Out):** Pacing falls below 600 cumulative tickets. Requires "soft interventions" (value-adds, food & beverage credits).
* **The Red Alert (30 Days Out):** Pacing falls below 850 cumulative tickets. This is the point of no return. Requires aggressive "hard interventions" (volume bundles, exclusive access plays).

## 🚨 The Target Game Forecast (Cavaliers vs. Hawks)
Currently, at **20 days out**, the Hawks game has only sold **398 tickets**. 
* **The Projection:** Based on historical Tier D pacing curves, the game is pacing to finish at approximately **946 total tickets**, missing the 2,500 goal by over 1,500 tickets.
* **The Action Plan:** Because this game has crossed the 30-Day "Red Alert" threshold, we recommend immediate **Volume Plays** (e.g., Youth League Family 4-Packs) and **Access Plays** (e.g., linking Hawks ticket purchases to presale access for future Tier A+ games) to drive urgency without gutting the single-ticket face value.

## 📂 Repository Contents
* `Single_Game_Ticket_Analysis.ipynb`: Python code used for initial data cleaning, exploratory data analysis (EDA), and calculating the specific projection formulas.
* `Cavs_Command_Center.twbx`: The packaged Tableau workbook containing the interactive dual-axis forecasting dashboard and pacing curves.
* `2025 Sports Business & Analytics Night - Hackathon Data Set.csv`: The raw dataset provided for the hackathon.
* `Hawks_Forecast_Chart_Data.csv`: The generated forecast data used to plot the exact trajectory of the target game.

## 🛠️ Tools Used
* **Python (Pandas, Matplotlib, Seaborn):** For data aggregation, pacing analysis, and forecast modeling.
* **Tableau:** For executive dashboarding, utilizing Level of Detail (LOD) expressions, running total Table Calculations, and Data Blending (Dual Axis). 

## 🚀 How to Run
1. View the Python analysis directly by opening the `.ipynb` file in GitHub.
2. To interact with the dashboard, download the `.twbx` file and open it using Tableau Desktop or Tableau Reader.
