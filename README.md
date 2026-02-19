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
## visualization
<img width="563" height="475" alt="image" src="https://github.com/user-attachments/assets/f0a203d1-071d-4430-8553-ca37350a20a2" />

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/cd99292b-d67e-415b-802b-3339bdccfd83" />

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/9704fc50-5431-4257-9e8a-d3beba89ac83" />

<img width="571" height="453" alt="image" src="https://github.com/user-attachments/assets/8cf3fe63-f8a1-42e6-b86e-416f3e6f5f1e" />

<img width="568" height="433" alt="image" src="https://github.com/user-attachments/assets/08290be2-a05f-498a-bba0-8cba70ba46d8" />

<img width="543" height="433" alt="image" src="https://github.com/user-attachments/assets/f9aaeb6a-b19d-4abe-9fc6-f5eac2f84ea3" />

<img width="552" height="433" alt="image" src="https://github.com/user-attachments/assets/fc22bfe5-9f96-4085-a1f2-fff6fb1498d7" />

<img width="571" height="453" alt="image" src="https://github.com/user-attachments/assets/69d04ead-3fe0-4fd8-bfe1-2198ef2c9b1c" />

<img width="587" height="453" alt="image" src="https://github.com/user-attachments/assets/eb5a76ab-dde2-4e69-b233-54baa3d72654" />

<img width="571" height="449" alt="image" src="https://github.com/user-attachments/assets/7bc95917-86bc-48f3-8457-f21048c0f4bb" />

<img width="543" height="433" alt="image" src="https://github.com/user-attachments/assets/b16499ca-0ce9-4ebb-b7f8-6870cc40f925" />

<img width="563" height="503" alt="image" src="https://github.com/user-attachments/assets/0e72e183-b7d3-4c72-9c6c-9c65e4cd0f8b" />






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
