# Student Performance & Study Behavior Analytics

An interactive, end-to-end data analysis and visualization dashboard built entirely in Microsoft Excel. This project analyzes the relationships between student demographics, attendance rates, study habits, and final academic outcomes for a cohort of 500 students.

## 📊 Live Dashboard Preview
*The dashboard features dynamic KPIs, cross-tabulated performance metrics, a study-hour correlation scatter plot, and multi-report connected slicers for interactive data storytelling.*

---

## 🚀 Project Overview & Objectives
The goal of this project was to transform raw student behavioral data into actionable insights for educators and academic administrators. The analysis focuses on:
*   Identifying key behavioral drivers (attendance, study hours) behind high academic performance.
*   Segmenting student outcomes by demographic factors like gender.
*   Building an early-warning tracking metric to easily isolate and flag "At-Risk" students needing immediate academic intervention.

## 🛠️ Data Pipeline & Workflow

### 1. Data Cleaning & Profiling (`Clean Data` Tab)
*   **Sanity Checks:** Handled missing values, standardized formatting, and prepared structural columns for analytical workflows.
*   **Feature Engineering:** Engineered custom logical metrics using nested formulas (e.g., `IFS` statements to segment students into *Excellent*, *Good*, and *Needs Improvement* performance tiers).
*   **Data Profiling:** Applied conditional formatting and conditional data bars to visually audit distributions and instantly flag at-risk records.

### 2. Aggregation & Segment Analysis (`Pivot Analysis` Tab)
*   Leveraged **Pivot Tables** to run cross-tabulations across multiple dimensions.
*   Analyzed the direct correlation between average scores and granular categorical buckets (e.g., separating trends by Attendance Groups: *High*, *Medium*, *Low*).

### 3. Interactive Visualization (`Final Dashboard` Tab)
*   **Dynamic KPIs:** Tracks core metrics globally (`Average Score`, `Total Students`, `Max Score`, `At-Risk Count`).
*   **Interactive Slicers:** Implemented multi-report connected Slicers (*Performance*, *Gender*, *Attendance Group*), allowing users to filter the entire dashboard view simultaneously.
*   **Visual Elements:** Combined bar charts, pie charts, and a scatter plot to map numeric distributions and catch correlation outliers.

---

## 📈 Key Insights Discovered
*   **Attendance Matters Most:** High attendance rates show a direct, measurable link to higher average exam scores ($84.52$ average score for high attendance vs. $62.67$ for low attendance).
*   **Performance Distribution:** The vast majority of the student cohort falls into the *Good* or *Excellent* performance categories, with only a small margin ($14$ students) flagged as *At-Risk*.
*   **Demographic Trends:** Female students slightly outperform male counterparts in overall average scores within this specific dataset.

---

## 💻 Tech Stack Used
*   **Tool:** Microsoft Excel
*   **Features:** Advanced Formulas (`IFS`, `AVERAGE`, `COUNTIF`), Power Query (Data Transformation), Pivot Tables, Pivot Charts, Report-Connected Slicers, Conditional Formatting.
