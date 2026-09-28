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