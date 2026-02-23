# 🏏 IPL_Analysis_P1

![Python](https://img.shields.io/badge/Python-3.x-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Domain](https://img.shields.io/badge/Domain-Sports%20Analytics-purple)

---

## 📌 Project Overview

IPL_Analysis_P1 is a Data Engineering and Analytics project focused on analyzing Indian Premier League (IPL) match data.

This project builds a complete ETL pipeline using Python and MySQL to clean, transform, store, and analyze cricket match data to generate meaningful insights and dashboards.

---

## 🎯 Objectives

- Analyze team performance across seasons
- Evaluate player performance metrics
- Measure win percentages and dominance
- Identify match trends and patterns
- Build analytical dashboards for insights

---

## 🏗️ ETL Architecture

CSV Files (matches.csv, deliveries.csv, players.csv)
↓
Python ETL (IPL_Analysis.ipynb)
- Remove Duplicates
- Handle Missing Values
- Standardize Data
- Apply Business Rules
↓
Cleaned Data Tables (MySQL)
↓
SQL Analytics
↓
Matplotlib Dashboards


---

## 📂 Repository Structure

IPL_Analysis_P1/
│
├── IPL_Analysis.ipynb
├── IPL ANALYSIS.docx
├── IPL Analysis Dashboard_Problem_Statements.txt
├── matches.csv
├── deliveries.csv
├── players.csv
├── README.md
└── .ipynb_checkpoints/

---

## 📊 Data Files Used

- `matches.csv` → Match-level information
- `deliveries.csv` → Ball-by-ball delivery data
- `players.csv` → Player details

---

## 📊 Dashboards Implemented

### 🔹 Team Performance
- Team with highest wins
- Wins by venue
- Season-wise dominance

### 🔹 Match Insights
- Average runs per match
- Matches with "No Result"
- Home vs Away analysis

### 🔹 Player Analytics
- Runs distribution per match
- Wickets per match
- High-scoring matches

### 🔹 Business KPIs
- Top 5 teams by win percentage
- Match outcome predictability
- Venue impact analysis

---

## 🛠️ Tech Stack

| Category | Tools Used |
|----------|------------|
| Programming | Python |
| Notebook | IPL_Analysis.ipynb |
| Data Processing | Pandas |
| Visualization | Matplotlib |
| Database | MySQL |
| Domain | Sports Analytics |

---
## Visualization

  <img width="563" height="475" alt="image" src="https://github.com/user-attachments/assets/b2a87d1c-14af-432d-b607-a0cb9cf6a738" />

<img width="833" height="545" alt="image" src="https://github.com/user-attachments/assets/485a43f2-6be4-41bd-a2e0-a807de1fca0e" />

<img width="554" height="453" alt="image" src="https://github.com/user-attachments/assets/b3ffe54e-92c6-4b96-9fae-0b1694afc59a" />

<img width="554" height="475" alt="image" src="https://github.com/user-attachments/assets/4458ffc8-8177-4162-bb65-f8aab9f772be" />

<img width="495" height="409" alt="image" src="https://github.com/user-attachments/assets/daf382f3-da73-4931-993b-24360ee5ae21" />

<img width="564" height="436" alt="image" src="https://github.com/user-attachments/assets/d3e85172-2dc7-49b9-b74c-58cb8b3e8b68" />

<img width="571" height="453" alt="image" src="https://github.com/user-attachments/assets/3632f29c-3617-4f06-8b17-c71dca3987f5" />

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/ee2e8af2-6ed7-4e18-9900-f334abe7db75" />

<img width="389" height="409" alt="image" src="https://github.com/user-attachments/assets/2ee1539b-1aa6-4318-8186-162cd6118674" />

<img width="576" height="503" alt="image" src="https://github.com/user-attachments/assets/e1a6f7c8-1019-4019-b361-359eb02c2a47" />

## 🚀 How to Run

1. Clone the repository


git clone https://github.com/SyedMadhu/IPL_Analysis_P1.git
cd IPL_Analysis_P1


2. Install required libraries

pip install pandas matplotlib seaborn mysql-connector-python


3.Open Jupyter Notebook

jupyter notebook IPL_Analysis.ipynb

## 📈 Key Insights

Identified most dominant IPL teams

Analyzed venue impact on match results

Measured team win percentages

Evaluated player performance trends

## 🔮 Future Enhancements

Deploy dashboards using Streamlit

Add Machine Learning match prediction model

Integrate Power BI dashboard

Automate ETL pipeline

## 👨‍💻 Author
Syed Madhu
