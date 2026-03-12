# BOYCODE 4.0 – Data Analysis Assignments Portfolio
**Joseph Ngui**

> "I started with little knowledge of data analysis, but through Mr. Edu's excellent teaching in BOYCODE 4.0, I gained solid skills in Excel, Power BI, SQL, data cleaning, exploratory analysis, and visualization."

One-sentence summary:  
This repository contains my completed assignments and projects from the BOYCODE 4.0 data analysis course, demonstrating end-to-end skills from data wrangling to insight generation and dashboard creation.

⚙️ Project Type Flags  
(Check what applies across the portfolio)

- Exploratory Data Analysis (EDA)  
- SQL Analysis / Querying  
- Dashboard / Data Visualization  
- Data Cleaning / Wrangling  
- End-to-End (multiple of the above)

## Table of Contents

1. [Course Overview & Learning Journey](#1-course-overview--learning-journey)
2. [Objectives](#2-objectives)
3. [Tools & Technologies](#3-tools--technologies)
4. [Repository Structure](#4-repository-structure)
5. [Assignments Overview](#5-assignments-overview)
6. [Key Insights & Findings](#6-key-insights--findings)
7. [Recommendations & Lessons Learned](#7-recommendations--lessons-learned)
8. [Assumptions & Limitations](#8-assumptions--limitations)
9. [Future Enhancements](#9-future-enhancements)
10. [Author](#10-author)

## 1. Course Overview & Learning Journey

**Context**: BOYCODE 4.0 data analysis bootcamp/track – focused on practical skills for real-world data roles.  
**Problem/Goal**: Build foundational to intermediate proficiency in data handling, querying, visualization, and storytelling from raw data.  
**Approach**: Weekly assignments covering Excel cleaning, SQL querying, and Power BI dashboards on various datasets (possibly including layoffs, HR, sales, etc.).  
**Outcome**: A portfolio demonstrating clean code, thoughtful analysis, professional visualizations, and business-oriented insights.

## 2. Objectives

- Primary: Complete all BOYCODE 4.0 assignments with high-quality documentation, code, and visuals.  
- Demonstrate ability to clean messy data, write efficient SQL, create insightful Power BI reports, and communicate findings.  
- Build confidence and portfolio pieces for future data analyst opportunities.

## 3. Tools & Technologies

| Category          | Tool(s) Used                  |
|-------------------|-------------------------------|
| Data Storage      | CSV / Excel files             |
| Data Processing   | Excel, SQL                    |
| Analysis          | SQL queries, Excel formulas   |
| Visualization     | Power BI                      |
| Version Control   | GitHub                  |
| Documentation     | Markdown (this README)        |

## 4. Repository Structure
JOSEPH-NGUI.-assignments-BOYCODE-4.0/
│
├── data/                 # Raw + processed datasets used in assignments
├── visuals/              # Exported charts, dashboard screenshots, Power BI exports
├── .gitignore
└── README.md             # You are here

## 5. Assignments Overview

This portfolio contains **7 key assignments** from the BOYCODE 4.0 Data Analysis course. Each one built progressively on the previous skills, starting with Excel fundamentals and ending with SQL.

**Assignment 1: Excel Basic Calculations & Statistics**  
Exercises 3, 3.5 & 5 – Calculated average, minimum, maximum, total sales, sales tax, number of customers, and counts.  
**Skills used**: Excel formulas (AVERAGE, MIN, MAX, SUM, COUNT).  
**Location**: `data/processed/` + basic tables (screenshots available in visuals/).

**Assignment 2: Excel Formatting & Conditional Logic**  
Exercises 1 & 2 – Applied cell styling, coloring, conditional formatting, total & cell stacks, basic IF functions, and COUNTIFS.  
**Skills used**: Formatting, conditional formatting, logical functions.  
**Location**: `data/processed/` (screenshots in visuals/).

**Assignment 3: Excel Charts & Visualization**  
Built and formatted various charts, combined column charts with line charts, and learned chart customization.  
**Skills used**: Chart creation, formatting, and mixing chart types.  
**Location**: `data/processed/` + exported charts.

**Assignment 4: Power BI Introduction – Billionaire Dashboard**  
Created tables, queries, DAX formulas, and built a complete Billionaire Dashboard.  
**Skills used**: Power BI Desktop, data modeling, visuals, and measures.  
**Location**: `data/processed/` + `visuals/Screenshot 2026-03-06 001212.png` (shows the JOSEPH DASHBOARD).

**Assignment 5: Power BI Data Modeling – Superstore Sales**  
Used Superstore dataset to establish relationships between tables and create interactive charts.  
**Skills used**: Data modeling, relationships, and dashboard building in Power BI.  
**Location**: `data/raw/` & `data/processed/`.

**Assignment 6: End-to-End HR Dashboard Project**  
Received messy HR data → cleaned it in Excel → built tables & DAX formulas in Power BI → delivered a professional HR Dashboard.  
**Skills used**: Full data cleaning, Power Query, DAX, dashboard design, and storytelling.  
**Location**: `data/raw/`, `data/processed/`, and visuals (includes WhatsApp Image 2026-03-06 at 12.05.20 AM.jpeg).

**Assignment 7: SQL – Parks and Recreation Database**  
Created tables, ran queries, and practiced database fundamentals on the Parks & Recreation sample database.  
**Skills used**: SQL (CREATE TABLE, SELECT, INSERT, basic joins & aggregations).  
**Location**: SQL script files (or queries folder if added later).

---

## 6. Key Insights & Findings

- **Insight 1: Data cleaning is the foundation of everything**  
  The HR dataset was extremely messy (missing values, inconsistent formatting). After cleaning the data in Excel and loading it into Power BI, clear patterns that were invisible before emerged, proving that 70–80% of analysis time should be spent on preparation.

- **Insight 2: Conditional formatting and COUNTIFS reveal hidden stories**  
  Using IF and COUNTIFS in Assignment 2 instantly highlighted top performers, outliers, and problem areas in sales/customer data that raw numbers hid.

- **Insight 3: Combined charts tell better stories than single visuals**  
  In Assignment 3, overlaying a line chart on a column chart showed the relationship between sales volume and profit margin over time — something a single chart could not communicate.

- **Insight 4: Power BI relationships unlock multi-table analysis**  
  The Superstore dataset only made sense after proper one-to-many relationships were created. This allowed accurate profit-by-category and sales-by-region breakdowns.

- **Insight 5: SQL turns raw data into instant answers**  
  Simple queries on the Parks and Recreation database instantly answered questions like “How many employees per department?” and “Who has the highest salary?” — skills that will be used daily in real jobs.

## 7. Recommendations & Lessons Learned

**Key Recommendations**
- Always keep raw data untouched (`data/raw/`) and work only on copies in `processed/`.
- Document every cleaning step — it saved me hours when I had to revisit the HR project.
- Use DAX measures instead of calculated columns in Power BI for better performance.
- Test SQL queries on small datasets first before scaling.

**Lessons Learned**
- Conditional formatting and IF/COUNTIFS functions are extremely powerful even in basic Excel.
- Power BI dashboards look professional only when you limit to 4–6 key visuals per page.
- Messy real-world data (like the HR file) is normal — the skill is turning it into something clean and useful.
- SQL is faster than Excel for large datasets; I wish I had learned it earlier.


## 8. Assumptions & Limitations

**Assumptions**
- All datasets used were provided by the instructor or were available.
- Calculations (tax, sales totals, etc.) followed standard business rules taught in class.
- Screenshots represent final outputs; live .pbix files are available on request.

**Limitations**
- Some assignments were time-constrained (weekly submissions), so analysis remained at an intermediate level.
- The Parks & Recreation database is a training set, not real company data, that had tons of issues when it comes to cleaning and analyzing it.
 
## 9. Future Enhancements

- Include more advanced SQL (CTEs, window functions, stored procedures).
- Build a capstone project combining Excel, Power BI, and SQL in one end-to-end pipeline for one detailed project.

## 10. Author

**Joseph Ngui**  
BOYCODE 4.0 Data Analysis Student

- 🔗 [LinkedIn](https://www.linkedin.com/in/joseph-ngui-b244a6333/)  
- 💼 [GitHub](https://github.com/mogvin)  
- 📧 jose.k.ngui@gmail.com

Last updated: March 2026 
