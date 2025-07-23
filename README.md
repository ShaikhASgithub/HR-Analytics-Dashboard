# **HR Analytics Dashboard: Workforce Attrition Insights**

An interactive data visualization tool designed to analyze employee attrition trends across departments, age groups, education levels, salary bands, and job roles—empowering HR professionals to uncover patterns, address pain points, and improve retention strategies.

---

## 🔹 **Short Description / Purpose**

The HR Analytics Dashboard is a comprehensive Power BI report aimed at helping organizations monitor and reduce employee attrition. It provides in-depth visibility into employee demographics, job satisfaction, and compensation structures to identify key drivers of workforce turnover.

---

## 🛠️ **Tech Stack**

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Used to design, develop, and visualize all analytical components.
- 📂 **Power Query Editor** – Employed for cleaning, reshaping, and transforming raw CSV data.
- 🧠 **DAX (Data Analysis Expressions)** – Applied for dynamic KPIs, attrition rates, and conditional formatting.
- 📝 **Data Modeling** – One centralized dataset with relationships to support cross-filtering by job role, education, and department.
- 📁 **File Format** – `.pbix` for Power BI development; `.csv` as the source file for HR data input.

---

## 📂 **Data Source**

**Source:** Internal HR Department (`HR_Analytics.csv`)  
The dataset includes 1,470 employee records with attributes such as age, department, education, gender, salary, job satisfaction, attrition status, job role, and years of service. Attrition status is recorded as "Yes" or "No," allowing direct measurement of employee turnover and its distribution.

---

## 📌 **Features / Highlights**

### • **Business Problem**  
High employee attrition affects operational continuity, increases recruitment costs, and reduces organizational efficiency. HR teams often lack clear visibility into which roles, departments, or demographics are most at risk of turnover, making it difficult to plan effective retention strategies.

**Key questions include:**
- What job roles and salary ranges are most affected by attrition?
- Is attrition higher among younger employees or certain departments?
- How does education or job satisfaction impact employee retention?

---

### • **Goal of the Dashboard**

To create a dynamic HR tool that:
- Identifies attrition patterns across departments, roles, and demographics.
- Supports HR decision-making through interactive visual analysis.
- Enables proactive workforce planning and improved employee engagement strategies.

---

### • **Walkthrough of Key Visuals**

**KPI Panel (Top Cards):**
- Count of Employees: 1,470  
- Attrition Count: 237  
- Attrition Rate: 16.1%  
- Average Age: 37  
- Average Salary: ₹6.5K  
- Average Years of Experience: 7  

**Attrition by Age Group (Bar Chart):**  
Shows that the 26–35 age group has the highest attrition count (116), indicating younger professionals may be more likely to leave.

**Attrition by Gender and Age (Stacked Bar Chart):**  
Compares attrition counts for males (140) and females (79), giving insights into gender-based retention trends.

**Attrition by Education (Donut Chart):**  
Life Sciences and Medical education backgrounds dominate attrition counts, which may indicate skill-specific retention issues.

**Attrition by Salary (Bar Chart):**  
Most attrition occurs in employees earning less than ₹5K—highlighting salary as a potential retention factor.

**Attrition by Job Role (Horizontal Bar Chart):**  
Key roles affected include:
- Laboratory Technician (62)
- Sales Executive (57)
- Research Scientist (47)
- Sales Representative (33)
- Human Resources (12)

**Attrition by Job Satisfaction (Matrix Table):**  
Cross-tab of satisfaction levels (1–4) and attrition count by job role—helps identify engagement gaps.

**Attrition Trend by Age (Line Chart):**  
Displays attrition frequency over specific age values, useful for identifying age brackets at high risk of leaving.

---

### • **Business Impact & Insights**

- **Retention Strategy:** HR can target low-salary and high-attrition roles with better engagement and compensation plans.  
- **Talent Management:** Helps in identifying vulnerable employee segments by age, role, and department.  
- **Workforce Planning:** Supports leadership in allocating resources where attrition risk is highest.  
- **Employee Engagement:** Job satisfaction insights allow HR to address dissatisfaction at its root.

---

## 🖼️ **Dashboard Preview**

![Dashboard Preview](https://github.com/ShaikhASgithub/HR-Analytics-Dashboard/blob/main/HR_Analystics_dashboard.PNG?raw=true)
