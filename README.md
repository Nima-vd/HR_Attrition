# 📊 HR Attrition & Retention Analysis | Power BI

> **End-to-end HR Analytics project analyzing employee attrition, workforce patterns, and retention factors using Excel, Power Query, DAX, and Power BI.**

---

## 📌 Project Overview

Employee attrition can impact organizations through increased recruitment costs, productivity loss, and the loss of experienced employees.

This project analyzes the **IBM HR Employee Attrition dataset** to identify patterns associated with employee turnover and transform raw HR data into an **interactive Power BI dashboard**.

The analysis focuses on understanding **who is leaving, where attrition is concentrated, and which workforce factors are associated with higher attrition**.

### Key Business Questions

* What is the overall employee attrition rate?
* Which departments and job roles have the highest attrition?
* How does attrition vary by employee tenure?
* Is employee income associated with attrition?
* How does business travel relate to employee turnover?
* What patterns exist across overtime, job satisfaction, and work-life balance?
* Which employee groups may require further investigation for retention?

> ⚠️ **Analytical Note:** The findings represent associations observed in the dataset and should not be interpreted as proof of causation.

---

# 🎯 Project Objectives

* Analyze overall workforce composition and employee attrition.
* Identify departments and job roles with higher attrition.
* Explore attrition across demographic and employment characteristics.
* Analyze relationships between income, tenure, travel, overtime, and attrition.
* Examine employee satisfaction and work-life balance indicators.
* Build an interactive HR analytics dashboard in Power BI.
* Translate analytical findings into meaningful business insights.

---

# 🔄 Project Workflow

**Excel → Power Query → Data Transformation → Data Modelling → DAX → Power BI → Business Insights**

### 1. Data Preparation

* Imported and reviewed the HR employee dataset.
* Checked data quality and consistency.
* Identified relevant demographic, employment, satisfaction, and attrition fields.

### 2. Data Transformation

* Used **Power Query** for data cleaning and transformation.
* Prepared fields for analysis and visualization.
* Created calculated columns where required.

### 3. Data Modelling

* Structured the dataset for Power BI analysis.
* Organized fields and relationships.
* Created a model suitable for interactive reporting.

### 4. DAX Analysis

Created measures and calculations for key HR metrics, including:

* Attrition Rate
* Employee Headcount
* Average Income
* Average Age
* Attrition by Department
* Attrition by Job Role
* Attrition by Tenure
* Attrition by Demographic Factors

### 5. Dashboard Development

Built a **3-page interactive Power BI dashboard** using slicers, bookmarks, custom sorting, KPI cards, navigation, and interactive visualizations.

### 6. Business Analysis

Interpreted dashboard results to identify workforce patterns and potential areas for further HR investigation.

---

# 📊 Dashboard

The Power BI dashboard contains **three analytical pages**, supported by an additional **Insights & Recommendations** view.

## 1️⃣ HR Attrition Overview

Provides a high-level view of the organization's workforce and attrition.

### Key Metrics

* Attrition Rate
* Employee Headcount
* Average Income
* Average Age

### Analysis

* Department
* Job Role
* Gender
* Age
* Employee Attrition

---

## 2️⃣ Attrition Analysis

Provides a deeper analysis of employee attrition across workforce characteristics.

### Factors Analyzed

* Income
* Tenure
* Education
* Marital Status
* Business Travel
* Distance From Home
* Department
* Job Role

This page helps identify **employee segments where attrition is more concentrated**.

---

## 3️⃣ Employee Retention & Satisfaction

Examines workforce factors that may provide useful signals for retention analysis.

### Factors Analyzed

* Overtime
* Job Satisfaction
* Work-Life Balance
* Years Since Promotion
* Job Involvement

The objective is to understand how employee experience indicators differ across the workforce.

---

## 4️⃣ Insights & Recommendations

Summarizes the major findings from the analysis and translates them into potential areas for HR investigation.

The page connects:

**Finding → Interpretation → Potential Business Action**

> Recommendations are based on patterns observed in the dataset and should be validated with additional organizational and employee-level information before implementation.

---

# 🔎 Key Insights

### 📌 Early-Tenure Attrition

Employee attrition is highest during the **first year of employment**, highlighting the importance of examining onboarding and the early employee experience.

### 📌 Income & Attrition

Lower-income employees show **substantially higher attrition** compared with higher-income employees.

### 📌 Business Travel

Employees with frequent business travel show **higher attrition**, making travel requirements an area worth investigating further.

### 📌 Department & Job Role

Attrition is not evenly distributed across the organization. Certain **departments and job roles show higher attrition**, suggesting that retention strategies may need to be targeted rather than one-size-fits-all.

> **Important:** These findings describe patterns and associations within the dataset. Further analysis would be required to establish causal relationships.

---

# 🛠️ Tools & Technologies

| Technology          | Purpose                              |
| ------------------- | ------------------------------------ |
| **Microsoft Excel** | Data inspection and preparation      |
| **Power Query**     | Data cleaning and transformation     |
| **Power BI**        | Interactive dashboard development    |
| **DAX**             | Measures and analytical calculations |
| **Data Modelling**  | Structuring data for analysis        |

### Power BI Features

* KPI Cards
* DAX Measures
* Calculated Columns
* Interactive Slicers
* Bookmarks
* Custom Sorting
* Page Navigation
* Interactive Visualizations
* Reset Filters Button
* Dashboard UX Design

---

# 💼 Business Value

This project demonstrates how HR data can be transformed into insights that support **data-driven workforce decisions**.

The dashboard can help HR teams:

* Monitor employee attrition.
* Identify high-attrition departments and roles.
* Compare workforce segments.
* Investigate potential retention signals.
* Support workforce planning.
* Identify areas for deeper HR investigation.
* Move from descriptive reporting toward analytical decision-making.

### The analytical approach

**Data → Insight → Investigation → Business Decision**

---

# 📁 Repository Structure

```text
HR-Attrition-PowerBI/
│
├── 📊 HR Attrition PowerBI Dashboard.pdf
├── 📄 IBM-HR-Employee-Attrition cleaned.csv
│
├── 🖼️ HR Attrition Overview.png
├── 🖼️ Attrition Analysis.png
├── 🖼️ Employee Retention.png
├── 🖼️ Insights and Recommendations.png
│
└── 📖 README.md
```

---

# 📷 Dashboard Preview

### HR Attrition Overview

![HR Attrition Overview](HR%20Attrition%20Overview.png)

### Attrition Analysis

![Attrition Analysis](Attrition%20Analysis.png)

### Employee Retention

![Employee Retention](Employee%20Retention.png)

### Insights & Recommendations

![Insights and Recommendations](Insights%20and%20Recommendations.png)

---

# 📈 Skills Demonstrated

### Data Analytics

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* KPI Analysis
* Workforce Analytics
* HR Analytics
* Business Insight Generation

### Power BI

* Dashboard Development
* DAX
* Power Query
* Data Modelling
* Interactive Visualizations
* Slicers
* Bookmarks
* Page Navigation
* Dashboard UX

### Analytical Thinking

* Pattern Identification
* Comparative Analysis
* Correlation vs. Causation
* Business Problem Solving
* Data Storytelling
* Insight Generation

---

# 🚀 Future Improvements

Potential enhancements for this project include:

* Developing employee attrition risk segmentation.
* Adding advanced DAX calculations.
* Creating additional HR retention KPIs.
* Incorporating historical workforce data for trend analysis.
* Building a predictive attrition model using machine learning.
* Connecting the dashboard to a regularly refreshed data source.
* Adding automated reporting for HR stakeholders.

---

# 👨‍💻 About Me

I'm **Nima Norbu Sherpa**, a Computer Science graduate focused on building practical projects in **Data Analytics and Business Intelligence**.

### Technical Focus

**Power BI | SQL | Excel | Python | DAX | Power Query | Data Visualization | Business Intelligence**
---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a **⭐ Star**.

Thank you for visiting!
