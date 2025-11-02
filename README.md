# Python Homework: Payroll Data Analysis

**Overview**

This assignment focused on practicing core Python data analysis techniques using Pandas and NumPy. The project involved exploring a payroll dataset containing over 148,000 employee records across multiple U.S. states and years. The goal was to perform data cleaning, aggregation, and exploratory analysis to understand wage patterns, job distribution, and compensation trends.

Each step was completed as part of a structured set of exercises designed to test fluency in data handling, transformation, and analysis.

**Dataset**

- File: payroll.csv
- Size: 148,550 rows × 8 columns

Key Variables:

- ID, Name, Title, Wage, Bonus, Benefits, Year, State
- Derived variable: TotalPay = Wage + Bonus + Benefits

---

**Analysis and Tasks Completed**

- Imported and inspected the dataset using Pandas (df.head(), df.shape, df.dtypes).
- Sorted records by ID and verified dataset dimensions.
- Created a TotalPay column combining wage, bonus, and benefits.
- Calculated descriptive statistics:
-   Minimum, maximum, and average total pay.
-   Number of employees earning above average.
- Queried specific records:
-   Found employee details for Michael J. Proctor.
-   Identified the person with the highest wage overall.
- Aggregated data:
-   Employee counts by year and by state (e.g., NY-only results).
-   Average total pay per year and for NY/NJ employees.
- Performed data cleaning:
-   Checked for missing values.
-   Filled missing wages with the column mean.
- Grouped and filtered for insights:
-   Highest wage by year.
-   Most common job titles and their frequencies.
-   Count of unique and one-off titles per year.
-   Number of police-related titles outside NY.

---

**Tools and Skills**

- Python (Pandas, NumPy)
- Data cleaning and preprocessing
- Grouping and aggregation with groupby()
- Conditional filtering and Boolean indexing

---
Statistical summary and descriptive analytics

Iterative logic and validation (for loops, .idxmax(), .isnull())
