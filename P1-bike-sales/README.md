# Bike Sales Dashboard — Excel Portfolio Project

**Tool:** Microsoft Excel  
**Stage:** Stage 1 — Excel for Data Analysis (Project P1)  
**Dataset:** [Alex the Analyst — Excel Project Dataset](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)  
**Tutorial followed:** [Learn Excel in Under 3 Hours — Alex the Analyst](https://www.youtube.com/watch?v=zXnQNytHCPM)

---

## Project Overview

This is the first project in my data analyst portfolio, built by following Alex the Analyst's Excel tutorial. The goal was to take a raw bike sales dataset, clean it, analyse it with pivot tables, and present findings in an interactive dashboard — all within Excel.

The dataset contains 1,000 customer records across Europe, North America, and the Pacific, with demographic and behavioural attributes used to understand who purchased a bike and who didn't.

---

## What I Did

### 1. Data Cleaning
- Removed duplicate rows
- Expanded abbreviations in the **Marital Status** column (`M` → `Married`, `S` → `Single`) and **Gender** column (`M` → `Male`, `F` → `Female`) for readability
- Removed decimal points from the **Income** column and changed the data type to **Currency**
- Created a new **Age Range** column using nested IF statements to group customers into three brackets: `Adolescent` (under 31), `Middle Age` (31–54), and `Old` (55+)

### 2. Pivot Tables & Charts
Built three pivot tables and corresponding charts, each exploring a different driver of bike purchases:

| Chart | What it shows |
|---|---|
| **Average Income per Purchase** | Average income by gender, split by whether a bike was purchased — showing higher earners were more likely to buy |
| **Customer Commute** | Bike purchase rates across commute distance brackets — shorter commutes show stronger purchase rates |
| **Customer Age Brackets** | Purchase counts by age group — Middle Age customers dominate purchases |

### 3. Dashboard
- Combined all three charts onto a single **Dashboard sheet**
- Added **three slicers** connected to all charts simultaneously: Marital Status, Region, and Education
- Slicers allow filtering the entire dashboard to explore how different customer segments behave

---

## Key Findings

- **Middle-aged customers (31–54)** make up the largest group of bike buyers by a significant margin
- **Higher-income customers** across both genders are more likely to purchase — the gap is especially visible in male customers
- **Short commuters (0–1 miles)** show the highest purchase counts, suggesting bikes are seen as a practical short-distance option rather than a long-distance commute solution

---

## Files

| File | Description |
|---|---|
| `Bike_Sales_-_Alex_the_Analyst.xlsx` | Cleaned dataset, pivot tables, charts, and interactive dashboard |

---

## Skills Demonstrated

- Data cleaning in Excel (deduplication, find & replace, data types)
- Nested IF statements for calculated columns
- Pivot tables and pivot charts
- Interactive dashboard design with slicers
- Translating raw data into written findings

---

## Part of a Larger Learning Path

This project is **P1 of 13** in my structured data analyst workplan, progressing from Excel and Power BI through SQL, Python, and eventually machine learning applied to neurological and public health research.
