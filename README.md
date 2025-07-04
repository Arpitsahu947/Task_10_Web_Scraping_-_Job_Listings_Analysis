# Task_10_Web_Scraping_-_Job_Listings_Analysis

# 📊 Task 10: Web Scraping & Job Listings Analysis

## 🎯 Objective:
Collect and analyze job listing data for **Data Analyst roles** using Python. Since live scraping of Internshala presented dynamic content issues, simulated job data has been used to demonstrate the end-to-end pipeline including cleaning, analysis, and visualization.

---

## 🛠 Tools & Libraries Used:
- Python
- Pandas
- Matplotlib
- Regex (`re`)
- `collections.Counter`

---

## 🧠 Extracted Fields:
- Job Title
- Company Name
- Location
- Stipend
- Required Skills

---

## 📁 Files Included:
- `web_scraper_task10.ipynb` – Main Jupyter Notebook with logic and output
- `internshala_data_analyst_jobs.csv` – Simulated CSV job data
- `top_locations.png` – Bar chart showing top job locations
- `README.md` – This documentation file

---

## 📈 Summary of Findings:
- **Total Jobs Simulated**: 5  
- **Top Locations**:
  - Bangalore
  - Mumbai
  - Remote
  - Delhi
- **Top In-Demand Skills**:
  - `excel`
  - `python`
  - `sql`
  - `power`
  - `bi`
  - `tableau`
  - `powerpoint`

---

## 🧪 Challenges Faced:
- Dynamic content on Internshala required rendering via JavaScript
- Even with Selenium, job elements returned empty values
- Used simulated job listings to showcase data extraction and analysis structure

---

## 🚀 Learning Outcomes:
- Hands-on with real-world web scraping limitations
- Built a working analysis pipeline from raw data to insight
- Practiced data cleaning, parsing skills text with regex
- Visualized insights using Matplotlib

---

✅ This task demonstrates how a data analyst would extract unstructured job data and turn it into insights, even under scraping constraints.

