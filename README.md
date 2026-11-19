<h1 align="center">Student Marks Analyzer</h1>

<p align="center">
  A clean, beginner-friendly Python program that turns a list of marks<br>
  into a clear performance report, with total, average, percentage and grade.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white" alt="Python 3">
  <img src="https://img.shields.io/badge/Type-CLI%20Project-2ea44f?style=flat" alt="CLI Project">
  <img src="https://img.shields.io/badge/Level-Beginner%20Friendly-orange?style=flat" alt="Beginner Friendly">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat" alt="MIT License">
</p>

---

## About the Project

Student Marks Analyzer is a small command-line project written in Python. It takes the marks a student has scored across different subjects and produces a short, easy-to-read report: the total, the highest and lowest marks, the average, the overall percentage and a final grade.

I built it while learning Python and data analytics, as a way to practise loops, conditions and functions on something practical. It is intentionally simple, with no external libraries, so anyone can open the file, read it top to bottom and understand exactly what is going on.

## Features

- Works with **any number of subjects**, with no hardcoded limit
- Finds the **highest and lowest** marks using a plain loop
- Calculates **total, average and percentage**
- Assigns a **final grade** from the percentage
- Handles an **empty list** gracefully instead of crashing
- Prints a neatly **centered report** in the terminal
- Uses only core Python, so there is **nothing to install**

## Grading Scale

| Percentage | Grade |
|:----------:|:-----:|
| 90% and above | **A** |
| 80% to 89% | **B** |
| 70% to 79% | **C** |
| 60% to 69% | **D** |
| 50% to 59% | **E** |
| Below 50% | **Fail** |

## How It Works

1. The marks are stored in a list.
2. A single loop goes through every mark, adding it to the total and updating the highest and lowest values along the way.
3. The average is the total divided by the number of subjects.
4. The percentage is calculated against the maximum possible marks, which is the number of subjects multiplied by 100.
5. The percentage is checked against the grading scale to decide the final grade.
6. Everything is printed as a short report.

## Getting Started

### Requirements

- Python 3.x

### Run it

```bash
# Clone the repository
git clone https://github.com/Rammal-Ahmed/student-marks-analyzer.git

# Move into the project folder
cd student-marks-analyzer

# Run the program
python student_marks_analyzer.py
```

## Sample Output

For the marks `[75, 33, 85, 98, 56]`:

```
----------------------------------------
     STUDENT MARKS ANALYSIS REPORT      
........................................

Total Marks: 347
Highest Marks: 98
Lowest Marks: 33
Average Marks: 69.4
Percentage: 69.40%
Final Grade: D

========================================
        Keep learning. Keep building.   
   SEE YOU IN THE NEXT REPOSITORIES..!  
========================================
```

## Try Your Own Marks

Open `student_marks_analyzer.py` and change this line to any marks you like:

```python
marks = [75, 33, 85, 98, 56]
```

For example, a six-subject result:

```python
marks = [88, 72, 91, 65, 79, 84]
```

The percentage adjusts automatically to the number of subjects, so no other change is needed.

## Project Structure

```
student-marks-analyzer/
├── student_marks_analyzer.py
├── README.md
└── LICENSE
```

## What I Practised

- Looping through a list and tracking values (total, highest, lowest)
- Writing and calling a function with a parameter
- Using `if / elif / else` to build a grading system
- Formatting output with `.center()` and `.format()`
- Guarding against edge cases such as an empty list

## Ideas for Future Improvements

- [ ] Accept marks from the user instead of a fixed list
- [ ] Add subject names alongside each mark
- [ ] Show a pass or fail status for every subject
- [ ] Save the report to a text or CSV file
- [ ] Visualise the marks with a simple bar chart

## About me

# **Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details

---

*Developed as part of my Python programming practice*

---

**Project Status:** Completed

</div>
