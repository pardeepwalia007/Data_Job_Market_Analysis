## 📊 Data Job Market Analysis

### 🔎 Overview

This project analyzes the data job market (2020–2025) by scraping and cleaning job postings, normalizing attributes, and creating insights into demand, salary trends, and required skills.
The goal: help job seekers and analysts understand which skills are most in demand, how salaries vary, and how the market evolves year over year.

⸻
🛠️ Tools & Technologies
	•	Python (Pandas, NumPy, Matplotlib, Seaborn)
	•	SQL (MySQL for queries, window functions, joins, aggregations)
	•	Tableau (dashboards for insights & visual storytelling)
	•	Web Scraping (Adzuna API, LinkedIn Selenium scraping)


⸻
📑 Datasets
	•	Raw Data: ~22,000+ job postings (2020–2025)
	•	Sources: APIs + Web scraping (Adzuna, LinkedIn)
	•	Columns (normalized):
	•	Job title
	•	Skills mentioned
	•	Salary (standardized to annual)
	•	Location (cleaned by regex for provinces/states)
	•	Remote/On-site flag
	•	Posted year

Note: CSV datasets are excluded via .gitignore to keep repo clean.

⸻
🔑 Key Insights & KPIs
	•	📈 Skill Demand Over Time → which tools (Python, SQL, Tableau, AWS, etc.) grew most in demand.
	•	💰 Salary Trends → median and weighted salaries by role, location, and seniority.
	•	🌍 Remote Work Share → how remote jobs evolved since 2020.
	•	🔄 Year-over-Year Growth → growth rate of job postings for different analyst roles.
	•	🎯 AI/Cloud Mentions → % of postings requiring AI/ML or cloud tools (AWS, Azure, GCP).

⸻

📊 Dashboards & Visuals
	•	Tableau dashboards (notebook exports + GitHub screenshots):
	•	Skill Trends by Year
	•	Salary Distribution by Role
	•	Remote vs On-site Jobs
	•	Top 10 Skills by Market Share
	•	YoY Growth Index (2020 = 100)
  
Tableau Dashboard links:
https://public.tableau.com/app/profile/pardeep.walia/viz/DataJob_analysis_5/DataRolesSkillandPay
