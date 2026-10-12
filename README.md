# Customer Complaint Dashboard | Power BI

An interactive Power BI dashboard for analysing customer complaints, identifying recurring issues, monitoring complaint status, and understanding customer satisfaction.

## 📊 Project Overview

The **Customer Complaint Dashboard** transforms customer support data into meaningful visual insights. It helps users analyse complaint volumes across different products, complaint categories, communication channels, priority levels, and time periods.

The dashboard is designed to support data-driven decision-making by highlighting patterns that may require further investigation and improvement in customer service operations.

## 🎯 Objectives

- Analyse the overall volume of customer complaints.
- Monitor the number of closed complaints.
- Identify the top five products with the highest complaint counts.
- Understand the distribution of complaints by type and communication channel.
- Analyse complaints by priority level.
- Compare monthly complaint trends for 2020 and 2021.
- Monitor the overall customer satisfaction rating.
- Support business decisions related to complaint resolution and customer experience.

## 🛠️ Tools and Technologies

- **Microsoft Power BI Desktop** — Dashboard development and data visualisation.
- **Power Query** — Data preparation and transformation, where applicable.
- **DAX (Data Analysis Expressions)** — Calculations and measures, where applicable.
- **GitHub** — Project hosting and documentation.

## 📌 Dashboard Features

### 1. Total Complaints
Displays the overall number of complaints recorded in the dataset.

**Displayed value:** 2,129

**Business use:** Establishes the overall complaint volume and provides a baseline for further analysis.

### 2. Closed Complaints
Displays the number of complaints marked as closed.

**Displayed value:** 726

**Business use:** Helps monitor complaint resolution and identify the need to investigate pending or unresolved cases.

### 3. Top 5 Products with Most Complaints
Ranks the five products with the highest complaint counts.

Products shown include:
- Sony Xperia
- Sony 4K HDR TV
- Sony PlayStation
- Samsung Soundbar
- Xbox

**Business use:** Helps identify products that may require further investigation into recurring issues, product quality, or customer support.

### 4. Complaints by Type
Categorises complaints into:
- Billing Inquiry
- Cancellation Request
- Product Inquiry
- Refund Request
- Technical Issue

**Business use:** Helps identify frequently reported issues and determine which business processes may need improvement.

### 5. Complaints by Communication Channel
Analyses complaints received through:
- Email
- Phone
- Social Media
- Chat

**Business use:** Helps understand support-channel demand and plan customer service resources.

### 6. Complaints by Priority
Displays the distribution of complaints across four priority levels:
- Low
- Medium
- High
- Critical

**Business use:** Helps management understand the priority distribution and investigate critical complaints that may require urgent attention.

### 7. Complaint Trends: 2020 vs. 2021
A monthly line chart compares complaint patterns across 2020 and 2021.

**Business use:** Helps identify fluctuations, unusual peaks, and periods that require further analysis.

### 8. Customer Satisfaction Rating
Displays the customer satisfaction rating on a scale of 1 to 5.

**Displayed value:** 2.96

**Business use:** Provides an overview of customer satisfaction and helps identify areas for further investigation and service improvement.

### 9. Geographical Analysis
A map visual was included for geographical complaint analysis. It is currently disabled by the Power BI security settings shown in the report.

**Potential business use:** State-wise complaint analysis can help identify regional patterns when the map is enabled or when an alternative geographical visual is used.

## 📈 Key Metrics

| Metric | Dashboard Value |
|---|---:|
| Total Complaints | 2,129 |
| Closed Complaints | 726 |
| Calculated Closure Rate | 34.1% |
| Customer Satisfaction Rating | 2.96 / 5 |

The closure rate is calculated as:

Closure Rate = (Closed Complaints / Total Complaints) × 100

The displayed totals give a closure rate of approximately 34.1%. This calculation assumes that the two KPI cards use compatible complaint-count definitions and filters.

## 💡 Business Value

The dashboard can help businesses:

- Identify products associated with high complaint volumes.
- Investigate recurring customer issues.
- Monitor complaint resolution performance.
- Understand support-channel demand.
- Prioritise critical complaints.
- Track customer satisfaction.
- Investigate changes in complaint trends.
- Make informed decisions about customer service improvements.

These insights can guide further investigation; complaint counts alone do not establish the root cause of a problem.

## 🚀 How to Use the Dashboard

1. Open the Power BI project in Power BI Desktop.
2. Explore the KPI cards to understand the overall complaint situation.
3. Select a complaint type using the slicer at the top of the report.
4. Compare products, complaint categories, channels, and priority levels.
5. Review the monthly trend chart to identify changes over time.
6. Examine the customer satisfaction rating.
7. Use the findings to identify areas requiring further investigation.

*Note: The availability of interactive filtering depends on the report's visual interaction settings.*

## 🔍 Possible Future Improvements

- Add a complaint closure rate KPI.
- Analyse pending complaints and complaint ageing.
- Include average complaint resolution time.
- Add month-on-month and year-on-year comparisons.
- Enable geographical analysis where permitted.
- Add drill-through pages for detailed complaint analysis.
- Compare customer satisfaction across complaint types and channels.
- Introduce service-level agreement (SLA) monitoring.

## 📂 Project Files

The repository contains the Power BI project and supporting documentation or screenshots, as uploaded.

- **Power BI project:** Customer Complaint Dashboard
- **Dashboard screenshot:** Visual preview of the report

Refer to the files available in this repository for the actual project artefacts.

## 👨‍💻 Author

**Rishi Kumar Kanwar**

GitHub: [@rishikanwar55](https://github.com/rishikanwar55)

## ⭐ Conclusion

This project demonstrates the use of Power BI for customer support analytics and business reporting. By combining KPI cards, interactive filtering, bar charts, a donut chart, and a monthly trend chart, the dashboard presents complaint data in an accessible format and supports data-driven customer service decisions.
