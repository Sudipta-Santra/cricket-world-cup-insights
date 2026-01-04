#  Cricket World Cup Insights – BI Dashboard

##  Project Overview
This project is a **Business Intelligence (BI) and Data Visualization dashboard** built using **Google Looker Studio**.  
It analyzes historical **Cricket World Cup data** to uncover insights related to team performance, player analytics, trends over time, and venue-based performance, with a special focus on the **Indian cricket team**.

The goal of this project is to transform raw cricket data into **interactive, meaningful visual insights**.

---

##  Project Objectives
- Analyze **country-wise performance** in Cricket World Cups  
- Study **player performance and discipline** (runs, wides, no-balls) 
- Identify **trends in high individual scores** over time  
- Visualize **geographical venues** where India performed best  

---

##  Tools & Technologies Used
- **Google Looker Studio** – BI & Dashboard creation  
- **Google Sheets** – Data staging and integration  
- **CSV Datasets** – Historical Cricket World Cup data  

---

##  Dataset Description

### 1️. matches.csv
Contains match-level information:
- Match ID  
- Season (World Cup year)  
- Teams  
- Venue and City  
- Match Winner  

### 2️⃣ deliveries.csv
Ball-by-ball match data:
- Batter and Bowler  
- Runs scored  
- Wide balls  
- No balls  
- Extras  

### 3️⃣ points_table.csv
Tournament performance summary:
- Team name  
- Matches played  
- Wins and losses  
- Points  

---

## 📊 Dashboard Structure

The project consists of **one Looker Studio report** with **three dashboard pages**:

### 📄 Page 1: Overview & Country Performance
- Total matches, teams, and World Cup editions  
- Country-wise wins (bar chart)  
- Points table summary  
- Country and season filters  

### 📄 Page 2: Player Analytics & Discipline
- Player-wise total runs  
- Wide balls and no balls analysis  
- Top run scorers  
- Player and batting team filters  


### 📄 Page 3: Geospatial Analysis – India Venues
- Geo map showing venues where India won matches  
- Venue-wise wins table  
- Filters for season and venue  

---

## 🔁 Data Processing & Modeling
- Each dataset was added as a **separate data source**
- **Google Sheets** was used as a staging layer for stability
- **Blended data** was used to join match and delivery data
- Calculated fields were created for:
  - Total runs (null-safe)
  - Discipline metrics (wides, no-balls)
- Filters were applied at page and chart levels

---

## 📈 Key Insights
- Certain countries consistently dominate World Cup tournaments  
- Player discipline significantly impacts performance  
- High individual scores have increased in recent World Cups  
- India performs strongly at specific venues  

---

## 🔗 Live Dashboard Link
👉 **Looker Studio Report:**  
*(https://lookerstudio.google.com/reporting/ca332cff-1f83-41ff-90f1-61aafd26fa21)*

---

## 🏁 Conclusion
This project demonstrates how Business Intelligence tools can be used to analyze large sports datasets and convert them into actionable insights.  
The interactive dashboard enables users to explore team performance, player statistics, trends, and venue-based outcomes effectively.

---

## 🚀 Future Enhancements
- Add bowling performance analytics  
- Include tournament-wise comparisons  
- Integrate real-time data sources  
