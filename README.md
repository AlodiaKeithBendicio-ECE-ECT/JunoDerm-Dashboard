# 📊 Agent Productivity Dashboard – Google Looker  

---

## 🏢 Project Overview
<p align="justify">
This Google Looker dashboard tracks daily team performance by monitoring <b>Average Handling Time (AHT), Hold Time, Adherence, QA Scores, Offline Activities, Max Hours, Refused Calls, ACW,</b> and <b>Total Daily Hours</b>.  
It provides <b>real-time insights</b> for team leaders to assess productivity, identify workflow gaps, and make data-driven decisions to optimize efficiency.
</p>

---

## 🔧 Workflow & Data Pipeline
- **🖥️ Data Extraction:**  
  Daily activity data was automatically extracted from the company’s reporting portal using <b>Python + Playwright</b>, fully eliminating manual downloads.  

- **🧹 Data Preparation:**  
  Cleaned, validated, and standardized using <b>Excel</b> to ensure consistency.  
  - Unified date formats and field naming conventions  
  - Merged daily exports into consolidated monthly datasets  
  - Applied formula-based QA validation checks  

- **📊 Data Integration:**  
  Processed data was uploaded to <b>Google Sheets</b> as a live source connected to Looker Studio.  

- **📈 Dashboard Development:**  
  Built in <b>Google Looker Studio</b> to visualize agent-level metrics, team averages, and trend patterns across the covered date range.  

> ℹ️ <b>Data Coverage:</b> February 3 – June 13, 2025  
> Data was captured via Playwright automation and transformed through Excel before visualization.

---

## 📌 Key Metrics & Insights
- **👤 Agent Productivity** – Overall performance per agent  
- **⏱️ Average Handling Time (AHT)** – Efficiency in task or call handling  
- **📞 Average Hold Time** – Time spent on hold during interactions  
- **📅 Adherence** – Schedule compliance rate  
- **⭐ QA Scores** – Quality assurance ratings  
- **🛠️ Offline Activities** – Logged non-core activities  
- **⏳ Max Hours** – Longest logged hours in a shift  
- **🚫 Refused Calls** – Declined or unhandled calls  
- **📝 After Call Work (ACW)** – Post-interaction documentation duration  
- **🕒 Total Daily Hours** – Total logged time per agent  

---

## 🛠️ Tools & Technologies
- **Python (Playwright)** – Automated browser-based data extraction  
- **Excel** – Data cleaning, merging, and validation  
- **Google Sheets** – Data staging and integration  
- **Google Looker Studio** – Dashboard design and visualization  

---

## 🚀 Impact
- Streamlined data collection with <b>automated daily exports</b> from February to June 2025.  
- Reduced manual report generation by over <b>80%</b>.  
- Provided <b>team leaders</b> with accurate and timely operational insights.  
- Centralized all performance metrics in a single, dynamic dashboard.  

---

## 📁 Repository Contents
- `README.md` – Project documentation  
- `data-prep/` – Python script, excel templates and cleaning workflows (anonymized)  
- `dashboard/` – Looker dashboard screenshots and sample views  
- `assets/` – Visuals, banners, and logos

---

## 🔗 Dashboard Access
[View Google Looker Dashboard ↗](https://lookerstudio.google.com/reporting/63d0fa9a-7aa5-4d24-b1cf-0fc1a308fa9e)  


---

## 🖼️ Visual Preview
<p align="center">
  <img src="dashboard/junoderm-visual-preview.png" width="750">
</p>

---

## 📥 Resources
- [Excel Data Template](data-prep/JunoDerm%20Prod%20Report.xlsx)  
- [Python Automation Script (Playwright)](automation/JunoDerm%20Raw%20Data%20Extraction.ipynb)  
- [Looker Dashboard Screenshot](dashboard/junoderm-visual-preview.png)

---

## 📎 Data Notes
- **Source:** Internal performance reports (anonymized)  
- **Data Coverage:** February 3 – June 13, 2025  
- **Collection Method:** Automated daily export via Python + Playwright  
- **Transformation:** Excel  
- **Storage:** Google Sheets (connected to Looker Studio)  
- **Refresh Type:** Static snapshot (data collection concluded June 2025)  

---

