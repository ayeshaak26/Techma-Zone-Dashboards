
# 📊 Techma Zone: Student Enrollment & Marketing Dashboard

An interactive, 4-page Power BI dashboard designed to track student enrollment lifecycles, optimize marketing lead acquisition, monitor daily attendance, and identify student retention risks.

> 💡 **Note on Deployment:** This dashboard is built on local architecture. Below is a comprehensive visual walk-through and data breakdown of all 4 pages.

---

## 📸 Dashboard Walkthrough & Visuals

### Page 1: Student Enrollment Lifecycle
[Page 1 Screenshot](https://github.com/ayeshaak26/Techma-Zone-Dashboards/blob/main/1%20-%20Executive%20Overview.png)
* **Purpose:** Tracks the student pipeline from initial application to final registration.
* **Key Visuals:** Funnel chart showing conversion drop-offs, KPI cards for total enrollment.

### Page 2: Enrollment & Marketing
[Page 2 Screenshot](https://github.com/user-attachments/assets/70ded3a0-29ae-4bcd-96c8-b4f7544a5b41)
* **Purpose:** Evaluates which marketing channels yield the highest quality student leads.
* **Key Visuals:** Bar charts comparing acquisition cost vs. student retention by platform.

### Page 3: Student Course Health
[Page 3 Screenshot](<img width="1291" height="717" alt="4 - Student   Course Health" src="https://github.com/user-attachments/assets/4d461db1-8b22-44a0-80f4-f50fa3d9de07" />)
* **Purpose:** Pinpoints daily and weekly trends in student absences across different cohorts.
* **Key Visuals:** Heatmap matrix of attendance percentages by day and time.

### Page 4: Finance & Receivables
[Page 4 Screenshot](<img width="1285" height="722" alt="3 - Finance   Receivables" src="https://github.com/user-attachments/assets/2cc18421-b61f-4d89-b655-487e6f8bb298" />)
* **Purpose:** An early warning system identifying students at risk of dropping out.
* **Key Visuals:** Scatter plot showing the correlation between low attendance and failing grades.

---

💡 Key Business Insights Discovered
* **Marketing Optimization:** Identified that certain lead sources yielded high initial conversions but massive drop-out rates within the first 30 days.
* **Attendance Patterns:** Uncovered a statistical drop in attendance on specific days, directly correlating with higher risks in specific cohorts.
* **Retention Warning System:** Created a risk threshold filter highlighting students with less than 75% attendance for early advisor intervention.

---

## 🛠️ Tech Stack & Technical Implementation
* **Tool:** Power BI Desktop
* **Data Modeling:** Optimized data structure using a Star Schema layout (Fact tables connected to Dimension tables) to ensure fast dashboard performance.
* **DAX Formulas Used:** Developed custom measures for **Year-to-Date (YTD) Growth**, **moving attendance averages**, and **lead-to-student conversion percentages**.
* **UI/UX Design:** Implemented conditional formatting (colors changing based on risk), custom navigation menus, and specific drill-through filters.
