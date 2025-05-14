# 📊 Fall Enrollment Analysis Report

This project analyzes course enrollment trends across multiple campuses at Perimeter College. It highlights patterns in seat availability, section demand, and credit hour distribution—especially for special categories like PLC and Support Courses.

## 🔍 Key Features

- Calculates filled and open seats per course and campus
- Flags **PLC (Perimeter Learning Community)** and **Support Courses**
- Summarizes credit hour contributions by campus
- Visualizations:
  - Donut chart of enrollment by campus
  - Stacked bar charts (filled vs. open seats)
  - Per-course breakdown with % full and open seat counts
  - Subplot grid of all campuses side-by-side

## 🧠 What is a PLC?

**PLC** (Perimeter Learning Community) sections are part of cohort-based scheduling where students are pre-registered into coordinated courses. These sections often include reserved seating (e.g., via `ATTS` codes) and must be analyzed separately from general enrollment.

**Support Courses** typically accompany gateway math classes to assist students needing corequisite remediation. They're identified based on notes referencing other CRNs in the comments.

## 📂 Folder Contents

| File | Description |
|------|-------------|
| `Fall_Enrollment_Analysis_Notebook_Commented.ipynb` | Jupyter Notebook with analysis, charts, and commentary |
| `enrollment_pie_exploded.png` | Donut chart image used in README |
| `enrollment_bar_grid.png` | Grid of stacked bar charts by campus |
| `sample_schedule_data.csv` | Example input file format (anonymized) |

## 🚀 How to Use

1. Clone or download the repo
2. Open `Fall_Enrollment_Analysis_Notebook_Commented.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter
3. Upload your course schedule CSV
4. Run all cells to generate summaries and visualizations

## 🧩 Requirements

- Python 3.8+
- pandas
- matplotlib
- seaborn (optional for styling)
