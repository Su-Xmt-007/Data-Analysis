**Hospital Emergency Room Data Analysis Dashboard
📊 Project Overview**
This project analyzes patient data from a hospital emergency room to provide key insights through an interactive Excel dashboard. The primary goal is to empower stakeholders to monitor operational performance, analyze service quality, and make data-driven decisions to enhance patient care and resource management.

**📂 Repository Structure**
MainRepo/
├─ README.md   ← Project overview and documentation
├─ Hospital emergency room data complete.xlsx
│    ├─ Sheet1 → Raw patient data
│    ├─ PivotTables → Aggregated performance metrics
│    ├─ Dashboard → Visualization and interactive controls

**📑 Data Description**
**Sheet1 (Raw Data)**
Contains transaction-level details, including:
Patient Admission Date & time: The exact date and time a patient arrived.
Patient Age, Patient Gender, Patient Race: Patient demographic information.
Department Referral: The department the patient was referred to from the ER.
Patient Admission Flag: A boolean flag (TRUE/FALSE) indicating if the patient was admitted.
Patient Satisfaction Score: A numerical score (1-10) of the patient's experience.
Patient Waittime: The total time a patient waited in the emergency room (in minutes).

**PivotTables (Insights)**
Pre-built summaries for core analysis:
Patient Flow by Time: Tracks patient visits by hour, day, month, and year to identify peak times.
Admission Rate Analysis: Calculates the percentage of patients admitted versus those discharged.
Satisfaction vs. Wait Time: Correlates patient satisfaction scores with their wait times to highlight service impact.
Department Referral Patterns: Visualizes the distribution of patient referrals to other departments.

**Dashboard (Visualization Layer)**
An interactive dashboard with a high-level summary of the analysis:
Total patient count and key performance indicators (KPIs).
Charts for hourly, daily, and monthly patient trends.
Visualizations of average wait time and patient satisfaction.
A breakdown of department referral percentages.

**❓ Key Business Questions Answered**
How does patient traffic vary by day of the week and hour of the day?
What is the patient admission rate, and how does it trend over time?
What is the average patient wait time, and are there specific times when it spikes?
What is the average patient satisfaction score, and are there opportunities for improvement?
Which departments receive the most referrals from the emergency room?
How do patient demographics (age, gender) relate to key metrics like wait time and admission status?

**🚀 How to Use**
Open the Hospital emergency room data complete.xlsx file in Excel.
Navigate to the Sheet1 tab to review the raw data.
Go to the PivotTables sheet to view and interact with the pre-built summaries.
Access the Dashboard sheet for a comprehensive, visual overview. Use the slicers to filter data and gain deeper insights.

**📌 Future Enhancements**
Add interactive slicers for filtering data by patient demographics (age group, gender).
Create a drill-down feature to analyze specific outliers in wait times or satisfaction scores.
Automate data refresh and reporting using VBA macros.
