# Udemy Courses: Exploratory Data Analysis

A Jupyter notebook exploring a Udemy courses dataset (3,683 courses, 4 subjects: Web Development, Business Finance, Musical Instruments, Graphic Design).

## What it does
- Loads and inspects the data (`info`, missing values)
- Counts courses per subject (bar, pie, seaborn countplot)
- Looks at subscribers per subject (total and mean) and finds the most-subscribed course

## Tools
Python, pandas, NumPy, matplotlib, seaborn, Jupyter.

## How to run
1. `pip install pandas numpy matplotlib seaborn jupyter`
2. Get the dataset as `udemy_courses_clean.csv` and change the path in the first `read_csv` cell.
3. `jupyter notebook udemy_eda.ipynb`

## Note
The CSV is not included in this repo (the original path was on a local machine). The notebook keeps its saved outputs, so the tables and charts are visible on GitHub without running it.
