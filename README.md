# Student Performance & Operations Analytics Dashboard

An end-to-end data analytics project that cleanses relational database tables, aggregates performance records, and builds an interactive multi-page executive dashboard for educational insights.

## 📊 Dashboard Preview
![Executive Dashboard](dashboard_preview.png)

---

## 📂 Project Repository Structure

Click on any file link below to view the database architecture, source data, or core business intelligence files:

### 1. Core BI & Source Files
* **Power BI Desktop Report:** 🛠️ [Student Grade Power BI.pbix](Student%20Grade%20Power%20BI.pbix) *(Download to view interactive model)*
* **Master SQL Database Script:** 💾 [Student Grade Main.sql](Student%20Grade%20Main.sql) *(Table creations, keys, data constraints, and initial seeding)*

### 2. Relational Database Tables (Source Excel Sheets)
These files represent the core relational database tables staged and modeled inside Power BI:
* 👤 [Students Table](Student%20Grade%20Excel%20File.xlsx%20-%20Students.csv)
* 📚 [Courses Table](Student%20Grade%20Excel%20File.xlsx%20-%20Courses.csv)
* 📝 [Exams Performance Table](Student%20Grade%20Excel%20File.xlsx%20-%20Exams.csv)
* 📅 [Attendance Records Table](Student%20Grade%20Excel%20File.xlsx%20-%20Attendance.csv)
* 💳 [Financial Payments Table](Student%20Grade%20Excel%20File.xlsx%20-%20Payments.csv)
* 🏫 [Enrollments Mapping Table](Student%20Grade%20Excel%20File.xlsx%20-%20Enrollments.csv)
* 🧑‍🏫 [Instructors Table](Student%20Grade%20Excel%20File.xlsx%20-%20Instructors.csv)

### 3. Aggregated Model Insights & Staging Views
Processed data views used to directly feed the specific visualizations:
* 📊 [Master Analysis Data Table](Student%20Grade%20Excel%20File.xlsx%20-%20Analysis%20Data.csv)
* 📈 [Average Score By Department](Student%20Grade%20Excel%20File.xlsx%20-%20Average%20Score%20By%20Department.csv)
* 🏆 [Top Scorer By Course View](Student%20Grade%20Excel%20File.xlsx%20-%20Top%20Scorer%20By%20Course.csv)
* 💰 [Payment Analysis Metrics](Student%20Grade%20Excel%20File.xlsx%20-%20Payment%20Analysis.csv)
* ⏳ [Attendance vs Score Analytics](Student%20Grade%20Excel%20File.xlsx%20-%20Attendance%20vs%20Score.csv)

---

## 🔑 Key Insights Delivered

1.  **Academic Performance:** Identified top-performing engineering domains (Computer Science leading at an 88.00 average) and cataloged peak course metrics.
2.  **Operational Attendance:** Tracked distinct category frequencies across Present, Absent, Excused, and No Record statuses to flag low engagement.
3.  **Financial Summary:** Standardized financial data models to track sum allocations, mapping total student-level financial revenue contributions.

## 🛠️ Tools & Technologies Used
* **Database Engine:** Microsoft SQL Server (Relational Design, Primary/Foreign Key mappings)
* **Data Staging & ETL:** Microsoft Excel & Power Query
* **Business Intelligence:** Power BI Desktop (Data Modeling, Page Navigation, Custom Data Labels)
* **Version Control:** Git & GitHub
