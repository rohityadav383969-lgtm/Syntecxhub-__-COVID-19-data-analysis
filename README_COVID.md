# 🇮🇳 COVID-19 Cases in India – Data Analysis Project

## 📌 Project Overview

This project performs a **company-level exploratory data analysis (EDA)** on COVID-19 case data in India.
The objective is to understand how COVID-19 cases are distributed across Indian states and union territories,
and to analyze active cases, recoveries, and deaths using **Python, Pandas, Matplotlib, and Seaborn**.

This project is suitable for **college submission, internships, and data analyst portfolios**.

---

## 🎯 Objectives

- Understand the structure of COVID-19 data for India
- Perform data cleaning and validation
- Analyze confirmed, active, recovered, and death cases
- Visualize trends and comparisons across states
- Generate clear insights for decision-making

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Information

- File name: `Covid_cases_in_India.csv`
- Rows: 32 (States & UTs)
- Columns:
  - Name of State / UT
  - Total Confirmed cases
  - Active
  - Cured/Discharged/Migrated
  - Deaths

---

## 🔍 Data Cleaning Steps

- Removed unnecessary index column (`S. No.`)
- Checked for missing values (none found)
- Renamed columns for easier analysis
- Ensured numerical columns were correctly typed

---

## 📊 Exploratory Data Analysis (EDA)

### Analysis Performed:

- Top states by confirmed COVID-19 cases
- Active cases comparison across states
- Recovery vs death ratio
- State-wise death distribution
- Percentage contribution of active, recovered, and death cases

### Visualizations Used:

- Bar charts for state-wise comparisons
- Pie charts for case distribution
- Horizontal bar plots for better readability
- Count and value plots using Seaborn

All visualizations were created using **Matplotlib and Seaborn** with proper titles and labels.

---

## 📈 Key Insights

- A few major states contribute a large share of total confirmed cases
- Recovery rate is significantly higher than death rate across most states
- Active cases are concentrated in specific regions
- Smaller states and UTs show controlled case counts

---

## 📁 Project Structure

```
├── Covid_cases_in_India.csv
├── Covid_India_Data_Analysis.ipynb
└── README.md
```

---

## 📄 Conclusion

This analysis demonstrates how structured data analysis and visualization
can help understand the spread and impact of COVID-19 across India.
The project strengthens practical skills in data cleaning, EDA, and storytelling with data.

---

## 👤 Author

### Rohit Prabhat Yadav

#### INTERNSHIP : SYNTECXHUB

College Project & Internship Practice

---

## 🚀 Future Improvements

- Add time-series COVID trend analysis
- Include vaccination data
- Build a Streamlit dashboard for live visualization
