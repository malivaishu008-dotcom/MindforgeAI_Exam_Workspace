# MindForgeAI Internship 1.0
## Module Assessment 2 – Week 2–3 Practical Examination

### Student Information

- **Student Name:** VAISHNAVI MALI
- **Student ID:** 2026IT012
- **Repository Name:** mindforgeai-exam-2-<student-id>

---

# Project Objective

The objective of this assessment is to demonstrate practical skills in Python programming, data analytics, Git version control, and software engineering workflow. The project analyzes student academic performance using Python and generates meaningful insights based on attendance, assignments, laboratory performance, diary entries, and completed tasks.

---

# Repository Structure

```
mindforgeai-exam-2-<student-id>/

│
├── README.md
│
├── notebooks/
│   └── Module_Assessment_2.ipynb
│
├── data/
│   └── week_2_3_exam_student_signals.csv
│
├── outputs/
│   ├── analytics_output.png
│   └── final_dataframe.png
│
└── screenshots/
    ├── github_repository.png
    └── notebook_execution.png
```

---

# Tools and Technologies Used

- Python 3
- Jupyter Notebook
- Google Colab (Optional)
- Visual Studio Code
- Git
- GitHub
- Pandas
- NumPy
- Markdown

---

# Dataset

The project uses a student performance dataset containing the following information:

- Student ID
- Student Name
- Department
- Attendance Percentage
- Diary Entries
- Tasks Completed
- Assignment Score
- Laboratory Score

The dataset is stored inside the **data/** folder.

---

# Project Workflow

1. Create or load the student dataset.
2. Display the first few records.
3. Check dataset shape and data types.
4. Identify missing values.
5. Calculate a Readiness Score using attendance, diary entries, task completion, assignment marks, and laboratory marks.
6. Classify students into performance categories:
   - Support
   - Developing
   - Strong
   - Excellent
7. Generate analytics including:
   - Department-wise average readiness score
   - Top-performing student
   - Students requiring academic support
8. Document observations using Markdown cells.

---

# Readiness Score Logic

The readiness score is calculated using weighted academic indicators:

| Component | Weight |
|-----------|---------|
| Attendance | 25% |
| Diary Entries | 15% |
| Tasks Completed | 20% |
| Assignment Score | 20% |
| Lab Score | 20% |

The final score is calculated out of 100.

---

# Performance Classification

| Score Range | Performance Band |
|-------------|------------------|
| Below 40 | Support |
| 40–69 | Developing |
| 70–89 | Strong |
| 90 and Above | Excellent |

---

# Analytics Generated

The notebook generates the following insights:

- Department-wise average readiness score
- Highest-performing student
- Students requiring academic support
- Performance band distribution
- Final readiness score for every student

---

# Results Summary

The analysis indicates that students with higher attendance, consistent diary maintenance, and better assignment and lab performance achieve higher readiness scores.

Students with lower attendance and incomplete academic tasks are classified into the **Support** category and require additional academic assistance.

Department-wise averages provide an overview of overall academic performance across departments.

---

# How to Run the Project

## Option 1: Jupyter Notebook

1. Clone this repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Open the notebook located in the **notebooks/** folder.
4. Run all cells sequentially.

---

## Option 2: Google Colab

1. Upload the notebook.
2. Upload the dataset from the **data/** folder.
3. Run all notebook cells.

---

# Learning Outcomes

This project demonstrates understanding of:

- Python programming fundamentals
- Functions and conditional statements
- Loops
- Data analysis using Pandas
- Dataset validation
- Data visualization and interpretation
- Markdown documentation
- Git version control
- GitHub repository management
- Professional software engineering workflow

---

# Git Workflow

The project was managed using Git with meaningful commits.

Example commands:

```bash
git init
git add .
git commit -m "Completed Module Assessment 2"
git branch -M main
git remote add origin <repository-url>
git push -u origin main
```

---

# Repository Contents

✅ README.md

✅ Executed Jupyter Notebook

✅ Dataset (CSV)

✅ Output Screenshots

✅ Git Commit History

---

# Conclusion

This assessment demonstrates the complete workflow of a data analytics project—from dataset preparation and exploratory analysis to readiness score calculation, performance classification, interpretation of insights, and deployment using GitHub. The repository follows standard software engineering practices with organized folders, clear documentation, and reproducible notebook execution.

**Module:** MindForgeAI Internship 1.0

**Assessment:** Module Assessment 2 – Week 2–3 Practical Examination
