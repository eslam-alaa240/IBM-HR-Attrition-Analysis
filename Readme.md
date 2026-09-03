# IBM HR Employee Attrition Analysis & Executive Dashboard

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 📌 Project Overview

With an employee turnover rate of **16.1%** exceeding industry benchmarks, this project tackles the critical business challenge of talent retention and rising recruitment costs. I conducted a comprehensive exploratory data analysis (EDA) on **1,470 employee records** leveraging Python to investigate key drivers such as demographics, compensation, overtime, and job satisfaction.

The analysis uncovered that **Sales Representatives face a critical 39.8% attrition rate** and that **employees working overtime are three times more likely to leave**. These actionable insights led to strategic recommendations—including compensation restructuring and targeted retention programs—to mitigate risk, reduce hiring expenses, and enhance long-term workforce stability.

---

## 🎯 Key Business Metrics

| Metric | Finding | Business Impact |
|--------|---------|-----------------|
| **Overall Attrition** | 16.1% | Above industry average; urgent action needed |
| **Sales Reps Attrition** | 39.8% | Nearly 4 out of 10 leave; high recruitment costs |
| **Overtime Risk** | 3x more likely to leave | Work-life balance issue; burnout risk |
| **Income Gap** | Leavers earn $2,046 less | Compensation competitiveness issue |
| **Age Factor** | Leavers are 4 years younger | Early-career retention problem |

---

## 🛠️ Tools & Technologies

### Core Libraries
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical computations
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical visualizations

### Development Environment
- **Jupyter Notebook** - Interactive analysis
- **Python 3.9+** - Programming language

### Key Skills Demonstrated
- Data Cleaning & Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Correlation Analysis
- Executive KPI Dashboard Design
- Data Storytelling & Visualization

---

## 📊 Executive Dashboard Preview

![Dashboard](images/HR_Executive_Dashboard.png)

*The dashboard consolidates 9 key visualizations into a single executive view for strategic decision-making.*

### Visualizations Included:
1. **Overall Attrition** - Pie chart showing 16.1% turnover
2. **Attrition by Department** - Sales leads with 20.6%
3. **Top 5 High-Risk Roles** - Sales Reps at 39.8%
4. **Overtime Impact** - 3x higher attrition
5. **Age Distribution** - Younger employees more likely to leave
6. **Income Distribution** - Significant pay gap
7. **Job Satisfaction** - Lower satisfaction among leavers
8. **Correlation Matrix** - Key feature relationships

---

## 🔍 Key Findings & Insights

### 1. Department & Role Risk

| Department | Attrition Rate |
|------------|----------------|
| Sales | 20.6% |
| Human Resources | 19.1% |
| Research & Development | 13.8% |

| Top Roles | Attrition Rate |
|-----------|----------------|
| Sales Representative | 39.8% ⚠️ CRITICAL |
| Laboratory Technician | 23.9% |
| Human Resources | 23.1% |
| Sales Executive | 17.5% |
| Research Scientist | 16.1% |

### 2. Overtime is a Major Driver
- **No Overtime:** 10.4% attrition
- **With Overtime:** 30.5% attrition
- **Risk Factor:** **3x more likely to leave**

### 3. Employee Profile: Leavers vs. Stayers

| Feature | Stayed | Left | Difference |
|---------|--------|------|------------|
| **Age** | 37.6 yrs | 33.6 yrs | -4 years |
| **Monthly Income** | $6,833 | $4,787 | -$2,046 |
| **Years at Company** | 7.4 yrs | 5.1 yrs | -2.3 years |
| **Job Satisfaction** | ~3/4 | ~2/4 | -1 point |

### 4. Job Satisfaction Correlation
- **Weak correlation with other factors** → Independent driver
- Employees with lower satisfaction are more likely to leave
- **Recommendation:** Regular satisfaction surveys with follow-up action

---

## 💡 Strategic Recommendations

| Priority | Action | Expected Impact |
|----------|--------|-----------------|
| 🔴 **High** | Review compensation structure, especially for Sales and entry-level roles | Reduce income-driven attrition |
| 🔴 **High** | Implement work-life balance programs and review overtime policies | Reduce overtime-related attrition |
| 🟡 **Medium** | Create career development programs for younger employees | Improve early-career retention |
| 🟡 **Medium** | Focus retention efforts on Sales Representatives and Lab Technicians | Address highest-risk roles |
| 🟡 **Medium** | Regular satisfaction surveys with follow-up action plans | Early identification of at-risk employees |
| 🟢 **Low** | Enhance onboarding and mentorship for new hires | Increase early tenure retention |

---

## 📁 Repository Structure
