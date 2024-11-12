**Project: Employee Performance and Demographics Analysis**

Tools: Python, Pandas, Seaborn, Matplotlib

**Objective:**

Conducted exploratory data analysis on a company’s employee dataset to understand factors influencing employee performance and tenure.

**Data Cleaning & Preparation:**

Imputed missing values in previous_year_rating using median values.
Removed missing values in education and duplicates.
Renamed columns for clarity and removed irrelevant fields (e.g., employee_id).

**Exploratory Data Analysis (EDA):**

Age Distribution: Discovered that the employee age distribution is right-skewed, with most employees aged 30–45.
Education Analysis: Found that employees with Bachelor’s and Master’s degrees achieved higher KPI>80 scores than those with lower education levels.
Department Performance: Analyzed department performance metrics, revealing that Operations and Sales & Marketing have the highest performance (KPI>80), while Legal and R&D departments scored lower.
Training Score Analysis: Found that previous year’s performance rating had little influence on current average training scores, indicating consistent training performance across the board.
Age vs. Tenure Correlation: Identified a strong positive correlation between age and tenure, with older employees typically staying longer.
Recruitment Channel Performance: Observed that employees hired through "Other" and "Sourcing" channels performed better than those referred.

**Visualizations:**

Created bar charts, histograms, and box plots to visualize distributions and trends in age, education, and department performance.
Generated heatmaps to examine correlations between variables like age, tenure, and training scores.

**Key Findings:**

Departments and education levels are strong indicators of employee performance.
Age and tenure are positively correlated, with older employees staying longer.
Recruitment channel impacts performance, with direct sourcing yielding better results.
