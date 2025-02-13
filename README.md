
# **ABC Company Employee Analysis**

## **Overview**
This project analyzes employee data from **ABC Company** to understand workforce distribution, salary trends, and key insights across different teams and positions.

### **Tasks Covered**
A.**Preprocessing:** Data cleaning, handling missing values, replacing height column.  
B.**Analysis:** Employee distribution, age groups, salary expenditure, and correlations.  
C.**Visualizations:** Bar charts, pie charts, histograms, scatter plots, and heat maps.  
D. **Data Story:** Key insights from the analysis for decision-making.  

---

## **Dataset**
The dataset consists of **458 rows and 10 columns**, covering employee attributes like    
 
 **Name, Team, Number, Position, Age, Height, Weight, College, Salary,**. 
 
**File:** `ABC_Employees.csv`  

---

## **Analysis & Findings**

### **Employee Distribution by Team**
The largest team is **New Orleans Pelicans**, contributing **4.15%** of employees.
The smallest team is **Orlando Magic**, making up only **3.06%**.

===> **Insight:**
**New Orleans Pelicans** has the largest workforce, likely playing a major role in company operations.
**Orlando Magic** has a smaller team size, possibly indicating a more specialized function.

### **Employees by Position**
The **SG (Shooting Guard) position** is dominant, followed by **PF (Power Forward)**.
The least common position is **C (Center)**, indicating a specialized role.

===> **Insight:**
**Shooting Guards (SGs)** form the majority, meaning they are crucial for the team structure.
**Centers (C)** are fewer, likely due to their specific skill set or strategic importance.

### **Predominant Age Group**
The majority of employees fall in the **20-25 age group**.
Very few employees **(0 total) are aged 50**, suggesting a younger workforce.

===> **Insight**:
The company has **a young workforce**, indicating early-career recruitment.
No employees aged 50+ suggests that retention or **hiring of senior employees is low.**

 ### **Salary Expenditure Trends**
The **Cleveland Cavaliers team** has the highest salary costs.
The **C (Center) position** earns the most, while **SG (Shooting Guard) has the least salary allocation.**

===> **Insight:**
**Cleveland Cavaliers' higher salary cost** suggests a **high concentration of senior or high-value employees.**
**Centers (C) being the highest-paid indicates that experience, demand, or skill set drives salary in this role.**

### **Correlation Between Age and Salary**
The correlation coefficient between **Age and Salary is 0.21.**
**A positive correlation exists—older employees tend to earn more.**
This is likely due to experience and seniority-based salary increments.

===> **Insight:**
Since the **correlation is 0.21 (weak positive correlation),** age has some influence on salary but is not the only factor.
Seniority plays a role, but performance, skill level, or team role likely contribute to earnings.

### **Conclusion & Recommendations**

===> **1️.Recruitment Strategy:**
Since most employees are 20-25, HR should focus on career development & retention plans.
Consider hiring experienced professionals for strategic team growth.

===> **2️. Team Salary Planning:**
Cleveland Cavaliers' higher salary needs an ROI analysis to ensure pay scales align with performance.
Centers (C) receive the highest salary—assess if their impact justifies the cost.

===> **3️. Long-Term Workforce Planning:**
Few employees aged 50+—plan for succession management & skill transfer programs.
If age-salary correlation remains weak (0.21), introduce merit-based salary adjustments to maintain fairness.
  

---

## **Technologies Used**
- **Python** (Data Analysis & Preprocessing)  
- **NumPy, Pandas** (Data Wrangling & Manipulation)  
- **Matplotlib, Seaborn** (Data Visualization)  

---



### **Clone the Repository**
```sh
git clone https://github.com/your-username/ABC_Company_Analysis.git
cd ABC_Company_Analysis
```

### **Install Dependencies**
```sh
pip install pandas numpy matplotlib seaborn
```

### **Run the Jupyter Notebook**
```sh
jupyter notebook ABC_Company_Analysis.ipynb
```

---

## **File Structure**
```
 ABC_Company_Analysis/
├──  ABC_Employees.csv           # Dataset File
├──  ABC_Company_Analysis.ipynb  # Jupyter Notebook with Code & Analysis
├──  README.md                   # Project Documentation (This File)
```

---

## **Contribution & Acknowledgements**
- **Project By:** Jacob Thomas Joshy
- Data provided by **ABC Company** for analysis purposes.  

---

