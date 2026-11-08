# 🏥 Hospital Data Analytics
### Transforming Raw Healthcare Data into Actionable Business Insights

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Query-2B579A?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-6A1B9A?style=for-the-badge&logo=databricks&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Records_Analyzed-10,000-1565C0?style=flat-square" />
  <img src="https://img.shields.io/badge/Interactive_Dashboards-5-00897B?style=flat-square" />
  <img src="https://img.shields.io/badge/Domain-Healthcare-E53935?style=flat-square" />
</p>

---

## 📌 1. Project Overview

The **Hospital Data Analytics Project** is an end-to-end data analysis and business intelligence project focused on analyzing hospital patient records to uncover meaningful insights into patient demographics, medical conditions, billing patterns, insurance providers, and admission trends.

The project utilizes a dataset containing **10,000 healthcare records spanning October 2018 to October 2023**. The raw data was cleaned, transformed, and analyzed using Microsoft Excel and Power Query, followed by the development of interactive Power BI dashboards.

The primary objective was to transform raw healthcare data into structured analytical outputs that could help stakeholders understand patient characteristics, investigate financial patterns, monitor admission behavior, and identify potential operational improvement opportunities.

### ✨ Project Highlights

- 10,000 healthcare records analyzed.
- Data cleaning and transformation using Excel and Power Query.
- Exploratory and comparative analysis using Excel Pivot Tables.
- Demographic, financial, insurance, and admission trend analysis.
- Hypothetical elective admission redistribution scenarios.
- Five-page interactive Power BI reporting solution.
- Business findings and actionable recommendations.

---

## 💡 2. Why I Chose This Project

Healthcare is a data-intensive industry where effective data analysis can support operational planning, financial monitoring, and better resource utilization.

I chose this project to apply my data analytics skills to a practical business scenario rather than limiting myself to basic sales or retail datasets.

The project allowed me to explore how healthcare records can be transformed into meaningful information through data cleaning, exploratory analysis, comparative analysis, and interactive visualization.

It also provided an opportunity to work with multiple analytical dimensions, including patient demographics, medical conditions, billing amounts, insurance providers, and admission patterns.

My goal was to demonstrate an end-to-end analytical workflow using industry-relevant tools while developing the ability to translate data-driven findings into meaningful business recommendations.

---

## 🎯 3. Business Problem

Healthcare organizations generate large volumes of patient and operational data. However, raw datasets often contain inconsistent values, missing information, and disconnected records that make meaningful analysis difficult.

Without proper data preparation and analysis, stakeholders may struggle to:

- Understand the demographic composition of patients.
- Identify frequently recorded medical conditions.
- Compare billing patterns across medical conditions.
- Evaluate billing variations across insurance providers.
- Understand admission patterns across different time periods.
- Identify potential opportunities for better admission scheduling.

**Problem Statement:**

To transform raw hospital patient records into a structured analytical solution that provides insights into patient demographics, financial patterns, insurance comparisons, and admission trends, enabling data-driven exploration and operational planning.

---

## 🚀 4. Project Objectives

The project was designed around the following objectives:

1. **Patient Demographics Analysis:** Understand patient distribution across age groups, gender, and other demographic categories.

2. **Medical Condition Analysis:** Identify frequently recorded medical conditions and examine their distribution across different demographic groups.

3. **Financial Analysis:** Evaluate total and average billing amounts and compare financial patterns across medical conditions.

4. **Insurance Provider Analysis:** Compare average billing amounts across insurance providers and identify condition-wise differences.

5. **Admission Trend Analysis:** Investigate admission patterns across years, months, days, and admission types.

6. **Operational Scenario Analysis:** Explore hypothetical elective admission redistribution scenarios to understand how admission volumes could potentially be balanced across different periods.

7. **Business Intelligence Development:** Build interactive Power BI dashboards to communicate analytical findings and recommendations effectively.

---

## 📂 5. Dataset Description

The project uses a hospital healthcare dataset containing **10,000 patient records and 20 columns** in the final analytical table.

**Dataset Coverage:** October 2018 – October 2023.

### 📊 Dataset Information

| Attribute | Description |
|---|---|
| Total Records | 10,000 |
| Total Columns | 20 |
| Time Period | October 2018 – October 2023 |
| Medical Conditions | 6 |
| Insurance Providers | 5 |
| Admission Categories | 3 |
| Data Format | CSV / Excel |

### Dataset Attributes

| Category | Attributes |
|---|---|
| Patient Information | Name, Age, Gender, Blood Group |
| Medical Information | Medical Condition |
| Admission Information | Date of Admission, Discharge Date, Admission Type |
| Hospital Information | Doctor, Hospital, Room Number |
| Financial Information | Billing Amount |
| Insurance Information | Insurance Provider |
| Derived Attributes | Age Group, Age Classification, Year, Month Name, Day Name, Age & Gender |

### 🩺 Medical Conditions

- Arthritis
- Asthma
- Cancer
- Diabetes
- Hypertension
- Obesity

### 🏥 Admission Types

- Emergency
- Urgent
- Elective

The dataset was used for analytical and educational purposes. Its records should not be interpreted as verified clinical or operational data from a real hospital.

---

## 🛠️ 6. Technology Stack

The project was developed using the following technologies:

<p align="center">
  <img src="https://skillicons.dev/icons?i=excel,powerbi" alt="Excel and Power BI" />
</p>

| Technology | Purpose |
|---|---|
| Microsoft Excel | Initial data exploration, cleaning, Pivot Tables, and analytical calculations |
| Power Query Editor | Data transformation, standardization, and preparation |
| Microsoft Power BI | Interactive dashboards and data visualization |
| DAX | Measures, calculated metrics, and dynamic reporting |
| CSV / Excel | Data storage and exchange |

### 🔧 Key Features Used

**Microsoft Excel**
- Data cleaning and formatting
- Pivot Tables
- Univariate analysis
- Cross-tabulation
- Percentage deviation analysis
- Comparative analysis
- What-if scenario calculations

**Power Query**
- Data type conversion
- Text standardization
- Missing-value checks
- Date transformations
- Derived column creation
- Data preparation

**Power BI & DAX**
- KPI cards
- Interactive slicers
- Bar and column charts
- Donut charts
- Line charts
- Scatter plots
- Matrix visualizations
- Conditional formatting
- Date tables and relationships
- Dynamic measures
- Page navigation

---

## 🧹 7. Data Cleaning & Preparation

The raw dataset required several cleaning and transformation operations before it could be used for meaningful analysis.

Data preparation was performed using Microsoft Excel and Power Query Editor.

### Cleaning Operations

| Column | Issue Identified | Action Performed |
|---|---|---|
| Age | Inconsistent or invalid entries | Standardized and validated numeric values |
| Gender | Inconsistent values such as `M` and extra spaces | Standardized gender categories |
| Blood Type | Inconsistent text representation | Standardized blood group values |
| Medical Condition | Inconsistent capitalization and formatting | Applied consistent text formatting |
| Admission Type | Abbreviated and inconsistent entries such as `Emer` | Standardized admission categories |
| Billing Amount | Numeric formatting and missing values | Converted to numeric data type and validated |
| Date of Admission | Required time-based analysis | Standardized date values and extracted date attributes |
| Discharge Date | Required date-based analysis | Standardized date values |

### Additional Transformations

The following analytical columns were created:

- Age Classification
- Age Group
- Age & Gender
- Year
- Month Number
- Month Name
- Day Number
- Day Name
- Standardized Blood Group

These transformations improved data consistency and enabled more detailed demographic and time-based analysis.

**Data Quality Considerations:**

- Missing billing amounts were identified and excluded from average billing calculations rather than treated as zero.
- Inconsistent categorical values were standardized.
- Date attributes were extracted to support trend analysis.
- Age classifications were created to support demographic segmentation.

---

## 📈 8. Exploratory Data Analysis Using Excel

After preparing the dataset, exploratory analysis was performed using Excel Pivot Tables, summary tables, and comparative calculations.

The analysis was organized into three major analytical areas.

### A. Univariate Analysis

Individual variables were analyzed to understand their distributions and identify major patterns.

Analysis included:

- Age distribution across age ranges.
- Gender distribution.
- Medical condition distribution.
- Insurance provider distribution.
- Admission type distribution.
- Blood group distribution.
- Year-wise admission distribution.
- Hospital and doctor frequency distributions.

### B. DA-1: Demographic & Medical Condition Analysis

This analysis focused on relationships between patient demographics and medical conditions.

Key analyses included:

- Medical condition distribution by gender.
- Medical condition distribution by age group.
- Gender-wise comparison of medical conditions.
- Age-group-wise condition frequency.
- Cross-tabulation of demographic variables.

This helped identify differences in the representation of medical conditions across demographic categories.

### C. DA-2: Financial & Insurance Analysis

This analysis focused on understanding billing patterns and insurance provider comparisons.

Key analyses included:

- Average billing by medical condition.
- Average billing by insurance provider.
- Percentage deviation from overall average billing.
- Insurance provider versus medical condition comparison.
- Identification of the lowest-average-billing provider for each condition.
- Blue Cross comparative analysis.

A marketing-oriented comparison was also explored to identify potential opportunities for further investigation.

### D. DA-3: Admission Trend & Scenario Analysis

This analysis focused on understanding admission patterns and exploring potential scheduling improvements.

Key analyses included:

- Year-wise admission distribution.
- Month-wise admission distribution.
- Day-of-month admission distribution.
- Admission type comparisons.
- Identification of higher-volume and lower-volume periods.
- Hypothetical elective admission redistribution scenarios.

Two scenarios were explored:

1. **100% Redistribution Scenario:** Examined transferring elective admissions from days 8–17 to days 1–7.
2. **80% Redistribution Scenario:** Examined transferring 80% of elective admissions from the higher-volume period to the first week.

These scenarios were exploratory planning exercises rather than measured operational improvements.

---

## 📊 9. Power BI Dashboard Development

After completing the Excel analysis, the prepared dataset was used to develop an interactive five-page Power BI reporting solution.

The report includes one introduction page, three analytical dashboards, and one key insights and recommendations page.

### 📌 Dashboard 1: Hospital Overview & Patient Demographics

<img width="1396" height="791" alt="Screenshot 2026-11-08 181653" src="https://github.com/user-attachments/assets/fbd537d9-92ad-4cb1-8b92-6f91c385cecc" />

<img width="1390" height="799" alt="Screenshot 2026-11-08 181712" src="https://github.com/user-attachments/assets/58b8aca5-a83f-4c0e-9ef7-bf1f24b8e2e0" />

**Objective:** Understand the demographic composition of patient records and the distribution of medical conditions.

**Key Performance Indicators:**
- Total Patient Records
- Average Patient Age
- Female Patient Records
- Male Patient Records
- Number of Medical Conditions

**Visualizations:**
- Patients by Medical Condition
- Gender Distribution
- Patients by Age Group
- Medical Condition by Gender
- Patients by Insurance Provider
- Age Group by Medical Condition Matrix

**Interactive Filters:**
- Year
- Gender
- Medical Condition
- Insurance Provider
- Age

### 💰 Dashboard 2: Financial & Insurance Analysis
<img width="1382" height="789" alt="Screenshot 2026-11-08 181730" src="https://github.com/user-attachments/assets/056b5cab-5b26-4532-9208-a8c52a165389" />


**Objective:** Compare billing patterns across medical conditions, insurance providers, and admission categories.

**Key Performance Indicators:**
- Total Billing Amount
- Average Billing Amount
- Highest Average Billing by Condition
- Lowest Average Billing by Condition
- Records with Billing Data

**Visualizations:**
- Average Billing by Medical Condition
- Average Billing by Insurance Provider
- Average Billing by Condition and Insurance Provider
- Average Billing Trend Over Time
- Patient Age vs. Billing Amount
- Average Billing by Admission Type
- Insurance Provider Comparison Matrix

**Interactive Filters:**
- Year
- Medical Condition
- Insurance Provider
- Admission Type
- Age Group

### 📅 Dashboard 3: Patient Admission & Time Trends

<img width="1375" height="782" alt="Screenshot 2026-11-08 181754" src="https://github.com/user-attachments/assets/34477d42-3a43-4c44-b355-5709da8408a1" />

**Objective:** Analyze admission behavior and understand how admission volumes vary over time.

**Key Performance Indicators:**
- Total Admissions
- Emergency Admissions
- Urgent Admissions
- Elective Admissions

**Visualizations:**
- Admissions by Year
- Monthly Admission Trends
- Admissions by Type and Month
- Admission Type Distribution
- Admissions by Day of the Week
- Monthly Admissions Heatmap
- Admissions by Medical Condition and Year
- Average Billing by Admission Type

**Interactive Filters:**
- Year
- Month
- Admission Type
- Medical Condition
- Insurance Provider

### 📖 Supporting Pages

**Project Overview:** Provides the project introduction, objectives, dataset summary, tools used, and interactive navigation to the analytical dashboards.
<img width="1192" height="663" alt="Screenshot 2026-11-08 182019" src="https://github.com/user-attachments/assets/5564a6fa-5adb-4118-8967-92c0482a8d6b" />

**Key Insights & Recommendations:** Summarizes the major analytical findings and proposed business recommendations.

---

## 🔍 10. Key Business Findings

The analysis generated several meaningful findings.

### 1. Patient Demographics

- Total patient records: 10,000.
- Female records: 5,075 (50.75%).
- Male records: 4,925 (49.25%).
- Average patient age: approximately 51.45 years.

The dataset shows a nearly balanced gender distribution.

### 2. Medical Condition Distribution

| Medical Condition | Patient Records |
|---|---:|
| Hypertension | 2,155 |
| Cancer | 1,647 |
| Obesity | 1,627 |
| Arthritis | 1,587 |
| Asthma | 1,550 |
| Diabetes | 1,434 |

**Finding:** Hypertension is the most frequently recorded medical condition, representing 21.55% of the dataset.

### 3. Billing Differences Across Medical Conditions

| Medical Condition | Average Billing |
|---|---:|
| Cancer | 39,688.33 |
| Diabetes | 30,097.46 |
| Asthma | 22,650.73 |
| Arthritis | 20,054.35 |
| Hypertension | 17,637.16 |
| Obesity | 12,511.82 |

**Finding:** Cancer has the highest average billing amount, while Obesity has the lowest.

The difference suggests substantial variation in recorded billing across medical condition categories.

### 4. Insurance Provider Comparison

| Insurance Provider | Average Billing |
|---|---:|
| Cigna | 24,236.03 |
| Aetna | 24,133.56 |
| Medicare | 22,950.64 |
| UnitedHealthcare | 22,913.97 |
| Blue Cross | 22,778.89 |

**Finding:** Average billing amounts are relatively similar across insurance providers compared with the differences observed across medical conditions.

### 5. Admission Type Distribution

| Admission Type | Records | Percentage |
|---|---:|---:|
| Emergency | 3,587 | 35.87% |
| Urgent | 3,336 | 33.36% |
| Elective | 3,077 | 30.77% |

**Finding:** Emergency admissions represent the largest admission category, although the three categories are relatively evenly distributed.

### 6. Admission Trends

- The dataset covers October 2018 to October 2023.
- The year 2021 has the highest recorded annual admission count among the six calendar years.
- Day 15 has the highest day-of-month admission count, with 497 records.
- October has the highest monthly share of records at approximately 8.83%.

The first and last years have incomplete date coverage, so annual comparisons require caution.

---

## 💡 11. Business Recommendations

Based on the analytical findings, the following recommendations were developed.

### 1. Investigate High-Billing Medical Conditions

Cancer and Diabetes have considerably higher average recorded billing amounts.

Further analysis should investigate treatment complexity, length of stay, services provided, and other potential cost drivers.

### 2. Explore Admission Scheduling Optimization

The day-of-month analysis suggests an opportunity to investigate whether elective admissions can be distributed more evenly across lower-volume periods.

The 80% and 100% redistribution scenarios provide a starting point for operational planning.

Any real implementation should consider clinical priorities, staffing capacity, available beds, and patient preferences.

### 3. Examine Billing and Length of Stay Together

Analyzing the relationship between length of stay and billing amounts could help identify additional financial and operational patterns.

This would require further investigation using the available admission and discharge dates.

### 4. Monitor Medical Condition Distribution

The high representation of hypertension in the dataset suggests that it deserves attention in further demographic and healthcare resource analysis.

These findings should be interpreted as patterns within the dataset rather than generalized clinical conclusions.

### 5. Improve Financial Monitoring

Interactive billing dashboards can help stakeholders compare billing patterns across conditions and insurance providers and identify categories requiring further investigation.

---

## 🏆 12. Project Outcomes

The project successfully transformed raw healthcare records into a structured analytical dataset and an interactive reporting solution.

### Key Deliverables

- Cleaned and standardized healthcare dataset.
- Excel-based exploratory analysis workbook.
- Univariate analysis and demographic comparison tables.
- Financial and insurance provider analysis.
- Admission trend analysis and hypothetical scheduling scenarios.
- Five-page interactive Power BI report.
- DAX measures and interactive filtering.
- Business findings and recommendations.

### Overall Outcome

The project demonstrates how raw healthcare data can be transformed into meaningful analytical outputs through structured data preparation, exploratory analysis, comparative analysis, and business intelligence reporting.

It provides an organized framework for exploring patient demographics, billing variations, insurance comparisons, and admission behavior.

---

## 📁 13. Repository Structure

The GitHub repository is organized to keep source data, analysis files, reports, and documentation accessible.

```text
Hospital-Data-Analytics/
│
├── Dataset/
│   ├── Healthcare_Data_v1.csv
│   └── Hospital_Analysis_Final.xlsx
│
├── Excel_Analysis/
│   ├── Univariate_Analysis/
│   ├── DA-1_Demographic_Analysis/
│   ├── DA-2_Financial_Analysis/
│   ├── DA-3_Admission_Analysis/
│   └── Data_Dictionary/
│
├── PowerBI/
│   └── Hospital_Analytics_Dashboard.pbix
│
├── Screenshots/
│   ├── Project_Overview.png
│   ├── Patient_Demographics.png
│   ├── Financial_Insurance_Analysis.png
│   ├── Admission_Trends.png
│   └── Key_Insights.png
│
└── README.md
```

*Note: Adjust the folder and file names to match your actual GitHub repository.*

---

## 🧠 14. Skills Demonstrated

Through this project, I demonstrated the following technical and analytical skills:

### Technical Skills

- Microsoft Excel
- Data Cleaning and Data Transformation
- Power Query Editor
- Exploratory Data Analysis (EDA)
- Pivot Tables and Cross-Tabulation
- Comparative and Financial Analysis
- Microsoft Power BI
- DAX Measures
- Data Modeling
- Interactive Data Visualization
- KPI Development
- Time-Based Analysis

### Analytical Skills

- Problem Understanding
- Data Quality Assessment
- Demographic Analysis
- Trend Analysis
- Financial Pattern Identification
- Scenario Analysis
- Business Insight Generation
- Analytical Storytelling
- Business Recommendations

---

## 🎓 15. Conclusion

The Hospital Data Analytics Project provided an opportunity to apply practical data analytics techniques to a healthcare-focused business problem.

Starting with 10,000 raw patient records, I performed data cleaning, transformation, exploratory analysis, demographic comparisons, financial analysis, and admission trend investigation using Microsoft Excel and Power Query.

The analytical outputs were then translated into a five-page interactive Power BI report using DAX measures, visualizations, KPI cards, and interactive filters.

The project helped strengthen my ability to work with structured datasets, identify meaningful patterns, develop interactive dashboards, and communicate findings through business-oriented recommendations.

**The ultimate objective was not just to visualize data, but to transform raw records into meaningful information that can support better analytical understanding and operational decision-making.**

---

## 👨‍💻 Author

### Pratham Pulkeet

**Aspiring Data Analyst | Excel | Power BI | SQL | Python**

<p align="left">
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="YOUR_GITHUB_URL">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<p align="center">
  ⭐ If you find this project interesting, feel free to explore the repository!
</p>

<p align="center">
  <sub>This project was developed for educational and portfolio purposes. The dataset is used as an analytical example and should not be interpreted as verified real-world hospital performance or clinical evidence.</sub>
</p>
