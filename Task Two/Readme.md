HR Data Cleaning & Statistical Analysis

📌 Project Overview

This project performs Data Cleaning, Exploratory Data Analysis (EDA), and Statistical Analysis on the IBM HR Analytics Employee Attrition & Performance dataset.

The dataset contains information about employee demographics, job characteristics, compensation, satisfaction, work experience, and employee attrition.

The main objective is to understand the structure and quality of the data, identify meaningful patterns and potential anomalies, and statistically examine relationships between employee characteristics and attrition.

This project was completed as part of the CodeAlpha Data Analytics Internship — Task 2: Exploratory Data Analysis (EDA).

---

🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Inspect data types and basic statistical summaries.
- Check for missing values and duplicate records.
- Detect invalid or potentially problematic values.
- Remove unnecessary and constant columns.
- Define meaningful business questions before analysis.
- Explore employee attrition across different variables.
- Analyze relationships between numerical and categorical variables.
- Perform statistical hypothesis testing.
- Detect potential outliers using the IQR method.
- Prepare a cleaned dataset for further analysis and visualization.

---

🗂️ Dataset Overview

The dataset contains:

- 1,470 employee records
- 35 columns before cleaning
- Demographic information
- Job and department information
- Salary and income information
- Employee satisfaction measures
- Work experience information
- Overtime status
- Employee attrition status

Target Variable

"Attrition"

- "Yes" → Employee left the company
- "No" → Employee stayed with the company

---

🧹 Data Cleaning

The following data quality checks were performed:

Missing Values

No missing values were found in the dataset.

Total Missing Values: 0

Duplicate Records

No duplicate rows were found.

Duplicate Rows: 0

Invalid Values

The analysis checked for invalid values in important numerical variables, including:

- Age
- Monthly Income
- Daily Rate
- Hourly Rate
- Monthly Rate
- Total Working Years
- Years at Company

No invalid values were detected according to the defined validation rules.

Unnecessary Columns

The following columns were removed:

- "EmployeeCount"
- "EmployeeNumber"
- "Over18"
- "StandardHours"

These columns were removed because they were constant or served primarily as identifiers rather than useful analytical variables.

After removing these columns:

Remaining Columns: 31

---

❓ Research Questions

The analysis was structured around the following questions:

1. Is working overtime associated with employee attrition?
2. Which department has the highest observed attrition rate?
3. Do employees who leave differ in age from employees who stay?
4. Do employees who leave have a different average monthly income?
5. Which job roles have the highest observed attrition rates?
6. Are there unusual patterns or potential anomalies in the dataset?

---

🧪 Statistical Analysis

Several statistical tests were performed to investigate relationships with employee attrition.

Welch's T-Test

Welch's independent samples t-test was used to compare employees who stayed with employees who left across numerical variables.

The following variables showed statistically significant differences at the 0.05 level:

- Age
- Monthly Income
- Years at Company
- Total Working Years
- Distance From Home
- Job Satisfaction
- Work-Life Balance

Statistical significance indicates that the observed group differences are unlikely to be explained by random sampling variation alone under the test assumptions. It does not establish causation.

---

Chi-Square Test of Independence

Chi-square tests were used to examine relationships between categorical variables and employee attrition.

The following variables showed statistically significant associations with attrition:

- Department
- Job Role
- Overtime
- Marital Status
- Education Field
"Gender" did not show a statistically significant association with attrition in this analysis.

---

📊 Attrition Analysis

Overall Attrition

The dataset contains:

- 1,233 employees who stayed
- 237 employees who left

The observed overall attrition rate is:

16.12%

---

Department Attrition

Observed attrition rates:

Department| Attrition Rate
Sales| 20.63%
Human Resources| 19.05%
Research & Development| 13.84%

---

Job Role Attrition

The highest observed attrition rates were found among:

Job Role| Attrition Rate
Sales Representative| 39.76%
Laboratory Technician| 23.94%
Human Resources| 23.08%
Sales Executive| 17.48%
Research Scientist| 16.10%

---

Overtime and Attrition

Observed attrition rates:

Overtime| Attrition Rate
No| 10.44%
Yes| 30.53%

Employees working overtime had a substantially higher observed attrition rate in this dataset.

This is an observed association and should not be interpreted as proof that overtime directly causes attrition.

---

📈 Employee Comparison

The analysis compared employees who stayed with employees who left.

Feature| Stayed| Left
Average Age| 37.56| 33.61
Average Monthly Income| 6,832.74| 4,787.09
Average Years at Company| 7.37| 5.13

These differences describe patterns observed between the two groups.

---

🔎 Correlation Analysis

A correlation matrix was calculated for the numerical variables.

The analysis also examined correlations between numerical variables and an encoded version of the "Attrition" variable.

Some variables showed negative correlations with attrition, including:

- Job Level
- Total Working Years
- Monthly Income
- Age
- Years at Company
- Years in Current Role

Correlation measures association between variables and does not establish causation.

---

🚨 Outlier Detection

Potential outliers were identified using the Interquartile Range (IQR) method.

Variable| Outliers
Age| 0
Monthly Income| 114
Years at Company| 104
Total Working Years| 63
Distance From Home| 0

These observations were identified as potential statistical outliers. They were not automatically removed because an outlier is not necessarily an invalid observation.

---

💡 Key Insights

The analysis identified several notable patterns:

- Employee attrition represents 16.12% of the dataset.
- Attrition rates vary across departments and job roles.
- Sales Representatives have the highest observed attrition rate among the analyzed job roles.
- Employees working overtime have a substantially higher observed attrition rate.
- Employees who left differ from those who stayed in variables such as age, income, tenure, and job satisfaction.
- Several numerical and categorical variables show statistically significant associations or group differences with attrition.
- Potential outliers exist in several numerical variables and may require additional consideration in future predictive modeling.

These findings describe patterns and statistical associations within the dataset and should not be interpreted as proof of causal relationships.

---

📁 Repository Structure

HR-Data-Cleaning-Statistical-Analysis/
│
├── HR_Data_Cleaning_and_Statistical_Analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── Cleaned_HR_Data.csv
├── README.md
└── requirements.txt

---

⚙️ Requirements

Install the required Python libraries using:

pip install -r requirements.txt

Required libraries:

pandas
numpy
scipy
matplotlib
seaborn

---

🚀 How to Run

1. Clone or download the repository.
2. Make sure the original CSV file is in the same directory as the notebook.
3. Install the required Python libraries.
4. Open "HR_Data_Cleaning_and_Statistical_Analysis.ipynb".
5. Run the notebook from beginning to end.
6. The cleaned dataset will be exported as:

Cleaned_HR_Data.csv

---

🎓 Internship Task

This project was completed as part of the CodeAlpha Data Analytics Internship — Task 2: Exploratory Data Analysis (EDA).

The task focuses on asking meaningful questions, understanding the dataset structure, identifying trends and anomalies, testing hypotheses, and detecting potential data issues.

---

👤 Author
Eslam Alaa

Data Analysis | Python | SQL | Data Visualization

GitHub: "@eslam-alaa240" (https://github.com/eslam-alaa240)
