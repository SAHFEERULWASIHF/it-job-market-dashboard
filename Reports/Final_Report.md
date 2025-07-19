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
   - US - we can clearly see US is hiring more tech employees
  
     
     ![High Demand Locations](figures/job%20location.png)

4. **Best Jobs For Freshers**

   - Data Analyst, Data Scientist, Data Engineer
   - Becouse these are the jobs giving good median salary with good amount of openings

     ![Entry level job median salary with job openings](figures/Entry%20level%20job%20median%20salary%20with%20job%20openings.png)
     
5. **Best Jobs For Mid Experienced**

   - Data Scientist, Data Engineer, Machine Learning Engineer, Research Scientist, Analytics Engineer
   - Becouse these are the jobs giving good median salary with good amount of openings

     ![Entry level job median salary with job openings](figures/Mid%20level%20job%20median%20salary%20with%20job%20openings.png)
     
6. **Best Jobs For Seniors**

   - Machine Learning Engineer, Data Scientist, Data Engineer, Data Analyst
   - Becouse these are the jobs giving good median salary with good amount of openings

     ![Entry level job median salary with job openings](figures/Senior%20level%20job%20median%20salary%20with%20job%20openings.png)
     
7. **Best Jobs For Experts**

   - Data Engineer
   - Becouse these are the jobs giving good median salary with good amount of openings

     ![Entry level job median salary with job openings](figures/Expert%20level%20job%20median%20salary%20with%20job%20openings.png)


---

## 📌 Dashboard Overview

📁 Path: `/Dashboard/it-job-market-dashboard.pbix`  
🖼️ Power BI Dashboard Preview:

![Power BI Dashboard Preview](../Dashboard/PowerBI%20Dashboard.png)

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

## ✅ Conclusion

The IT Job Market Intelligence Dashboard offers a strategic view of Global tech job market. From entry-level roles to expert positions, it uncovers:

- High-demand job titles

- Compensation trends by experience

- Location and remote work opportunities

These insights empower fresh graduates, career switchers, and hiring managers with data-driven decision-making capabilities. This project not only boosts technical and analytical skills but also enhances storytelling through visuals—a key differentiator in the data field.

## ✅ Future Improvements

- Add clustering (e.g, job titles grouped by salary + experience)
- Automate monthly data refresh using scheduled scripts
- Integrate Glassdoor or Indeed API (optional for enrichment)

---

## 👤 Author

**Name:** F Sahfeerul Wasihf  
**GitHub:** [@SAHFEERULWASIHF](https://github.com/SAHFEERULWASIHF)  
**LinkedIn:** [www.linkedin.com/in/sahfeerul-wasihf](https://www.linkedin.com/in/sahfeerul-wasihf)  
**Email:** wasihfwork@gmail.com
