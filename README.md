# 🚕 Zuber Ride-Sharing Market Analysis in Chicago
The project analyzes taxi data to uncover patterns in ride behavior and evaluate the impact of external factors specifically weather, on ride frequency. The data comes from competitors of Zuber, a new ride-sharing company launching in Chicago. 

## 📝 Project Description
The project aims to extract insights from taxi ride data to help Zuber strategically enten the competitive Chicago ride-sharing market. Through SQL queries and python analysis, customer preferences were examined to identify leading taxi companies and drop-off hotspots, and test the hypothesis that bad weather affects ride durations. 
Focus was on:
  - Ride frequency across companies and neighborhoods.
  - Weather's affect on trip duration from the Loop to O'Hare.
  - Identifying peak business areas and key competitors.

## 📚 Table of Contents
  - Project Description
  - Project Structure
  - Features
  - Analysis Summary
  - Installation
  - How to Use
  - Credits

## 🗂️ Project Structure
```bash
zuber-chicago-analysis/
│
├── data/
│   ├── project_sql_result_01.csv
│   ├── project_sql_result_04.csv
│   └── project_sql_result_07.csv
│
├── sql_queries/
│   └── analysis_queries.sql
│
├── notebooks/
│   └── notebook.ipynb
│
├── README.md
```
## ✨ Features
- 🔍 Competitor Analysis: Identify the leading taxi companies based on ride frequency.
- 📍 Neighborhoods Hotspots: Discover Chicago neighborhoods with high ride activity.
- 🌧️ Weather Impact Analysis: Analyze the influence of bad weather on ride duration.
- 📊 Data Visualization: Create visual representations efor easier data interpretations. 
- 🧪 Hypothesis Testing: Statistical analysis to validate assumptions.

## 📈 Analysis Summary
### ✅ Top Taxi Companies
Flash Cab and Taxi Affiliation Services led in ride volume on Nov 15–16, 2017, suggesting they are major companies in the market.

### 📍Top Drop-Off Locations
The most popular drop-off neighborhoods include areas near downtown Chicago, highlighting potential demand hubs for Zuber.

### 🌧️ Weather vs. Ride Duration
Using hypothesis testing, we found that rainy Saturdays lead to significantly longer ride durations from the Loop to O'Hare International Airport. This insight could influence pricing models or driver allocation strategies.

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/zuber-chicago-analysis.git
   cd zuber-chicago-analysis
2. Install dependencies (requires Python 3.8+):
   ```bash
   pip install -r requirements.txt
3. Set up your SQL environment (SQLite or PostgreSQL recommended) and import the database schema if working locally.
4. Run analysis scripts via Jupyter or command line.

## ▶️ How to Use
  - Run the SQL queries in the /sql_queries/ folder to retrieve data for November 2017 taxi rides.
  - Load and analyze CSV results in Python using the provided Jupyter notebook or script.
  - Key files:
      - project_sql_result_01.csv: Company ride frequencies (Nov 15–16)
      - project_sql_result_04.csv: Drop-off neighborhood averages
      - project_sql_result_07.csv: Loop-to-O’Hare trips and weather conditions
  - View visualizations and hypothesis tests in the notebook.

## 🤝 Credits
This project was created as part of the TripleTen Data Science program. Special thanks to:
- Dataset Source: Practicum by Yandex, Chicago Public Data Portal
- TripleTen instructors and peers for ongoing support and feedback

## 🛡️ License
This project is licensed under the MIT License.
