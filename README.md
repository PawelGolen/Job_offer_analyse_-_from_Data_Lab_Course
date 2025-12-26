# Job Offer Analysis (Pandas & Matplotlib)

This project performs a **basic exploratory data analysis (EDA)** on job offer data using **Python and Pandas**.  
The dataset contains job listings from a Polish job portal and was provided as part of a Data Lab course assignment.

---

## 📊 Dataset

The input dataset (`job_offers.csv`) includes the following fields:
- job title / role (`job`)
- company name
- city and country
- salary ranges (low / high / average)
- currency
- seniority flag (`is_senior`)

---

## 🔍 Analysis Performed

The analysis focuses on answering practical questions such as:

- Distribution of job offers by role  
  (Data Analyst, Data Engineer, Data Scientist)
- Number of job offers by **city and role**
- Average salary by **job role**
- Average salary by **location**
- Salary comparison between **junior and senior** positions
- Cross-analysis of location, role, and compensation

---

## 📈 Visualizations

Visualizations are created using **Matplotlib**, including:
- Bar charts for job distribution
- Salary comparisons by role and city
- Pivot-table based salary breakdowns

The plots are intended for quick insights rather than production dashboards.

---

## 🧰 Tech Stack

- **Python**
- **Pandas** – data loading, grouping, aggregation
- **Matplotlib** – basic data visualization

---

## 📝 Notes

- This is an **educational / exploratory project**
- Focus is on data manipulation and analysis, not pipeline orchestration
- The dataset is pre-processed and loaded from CSV

---

## 📄 License

This project is available under the **MIT License**.
