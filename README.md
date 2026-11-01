# 📊 Techma Zone: Student Enrollment & Marketing Dashboard

An interactive, 4-page Power BI dashboard designed to track student enrollment lifecycles, optimize marketing lead acquisition, monitor daily attendance, and identify student retention risks.

> 💡 **Note on Deployment:** This dashboard is built on local architecture. Below is a comprehensive visual walk-through and data breakdown of all 4 pages.

---

## 📸 Dashboard Walkthrough & Visuals

### Page 1: Student Enrollment Lifecycle
[Page 1 Screenshot](https://github.com)
* **Purpose:** Tracks the student pipeline from initial application to final registration.
* **Key Visuals:** Funnel chart showing conversion drop-offs, KPI cards for total enrollment.

### Page 2: Marketing Lead Acquisition
[Page 2 Screenshot](https://github.com)
* **Purpose:** Evaluates which marketing channels yield the highest quality student leads.
* **Key Visuals:** Bar charts comparing acquisition cost vs. student retention by platform.

### Page 3: Attendance Monitoring
[Page 3 Screenshot](https://github.com)
* **Purpose:** Pinpoints daily and weekly trends in student absences across different cohorts.
* **Key Visuals:** Heatmap matrix of attendance percentages by day and time.

### Page 4: Retention & Risk Matrix
[Page 4 Screenshot](https://github.com)
* **Purpose:** An early warning system identifying students at risk of dropping out.
* **Key Visuals:** Scatter plot showing the correlation between low attendance and failing grades.

---

## 💡 Key Business Insights Discovered
* **Marketing Optimization:** Identified that certain lead sources yielded high initial conversions but massive drop-out rates within the first 30 days.
* **Attendance Patterns:** Uncovered a statistical drop in attendance on specific days, directly correlating with higher risks in specific cohorts.
* **Retention Warning System:** Created a risk threshold filter highlighting students with less than 75% attendance for early advisor intervention.

---

## 🛠️ Tech Stack & Technical Implementation
* **Tool:** Power BI Desktop
* **Data Modeling:** Optimized data structure using a Star Schema layout (Fact tables connected to Dimension tables) to ensure fast dashboard performance.
* **DAX Formulas Used:** Developed custom measures for **Year-to-Date (YTD) Growth**, **moving attendance averages**, and **lead-to-student conversion percentages**.
* **UI/UX Design:** Implemented conditional formatting (colors changing based on risk), custom navigation menus, and specific drill-through filters.
