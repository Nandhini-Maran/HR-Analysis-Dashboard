# HR Analytics Dashboard using Power BI 

## 🔗 Objective
The **HR Analytics Dashboard** is designed to analyze HR data, uncover workforce trends, identify key factors driving employee attrition, and provide actionable recommendations for improving employee retention. This interactive dashboard enables HR professionals to make data-driven decisions for effective workforce management.

## 📈 Features & Insights
- **Total Employee Count** – Overview of the total workforce in the organization.
- **Attrition Analysis** – Breakdown of employees who left, categorized by gender, department, and other key factors.
- **Demographic Insights** – Age distribution, education levels, business travel frequency, and gender diversity.
- **Department-Wise Analysis** – Identification of departments with the highest attrition rates.
- **KPI & Trend Analysis** – Key performance indicators (KPIs), headcount trends, and workforce distribution.
- **Interactive Visuals** – Bar charts, pie charts, treemaps, matrix tables, and slicers for dynamic data exploration.
- **Filtering Options** – Users can filter data by business unit, country, age group, education, and job roles.
- **Data Export** – Option to export HR insights for further reporting and strategic planning.

## 📂 Steps Followed
### 1️⃣ Data Gathering
- Imported raw data from an **Excel file (Employee Sample Data.xlsx)** into Power BI.
- Transformed data using Power Query Editor for cleaning and processing.

### 2️⃣ Data Cleaning
- Removed empty columns, duplicates, and errors.
- Standardized column names and replaced inconsistent values.
- Ensured proper data types for each column.

### 3️⃣ Data Processing
- Created an **AttritionCount** column (1 if Attrition = "Yes", else 0).
- Developed key **DAX measures**, including:
  ```DAX
  Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount])
  ```
- Created calculated fields for **Active Employees, Total Attrition**, and other essential HR metrics.

### 4️⃣ Data Analysis & Visualization
- Designed **interactive dashboards** with key HR insights:
  - **Employee Count Overview** (KPI Cards, Bar Charts)
  - **Attrition Analysis** (Pie Charts, KPI Cards)
  - **Employee Age Distribution** (Clustered Column Charts)
  - **Business Unit & Country-Wise Headcount** (Treemaps, Bar Charts)
  - **Job Role Analysis** (Bar Charts, Matrix Tables)

## 👀 Key Questions Answered in the Dashboard
- **How many employees are currently in the organization?**
- **What is the attrition count for males and females?**
- **Which department has the highest employee count?**
- **Which job role experiences the highest attrition?**
- **Which business travel category has maximum employees?**
- **What is the average working years of employees?**

## 📊 Key Insights Summary
- **Total Employees:** The organization has **1,470 employees**, indicating stability.
- **Attrition Count:** A total of **237 employees left** (150 males, 87 females).
- **Highest Attrition Department:** Research & Development has the **highest attrition rate (56.13%)**.
- **Education Impact:** Employees from **Life Sciences** have the highest attrition rate.
- **Job Role at Risk:** Sales Department experiences the **highest attrition**.
- **Attrition by Age Group:** Maximum attrition occurs in employees **aged 25-34 years**.

## 🎨 Dashboard Preview
### **HR Analysis Dashboard Summary:**
- Provides a comprehensive **overview of key HR metrics**.
- **Visuals include:**
  - **Total Employee Count**![image](https://github.com/user-attachments/assets/36fcbde5-1441-43ac-9736-160adc0615d5)
  - **Employee Distribution by Gender![image](https://github.com/user-attachments/assets/7128c44c-f6ad-4170-a23f-2ce9fe157ea9)
, Age![image](https://github.com/user-attachments/assets/ae51dc30-28d3-4135-af7e-b2d090ee9a8c)
, and Country![image](https://github.com/user-attachments/assets/f3827198-29d3-4bf1-8ca6-e0e449667a24)
**
  - **Headcount Trends Over Time![image](https://github.com/user-attachments/assets/9a25a716-e188-4d50-ad56-93ca40896239)
**
  - **Department-Wise Breakdown![image](https://github.com/user-attachments/assets/ab7cffde-f8c2-4737-8858-c5af6e3e0204)
**

### **HR Dashboard Overview:**
- **Metadata includes:**
  - **Data Source:** Employee Sample Data.xlsx
  - **Data Refresh Frequency:** Every Friday
  - **Last Updated On:** March 11, 2025
  - **Contact:** hr.sample@gmail.com

## 📚 Data Source
- **Employee Sample Data.xlsx (Excel)**

## 🛠️ Tools & Technologies Used
- **Power BI** – Data visualization & interactive dashboard creation.
- **DAX (Data Analysis Expressions)** – For KPI calculations and insights.
- **Power Query** – For data transformation and processing.

## 🚀 How to Use This Dashboard?
1. Download the **HR Analysis Dashboard.pbix** file.
2. Open it in **Power BI Desktop**.
3. Navigate through the pages (HR Summary, HR Analysis) using the left-side menu.
4. Apply **filters** to customize the view based on country, business unit, and employee attributes.
5. Hover over visuals for **detailed insights**.
6. Use the **export option** to download HR insights for further reporting.

## 🎯 Future Enhancements
- **Advanced DAX Measures** for deeper workforce insights.
- **SQL Integration** for additional data filtering and analysis.
- **Enhanced Interactivity** with more slicers and drill-through pages.
- **Predictive Analysis** to forecast attrition trends.

## 📉 Dashboard
- **Summary![image](https://github.com/user-attachments/assets/585b8210-7209-4850-96f7-2f683427c735)
**
- **HR Analysis![image](https://github.com/user-attachments/assets/3c102d4b-dad1-46a9-be02-a129c52d1b2f)
**
## 📝 Conclusion
This **HR Analytics Dashboard** empowers HR teams to make **data-driven decisions**, optimize workforce management, and reduce attrition. By leveraging **Power BI** for interactive visualizations and insights, businesses can proactively address workforce challenges. Future improvements, such as **predictive analytics and advanced DAX calculations**, will further enhance the dashboard’s capabilities.

## 📚 License
This project is **open-source** and free to use for educational purposes.
