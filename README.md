# 💼 IT Job Market Intelligence Dashboard

Analyze and visualize salary trends, role distribution, and hiring patterns in the Global IT job market using real-world data. This project focuses on roles across experience levels—Entry, Mid, Senior, and Expert—and aims to uncover actionable insights for job seekers and HR professionals.

---

## 📌 Objective

- Understand salary distribution across Global IT roles
- Identify top-paying roles and high-demand locations
- Support freshers and career switchers with career decisions
- Demonstrate data analytics, visualization, and storytelling skills

---

## 🗃️ Dataset Used

| Source | Description |
|--------|-------------|
| [Kaggle – Global Tech Salary Dataset](https://www.kaggle.com/datasets/yaaryiitturan/global-tech-salary-dataset) | Real-world tech salary dataset focused on global job markets. Contains job titles, experience levels, work years, locations, salaries, and remote work status. |

📁 Located in `/data/raw/`

---

## 🧰 Tools & Tech Stack

- **Python**: pandas, matplotlib, seaborn
- **Power BI**: dashboarding and visuals
- **Jupyter Notebook**: data exploration and transformation
- **CSV**: structured dataset from Kaggle (no web scraping used)

---

## 📊 Dashboard Overview

📂 Path: `/dashboard/it-job-market-dashboard.pbix`  
🖼️ Screenshot: `PowerBI Dashboard`
![Power BI Dashboard Preview](Dashboard/PowerBI%20Dashboard.png)

### Dashboard Insights:
- 💰 Median salary by experience level and role
- 🌍 Job count by US state
- 🧑‍💼 Job role distribution
- 📈 Trend analysis of hiring activity

---

### 🔦 Highlight: Best Entry-Level Tech Jobs

📊 Fresher Job Title vs Median Salary (only roles with 30+ job openings):

![Entry level job median salary with job openings](Reports/figures/Entry%20level%20job%20median%20salary%20with%20job%20openings.png)

**Roles like Data Analyst and Data Engineer dominate entry-level opportunities with high median salaries.**


---

## 📁 Project Structure

```it-job-market-dashboard/
├── data/
│ ├── raw/ # Unprocessed CSVs
│ └── processed/ # Cleaned datasets for dashboarding
├── notebooks/
│ ├── 1.Combining data.ipynb
│ └── 2.dashboard_preparation.ipynb
├── dashboard/
│ ├── it-job-market-dashboard.pbix
│ └── PowerBI Dashboard.png
├── Reports/
│ ├── Final_Report.md
│ └── figures/ # PNG charts for visual storytelling
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## 🚀 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/it-job-market-dashboard.git
cd it-job-market-dashboard
```

2. **Install Python Dependencies**
```bash
pip install -r requirements.txt
```

3. **Open Notebooks for Exploration**
```bash
jupyter notebook
```

4. **Launch Power BI Dashboard**

   - Open the `it-job-market-dashboard.pbix` file using **Power BI Desktop**
   - Explore interactive visuals with filters for:
     - **Experience Level** (Entry, Mid, Senior, Expert)
     - **Job Title**
     - **Job Location** (State or Country)
   - Analyze salary trends, role distributions, and hiring hotspots through visual storytelling

   
## 🧠 Key Skills Demonstrated
- Data wrangling with Python

- Data storytelling using Power BI

- Real-world job market analysis

- Business-oriented dashboard design

## 📚 Final Report

All key findings, visuals, and methodology are documented in:  
📄 [`Reports/Final_Report.md`](Reports/Final_Report.md)


## 👤 Author

**Name:** F Sahfeerul Wasihf  
**GitHub:** [@SAHFEERULWASIHF](https://github.com/SAHFEERULWASIHF)  
**LinkedIn:** [www.linkedin.com/in/sahfeerul-wasihf](https://www.linkedin.com/in/sahfeerul-wasihf)  
**Email:** wasihfwork@gmail.com


