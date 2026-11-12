# 🎓 Student Performance Analysis Using NumPy

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-013243?logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-1000%20Students-success)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Project Overview

The **Student Performance Analysis Using NumPy** project is a data analysis project developed using Python and NumPy to analyze the academic performance of 1,000 students.

The project focuses on extracting meaningful insights from student academic records through numerical computing, statistical operations, array manipulation, and data analysis techniques.

It explores student demographics, subject-wise performance, academic rankings, department-wise results, pass/fail statistics, and grade distributions.

The primary objective is to demonstrate practical NumPy skills by performing real-world-style data analysis without using Pandas or other data analysis libraries.

---

## 🎯 Project Objectives

- Analyze academic performance across 1,000 students.
- Calculate subject-wise average marks.
- Identify top-performing and low-performing students.
- Find the overall class topper.
- Analyze department-wise academic performance.
- Calculate student pass and fail percentages.
- Perform statistical analysis using NumPy.
- Classify students into academic grades.
- Extract meaningful insights from numerical data.

---

## 📂 Dataset Information

The project uses a synthetic dataset containing 1,000 student records.

| Dataset Information | Details |
|---|---|
| Total Students | 1,000 |
| Total Columns | 20 |
| File Format | CSV |
| Data Type | Structured Student Data |
| Dataset Type | Synthetic / Educational |
| Analysis Library | NumPy |

### Dataset Features

The dataset contains the following types of information:

**Student Information**
- Student ID
- Name
- Email
- Age
- Gender
- Department
- Semester
- City

**Academic Information**
- Mathematics Marks
- Physics Marks
- Programming Marks
- Database Management Marks
- English Marks
- Total Marks
- Maximum Marks
- Percentage
- Grade
- Academic Result

**Additional Information**
- Enrollment Year
- Scholarship Status

---

## 🛠️ Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Python | Core Programming Language |
| NumPy | Numerical Computing and Data Analysis |
| CSV Module | Loading CSV Dataset |
| Jupyter Notebook | Interactive Development |
| VS Code | Code Editor |
| Git & GitHub | Version Control and Project Hosting |

**Important:** NumPy is used for all major numerical analysis and calculations. The built-in Python CSV module is used to load the dataset.

---

## 📊 Project Analysis – 10 Questions

### Q1. Student Demographic Analysis
- Calculate total number of students.
- Find average age.
- Identify minimum and maximum age.
- Analyze gender distribution.

### Q2. Subject-wise Average Marks Analysis
- Calculate average marks in each subject.
- Identify the strongest-performing subject.
- Identify the weakest-performing subject.

### Q3. Top 10 Performing Students
- Rank students based on total marks.
- Display student IDs and names.
- Calculate their overall percentages.

### Q4. Bottom 10 Performing Students
- Identify the 10 lowest-performing students.
- Display their total marks and percentages.
- Analyze low academic performance.

### Q5. Class Topper Analysis
- Identify the student with the highest total marks.
- Display complete student information.
- Calculate the topper's percentage and grade.

### Q6. Subject-wise Highest and Lowest Marks
- Find the maximum marks in every subject.
- Find the minimum marks in every subject.
- Identify students achieving these scores.

### Q7. Student Pass/Fail Analysis
- Apply a minimum passing percentage of 50%.
- Calculate total passed students.
- Calculate total failed students.
- Calculate pass and fail rates.

### Q8. Department-wise Performance Analysis
- Calculate department-wise student counts.
- Find average percentage for each department.
- Identify the best-performing department.

### Q9. Statistical Analysis
Calculate the following statistical measures:

- Mean
- Median
- Variance
- Standard Deviation
- Minimum Percentage
- Maximum Percentage

### Q10. Grade Distribution and Classification

Classify students according to their overall percentage.

| Percentage Range | Grade |
|---|---|
| 90–100% | A |
| 80–89.99% | B |
| 70–79.99% | C |
| 60–69.99% | D |
| 50–59.99% | E |
| Below 50% | F |

Also calculate the total number of students in each grade.

---

## 📈 Key Project Findings

The following insights were obtained from the dataset:

### 1. Student Demographics

- Total Students: 1,000
- Average Age: 20.52 years
- Male Students: 551
- Female Students: 449

### 2. Subject-wise Performance

| Subject | Average Marks |
|---|---:|
| Mathematics | 68.80 |
| Physics | 66.38 |
| Programming | 71.21 |
| DBMS | 70.51 |
| English | 73.05 |

- Strongest Subject: English
- Weakest Subject: Physics

### 3. Topper Performance

- Topper: Saanvi Reddy
- Total Marks: 500/500
- Percentage: 100%
- Grade: A

### 4. Pass/Fail Analysis

| Metric | Result |
|---|---:|
| Total Students | 1,000 |
| Passed Students | 952 |
| Failed Students | 48 |
| Pass Rate | 95.2% |
| Fail Rate | 4.8% |

Passing criteria: Minimum 50% overall percentage.

### 5. Department-wise Performance

- Best Performing Department: Business Administration
- Average Percentage: 70.98%
- Lowest Performing Department: Mechanical Engineering
- Average Percentage: 69.27%

### 6. Statistical Insights

| Statistical Measure | Result |
|---|---:|
| Mean | 69.99% |
| Median | 70.60% |
| Variance | 144.98 |
| Standard Deviation | 12.04 |
| Minimum Percentage | 30.20% |
| Maximum Percentage | 100% |

*All findings are based on the synthetic educational dataset.*

---

## 🧮 NumPy Functions Implemented

The project uses several important NumPy functions:

| NumPy Function | Purpose |
|---|---|
| `np.array()` | Create NumPy arrays |
| `np.column_stack()` | Combine subject arrays |
| `np.sum()` | Calculate total marks |
| `np.mean()` | Calculate average |
| `np.median()` | Calculate median |
| `np.max()` | Find maximum value |
| `np.min()` | Find minimum value |
| `np.argmax()` | Find index of maximum value |
| `np.argmin()` | Find index of minimum value |
| `np.argsort()` | Sort student rankings |
| `np.unique()` | Find unique categories |
| `np.where()` | Apply conditional classification |
| `np.std()` | Calculate standard deviation |
| `np.var()` | Calculate variance |
| `np.size()` | Count array elements |

Additional concepts:
- 1D and 2D NumPy Arrays
- Array Indexing and Slicing
- Boolean Masking
- Conditional Operations
- Axis-based Calculations
- Statistical Computation

---

## 📁 Project Structure

```text
Student-Performance-Analysis-NumPy/
│
├── student_analysis_data.csv
│
├── student_performance_analysis.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

---

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/student-performance-analysis-numpy.git
```

### Step 2: Navigate to Project Directory

```bash
cd student-performance-analysis-numpy
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Project

Open:

`student_performance_analysis.ipynb`

Run all notebook cells sequentially to reproduce the analysis.

---

## 📦 Requirements

The project requires:

```text
numpy
jupyter
notebook
```

---

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

- Working with real-world-style structured datasets.
- Performing numerical analysis using NumPy.
- Creating and manipulating multidimensional arrays.
- Applying Boolean indexing and conditional filtering.
- Performing statistical calculations.
- Ranking and comparing student performance.
- Extracting meaningful insights from data.
- Organizing and documenting a complete Python data analysis project.

---

## 🚀 Future Improvements

Possible future enhancements include:

- Data visualization using Matplotlib and Seaborn.
- Interactive dashboards using Power BI.
- Advanced student performance prediction.
- Correlation analysis between subjects.
- Attendance-based academic eligibility analysis.
- Machine Learning-based performance prediction.

---

## 👨‍💻 Author

**Sumit Raj**

Computer Science & Engineering Student  
Aspiring Data Analyst | Python | NumPy | SQL | Power BI

---

## ⭐ Support

If you find this project useful or interesting, consider giving this repository a ⭐ on GitHub.

Your feedback and suggestions are always welcome!

**Thank you for visiting my project!**
