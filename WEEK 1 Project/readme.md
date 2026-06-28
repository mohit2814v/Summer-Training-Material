# Student Gradebook Analysis using Pandas and NumPy

## Project Overview

This project demonstrates the use of **Python**, **Pandas**, and **NumPy** to build a simple Student Gradebook System. It stores student grades for multiple subjects, performs statistical analysis, manipulates the data, and visualizes student performance using graphs.

The project helps students understand the fundamentals of data analysis using Pandas DataFrames.

---

## Features

* Store student names and subject marks using a Pandas DataFrame.
* Load student data from a CSV file or manually create a DataFrame.
* Calculate:

  * Average marks
  * Median marks
  * Maximum marks
  * Minimum marks
* Compute statistics for:

  * Each student across all subjects
  * Each subject across all students
* Sort students according to their average marks.
* Identify the top-performing student.
* Display graphical analysis using Matplotlib.

---

## Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib

---

## Dataset

The dataset contains the following columns:

| Column   | Description    |
| -------- | -------------- |
| Name     | Student Name   |
| Math     | Math Marks     |
| Science  | Science Marks  |
| English  | English Marks  |
| Computer | Computer Marks |
| History  | History Marks  |

Example:

| Name    | Math | Science | English | Computer | History |
| ------- | ---- | ------- | ------- | -------- | ------- |
| Alice   | 85   | 90      | 88      | 95       | 76      |
| Bob     | 92   | 85      | 79      | 89       | 82      |
| Charles | 78   | 80      | 84      | 92       | 75      |

---

## Data Representation

Student records are stored in a **Pandas DataFrame**, where:

* Each row represents one student.
* Each column represents a subject or calculated statistic.

Example:

```python
df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charles"],
    "Math": [85, 92, 78],
    "Science": [90, 85, 80],
    "English": [88, 79, 84],
    "Computer": [95, 89, 92],
    "History": [76, 82, 75]
})
```

---

## Data Loading

### Option 1: Load from CSV

```python
import pandas as pd

df = pd.read_csv("student_grades.csv")
```

### Option 2: Create DataFrame Manually

Create the DataFrame using a Python dictionary as shown above.

---

## Statistical Analysis

The project calculates the following statistics.

### Student-wise Statistics

* Total Marks
* Average Marks
* Median Marks
* Maximum Marks
* Minimum Marks

### Subject-wise Statistics

For every subject:

* Average
* Median
* Highest Marks
* Lowest Marks

---

## Data Manipulation

The project performs several data manipulation tasks:

* Add Average column
* Sort students by average marks
* Find the topper
* Filter students using `query()`
* Find highest scoring subject for a student
* Save the updated DataFrame to CSV

Example:

```python
df = df.sort_values(by="Average", ascending=False)
```

---

## Data Visualization

The project includes graphs such as:

* Bar Chart: Student Name vs Average Marks
* Line Graph: Student Performance
* Subject-wise Marks Comparison (optional)

Example:

```python
import matplotlib.pyplot as plt

plt.bar(df["Name"], df["Average"])
plt.title("Average Marks of Students")
plt.xlabel("Student Name")
plt.ylabel("Average Marks")
plt.show()
```

---

## How to Run the Project

1. Install the required libraries.

```bash
pip install pandas numpy matplotlib
```

2. Open the Jupyter Notebook.

```bash
jupyter notebook WEEK_1_Project.ipynb
```

3. Run all cells sequentially.

4. View the generated statistics and graphs.

---

## Expected Output

* Student gradebook displayed as a DataFrame.
* Student-wise statistics.
* Subject-wise statistics.
* Sorted list of students based on average marks.
* Top-performing student identified.
* Graph showing average marks of all students.

---

## Learning Outcomes

After completing this project, you will be able to:

* Create and manipulate Pandas DataFrames.
* Load and save CSV files.
* Perform descriptive statistical analysis.
* Use filtering and sorting techniques.
* Visualize data using Matplotlib.
* Apply NumPy and Pandas for basic data analytics.

---

## Author

**Mohit Gupta**

B.Tech Student | Data Analytics Enthusiast
