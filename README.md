# 🧑‍💻 Data Science Job Salaries Analysis

This repository contains a detailed analysis of Data Science Job Salaries using Python, focusing on exploring trends, outliers, and insights based on job roles, company sizes, locations, and more.

---

## 📂 Dataset Overview

The dataset includes salary information for Data Science professionals from **2020 to 2023**, with details like experience levels, employment types, company locations, and salary amounts.

### 📊 Key Features of the Dataset:
- Covers various job titles (e.g., Data Scientist, ML Engineer, etc.).
- Contains 11 columns such as experience level, salary (USD), remote work ratio, and company size.
- Ideal for exploring the impact of experience, remote work, and company size on salaries.

---

## 🛠️ Tools and Libraries Used

- **Python:** Data analysis and visualization.
- **Pandas & NumPy:** Data cleaning and aggregation.
- **Seaborn & Matplotlib:** In-depth, customized visualizations.
- **Phik:** For advanced correlation analysis.
- **Plotly:** Interactive treemaps and visualizations.

---

## 🧑‍💻 Project Highlights

### 🔍 Exploratory Data Analysis (EDA)
- **Salary Distribution:** Median salary comparison across job titles.
- **Highest-Paying Jobs:** Insights into top-paying roles like Data Science Tech Lead.
- **Remote Work Impact:** Analyzed the relationship between remote work percentages and salaries.
- **Company Size:** Median salary comparison for small, medium, and large organizations.
- **Global Insights:** Identified countries with the highest and lowest salaries.

---

## 📊 Visualizations

### Top 10 Highest Paid Job Titles
![Top 10 Highest Paid Job Titles](https://github.com/user-attachments/assets/6180eda1-224b-49b2-b836-181208713013)

### Salary Distribution by Job Title (Boxplot)
![Salary Distribution by Job Title (Boxplot)](https://github.com/user-attachments/assets/646842f1-54b1-417a-8414-72f58d31c8d9)

### Kendalls Tau Correlation Salary vs Remote Work Type
![Kendalls Tau Correlation Salary vs Remote Work Type](https://github.com/user-attachments/assets/620d643d-4361-42f0-a747-32f29705e003)

### Salary Growth by Job Title (2020 vs 2023)
![Salary Growth by Job Title (2020 vs 2023)](https://github.com/user-attachments/assets/f0c7791a-9403-4b74-9de6-31b9bc02670b)

---

## 📝 Analytical Insights  

- **Median vs. Mean**:  
  - For salary analysis, we used the **median value**, as salaries within the same job title (e.g., Data Scientist, ML Engineer) can vary significantly—from very low to extremely high.  
  - The **mean salary** is sensitive to outliers. For example, a few employees earning exceptionally high salaries (e.g., $1M) skew the average upward, distorting the overall picture.  
  - On the other hand, the **median salary** provides a more accurate representation of actual salary levels, as it is unaffected by abnormally high values. This makes it a better metric for comparing salaries across job titles.  
- **Geographic Insights**:  
  - The **United States** is the most popular country for job vacancies, with 1929 listings.  
  - **Israel** boasts the highest recorded median salary, while **North Macedonia** has the lowest.  
- **Company Size**: Medium-sized companies offer the **highest average salaries** compared to smaller or larger companies.  
- **Remote Work**:  
  - **No correlation** was found between salary levels and remote work.  
  - A majority (96.3%) of employees work in their country of residence.  
  - Among remote employees working for companies in other countries, **Russia** has the highest rate (50%), followed by **Argentina** and **Italy**.  
- **Profile of the Most Successful Professionals**:  
  - Holds a leadership role (e.g., Data Science Tech Lead, Cloud Data Architect, Data Lead).  
  - Based in **Israel**, **Puerto Rico**, or the **US**.  
  - Works for a **medium-sized company**.  
  - Operates either **fully remotely** or **on-site full-time**.

---

## License
This repository is my personal portfolio and is intended solely to demonstrate my professional skills.
