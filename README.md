# 📊 Student Performance Analysis using Pandas

A beginner-friendly **Python Data Analysis** project built using **Pandas** and **NumPy**. This project demonstrates essential data wrangling techniques such as data cleaning, feature engineering, grouping, merging datasets, and generating summary reports.

---

## 📌 Project Overview

This project analyzes student performance data to extract meaningful insights from academic records. It walks through the complete data analysis workflow—from loading raw CSV files to cleaning data, engineering new features, performing exploratory analysis, merging attendance data, and generating summary reports.

---

## 🚀 Features

- 📂 Load student performance data from CSV files
- 🔍 Explore dataset structure and descriptive statistics
- 🧹 Handle missing values using `fillna()`
- 🗑️ Detect and remove duplicate records
- 📊 Create new features:
  - Total Score
  - Average Score
  - Percentage
  - Grade
  - Pass/Fail Status
- 📈 Analyze overall student performance
- 👨‍🎓 Find top and bottom performers
- 📑 Perform `groupby()` analysis
- 🔗 Merge attendance data with student records
- 💾 Export cleaned dataset
- 📝 Generate a summary report

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

---

# 📁 Project Structure

```text
Student-Performance-Analysis/
│
├── StudentsPerformance.csv
├── student_attendance.csv
├── cleaned_students.csv
├── report.txt
├── student_analysis.ipynb
├── README.md
└── requirements.txt
```

---

# 📚 Concepts Covered

- Pandas DataFrame
- `read_csv()`
- `head()`
- `tail()`
- `info()`
- `describe()`
- `isnull()`
- `fillna()`
- `duplicated()`
- `drop_duplicates()`
- `groupby()`
- `merge()`
- Feature Engineering
- Data Cleaning
- Data Analysis
- Exporting Processed Data

---

# 📊 Analysis Performed

The notebook performs the following analyses:

- ✅ Total number of students
- ✅ Male vs Female student count
- ✅ Average scores in Mathematics, Reading, and Writing
- ✅ Highest scoring student
- ✅ Lowest scoring student
- ✅ Overall percentage calculation
- ✅ Grade distribution
- ✅ Pass/Fail analysis
- ✅ Gender-wise average scores
- ✅ Lunch-wise performance comparison
- ✅ Test preparation course analysis
- ✅ Race/Ethnicity-wise performance
- ✅ Parent education-wise performance
- ✅ Attendance analysis

---

# 📈 Feature Engineering

The following new columns are created during preprocessing:

| Feature | Description |
|----------|-------------|
| **Total Score** | Sum of Math, Reading, and Writing scores |
| **Average Score** | Average of all subject scores |
| **Percentage** | Overall percentage |
| **Grade** | Grade assigned based on percentage |
| **Result** | Pass/Fail status |

---

# 📄 Output Files

After running the notebook, the following files are generated:

- `cleaned_students.csv`
- `student_attendance.csv`
- `report.txt`

---

# ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Student-Performance-Analysis.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Student-Performance-Analysis
```

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Notebook

Open the notebook in **Jupyter Notebook** or **Visual Studio Code** and execute all cells.

```
student_analysis.ipynb
```

---

# 📷 Sample Output

```
Student Performance Report

==============================
Top 10 Students
==============================

1. Student A
2. Student B
3. Student C
...

==============================
Bottom 10 Students
==============================

...

==============================
Group-wise Performance Analysis
==============================

Gender-wise Average Scores
Lunch-wise Performance
Attendance Analysis
Grade Distribution
Pass/Fail Summary
```

---

# 🎯 Learning Outcomes

By completing this project, you will learn:

- Loading datasets using Pandas
- Data cleaning and preprocessing
- Handling missing values
- Removing duplicate records
- Feature engineering
- Performing GroupBy operations
- Merging multiple DataFrames
- Exploratory Data Analysis (EDA)
- Generating reports
- Exporting processed datasets

---

# 📦 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

**requirements.txt**

```text
pandas
numpy
jupyter
```

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is created for educational and learning purposes and is free to use.

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

It motivates future improvements and helps others discover the project.

Happy Coding! 🚀

