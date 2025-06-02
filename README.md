# 💼 Job Analysis Project

## 📌 Overview

This project provides a comprehensive analysis of the Indian job market using real-world data scraped from the web. It focuses on understanding demand trends across job roles, skills, salaries, and top employers.

---

## 🧾 Sample Data (Preview)

| job\_id      | job\_role                          | company                         | experience | salary                   | location              | rating | reviews     | responsibilities                                       |
| ------------ | ---------------------------------- | ------------------------------- | ---------- | ------------------------ | --------------------- | ------ | ----------- | ------------------------------------------------------ |
| 151122600000 | Business Sales Manager - Banca     | Lavya Associates                | 5-10 Yrs   | ₹6,00,000 - ₹8,00,000 PA | Jorhat                | NaN    | NaN         | Life Insurance, BFSI, Bancassurance, team handling     |
| 301222000000 | HR Manager 1                       | Emerald Paper Products          | 2-7 Yrs    | ₹1,75,000 - ₹2,50,000 PA | Hybrid - Mohanlalganj | NaN    | NaN         | Human Resource Management, hr, monitoring, Recruitment |
| 20123500000  | Executive - DevOps Engineer        | Rahi                            | 3-8 Yrs    | Not disclosed            | Pune                  | NaN    | NaN         | Linux, Jenkins, web services, Gitlab, Puppet, DevOps   |
| 50123000000  | Operation Executive (Females Only) | Eduworld Bangalore Edu Services | 1-6 Yrs    | ₹1,25,000 - ₹2,50,000 PA | Trivandrum            | NaN    | NaN         | Team Management, Brand Development, Team Handling      |
| 70123500000  | Product Owner - Arcadis Gen        | Arcadis Consulting India Pvt.   | 4-7 Yrs    | Not disclosed            | Noida, Mumbai         | 4.2    | 145 Reviews | Product management, Sales, SAP, Performance management |

---

## 🎯 Objectives

* Understand the distribution of job roles and industry demand.
* Identify essential skills and experience ranges.
* Analyze salary patterns across regions and industries.
* Highlight top employers and their market share.

---

## 🧹 Data Processing

* **Null Handling:** Filled missing values or dropped incomplete rows.
* **Data Cleaning:** Standardized salary and experience columns.
* **Deduplication:** Removed duplicate `job_id` entries.
* **Transformation:** Extracted min/max salary and experience for analysis.

---

## 📊 Visualizations

* 📈 **Pie Chart**: Top 10 companies by minimum reviews
* 📊 **Bar Charts**: Role frequency, skill requirements
* 📍 **Location Maps** (optional for future): Job density by region

---

## 🔍 Key Insights

* 📌 **72,967 job listings** across **15,310 companies**.
* 📌 **Top Roles**: High demand for Data Analysts, HR Managers, and DevOps Engineers.
* 📌 **Key Skills**: SAP, Team Handling, Recruitment, Product Management.
* 📌 **Top Employers**:

  * **TCS** – 15.8% of top reviews
  * **RIL** – 13.7%
  * **HDFC Bank** – 12.3%
  * **ICICI Bank** – 10.5%
  * **Accenture** – 10.1%

---

## 🛠️ Technologies Used

| Tool         | Purpose                       |
| ------------ | ----------------------------- |
| `Python`     | Core language for analysis    |
| `Pandas`     | Data manipulation             |
| `Matplotlib` | Visualization                 |
| `Seaborn`    | Enhanced plots and aesthetics |
| `NumPy`      | Numerical operations          |


---

## 🔮 Future Enhancements

* 📊 Add salary prediction using machine learning
* 🗺️ Regional clustering of job demand
* 🔍 Skill-based filtering per company
* 📦 Dashboard development using Streamlit

---

✅ Conclusion
This job analysis project offers a detailed perspective on the Indian job market by examining thousands of job listings across various roles, industries, and companies. By cleaning and visualizing the data, we uncovered key patterns in job demand, skills, salary ranges, and top recruiters.

The analysis highlights the growing importance of technical and management roles such as DevOps Engineers, Data Analysts, and HR Managers. Additionally, skills like SAP, team leadership, and recruitment are in high demand. Companies like TCS, Reliance, and HDFC Bank lead the hiring landscape, offering abundant opportunities for job seekers.

These insights can guide students, professionals, and recruiters in making informed decisions about career paths, skill development, and talent acquisition strategies. Future work could focus on building predictive models to forecast job trends or designing an interactive dashboard to explore job data dynamically.
