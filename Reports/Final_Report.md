# 🧠 IT Job Market Intelligence Dashboard – United States

## 📌 Project Title
**IT Job Market Intelligence Dashboard for Entry-Level to Senior Roles in the United States**

---

## 🎯 Objective

To explore, analyze, and visualize the IT job market in the US using real-world salary data. The goal is to understand hiring patterns, salary trends, and the distribution of job roles across experience levels to help job seekers and decision-makers gain strategic insights.

---

## 🧩 Project Features

- 📊 Median salary comparison across experience levels (Entry, Mid, Senior, Expert)
- 📍 Location-based distribution of job opportunities
- 🧑‍💼 Role-wise breakdown of hiring volume and salary ranges
- 📈 Trend analysis of job postings and role evolution

---

## 🗃️ Data Source

- **Kaggle – Global Tech Salary Dataset**  
  Source: [https://www.kaggle.com/datasets/yaaryiitturan/global-tech-salary-dataset](https://www.kaggle.com/datasets/yaaryiitturan/global-tech-salary-dataset)  
  Description: Contains job roles, salary, company size, location, remote status, and work experience level. Focused primarily on the US, but also includes global entries.

> All original and cleaned datasets are stored in the `/data/` folder.

---

## 🧰 Tools & Technologies

- **Python** (pandas, matplotlib, seaborn)
- **Power BI** for interactive dashboard visualization
- **Jupyter Notebooks** for analysis and transformation
- **CSV datasets** from Kaggle (no scraping used)

---

## 📊 Key Insights

1. **Highest Paying Roles (Median):**
   - AWS Data Architect
   - Data Operations Engineer
   - Machine Learning Software Engineer

2. **Salary Breakdown by Experience:**
   - Entry Level: ~$85,000
   - Mid Level: ~$118,000
   - Senior Level: ~$161,000+
   - Expert Level: ~$190,000+

3. **Top Hiring Location:**
   - US

4. **Remote Trends:**
   - Remote roles offer competitive salaries, especially in engineering-heavy jobs.

---

## 📌 Dashboard Overview

📁 Path: `/Dashboard/it-job-market-dashboard.pbix`  
🖼️ Preview:

![Power BI Dashboard Preview](Dashboard/PowerBI%20Dashboard.png)

Includes:
- Salary by job role and experience level
- Job distribution by location
- Role-based filters and slicers
- Visual comparisons of job count vs. salary

---

## 📁 Repository Structure

```
it-job-market-dashboard/
├── data/
│ ├── raw/ # Original downloaded CSVs
│ └── processed/ # Cleaned datasets for dashboard
├── notebooks/
│ ├── 1.Combining data.ipynb
│ └── 2.dashboard_preparation.ipynb
├── dashboard/
│ ├── it-job-market-dashboard.pbix
│ └── PowerBI Dashboard.png
├── reports/
│ ├── Final_Report.md
│ └── figures/ # Insight charts (e.g., job trends, salary maps)
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## 💼 Career Relevance

This project showcases:
- Real-world business analysis using tech salary data
- Power BI for executive-level dashboards
- Data transformation and insight generation using Python
- Strong understanding of US tech job market dynamics

Suitable for roles such as:
- **Data Analyst**
- **Business Intelligence Analyst**
- **HR/Workforce Analyst**

---

## ✅ Future Improvements

- Add clustering (e.g, job titles grouped by salary + experience)
- Automate monthly data refresh using scheduled scripts
- Integrate Glassdoor or Indeed API (optional for enrichment)

---

## 👤 Author

**Name:** F Sahfeerul Wasihf  
**GitHub:** [https://github.com/SAHFEERULWASIHF](https://github.com/SAHFEERULWASIHF)  
**LinkedIn:** www.linkedin.com/in/sahfeerul-wasihf(www.linkedin.com/in/sahfeerul-wasihf)  
**Email:** wasihfwork@gmail.com
