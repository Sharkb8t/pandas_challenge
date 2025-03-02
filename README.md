# pandas_challenge
---

## 📌 Project Overview

This project analyzes school performance across a district using Python, Pandas, and Jupyter Notebook. The analysis involves merging student and school data, performing statistical calculations, and generating summarized insights into school performance based on key metrics such as test scores, student demographics, and school spending.

---

## 📂 Files Included

### 1️⃣: Data Files (Located in `Resources/` Folder)

`schools_complete.csv` → Contains school-level data (e.g., school type, budget, and total students).

`students_complete.csv` → Contains student-level data (e.g., math and reading scores, grade level, and school name).

### 2️⃣: Jupyter Notebook File

`school_district_analysis.ipynb` → Contains all Python code for data processing, analysis, and visualization.

---

## 📂 Repository Structure
```
pandas_challenge
|── PyCitySchools/
|  |── Resources/
|  |  |── schools_complete.csv
|  |  |── students_complete.csv
|  |── PyCitySchools.ipynb
|── .gitignore
|── README.md
```
---

## 🎯 Key Objectives & Analysis Steps

### 1️⃣ Data Preparation:

✅ Load school and student datasets using Pandas

✅ Merge datasets on `"school_name"` to create a unified DataFrame

✅ Clean and format the data for accurate analysis

### 2️⃣ District-Wide Summary Metrics:

✅ Count total schools, students, and budget

✅ Calculate average math & reading scores

✅ Determine percentage of students passing math, reading, and overall

### 3️⃣ Per-School Performance Summary:

✅ Categorize each school by type (Public/Charter)

✅ Compute per-school statistics such as:

  - Total Students
  
  - School Budget & Per-Student Budget
  
  - Average Test Scores
  
  - Percentage of Students Passing

### 4️⃣ School Performance Ranking:

✅ Identify Top 5 and Bottom 5 performing schools based on overall passing rate

### 5️⃣ Grade-Level Performance Breakdown:

✅ Analyze math & reading scores for each grade (9th–12th) at every school

### 6️⃣ Performance Based on Spending & Size:

✅ Categorize schools based on Per Student Budget (e.g., Low, Medium, High Spending)

✅ Group schools by size (Small, Medium, Large) and compare test scores

### 7️⃣ Performance by School Type:

✅ Compare Charter vs. Public Schools based on test performance

---

## 📦 Required Libraries & Dependencies

Ensure you have the following Python libraries installed:
```
pip install pandas jupyter
```

Alternatively, if using Anaconda to run this script install using the following:
```
conda install pandas jupyter
```
---
## 🏎️ How to Run the Project

1️⃣ Open the Jupyter Notebook environment in bash:
```
jupyter notebook
```

2️⃣ Navigate to `school_district_analysis.ipynb`

3️⃣ Restart Kernel and delete previous cell outputs

4️⃣ Run all cells sequencially (`Kernel` → `Run All`)

---
## 📈 Data Insights & Trends

🔹 Charter Schools Perform Better: Charter schools had higher passing rates in both math and reading compared to public schools.

🔹 Higher Spending ≠ Higher Performance: Schools with lower per-student budgets ($585–$630) had higher test scores compared to schools with higher budgets.

🔹 Smaller Schools Excel: Schools with fewer students (<1000) had higher average test scores than larger schools.

🔹 Grade-Level Trends: 9th and 10th graders tended to score slightly higher in math, while reading scores remained more consistent across grades.
