# Netflix Exploratory Data Analysis — CodeAlpha Internship Task 2

Exploratory data analysis of the Netflix Movies & TV Shows dataset using Python (Pandas).

## Dataset
Netflix Movies and TV Shows (Kaggle) — 8,807 titles originally, 8,797 after cleaning.

## What I Did
- Checked data structure, data types and missing values
- Filled missing `director`, `cast` and `country` with "Unknown"
- Dropped 10 rows with missing `date_added`
- Filled missing `rating` and `duration` with the most frequent value
- Converted `date_added` to a date type and created `year_added` and `month_added`
- Split `duration` into a number and a type (Minute / Season)
- Answered 10 questions about the data

## Key Findings
- Movies make up about 70% of the catalog, TV Shows about 30%
- The United States and India produce the most content
- TV-MA is the most common rating
- July and December are the busiest months for new additions
- The longest movie is "Black Mirror: Bandersnatch" (312 min)
- The TV show with the most seasons is "Grey's Anatomy" (17)

## Files
- `CodeAlpha_Internship_Task2.ipynb` — the analysis notebook
- `netflix_titles.csv` — original dataset

## Tools
Python, Pandas, Jupyter Notebook