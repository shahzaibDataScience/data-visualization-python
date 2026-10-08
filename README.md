# 📊 Data Visualization in Python

A gallery of 7 essential chart types with Matplotlib and Seaborn — each with an explanation of **when** to use it. Choosing the right chart is a key data analyst skill.

## What you'll learn

- **Line chart** — show a trend across a continuous variable
- **Bar chart** — compare numbers across categories
- **Histogram** — see the distribution of one variable
- **Boxplot** — compare spread across groups and spot outliers
- **Scatter plot** — see the relationship between two numbers (+ regression line)
- **Heatmap** — see correlations between many numeric columns at a glance
- **Countplot** — count rows per category, split by a second category

## Dataset

`data/employees.csv` — **5,000 employees** (generated with seed 42):

| Column | Description |
|---|---|
| EmployeeID | 1–5000 |
| Department | HR / Engineering / Sales / Marketing |
| Age | 22–65 |
| Salary | Rs. 30,000+ (rises with experience) |
| ExperienceYears | 0–20 |
| Gender | Male / Female |

## How to run

```bash
pip install -r requirements.txt
jupyter notebook visualization.ipynb
```

## Key findings

- **Salary rises with experience** — correlation 0.97 (clear upward trend line)
- **Engineering pays the most** on average (Rs. 134,627), then Sales (Rs. 125,533)
- **Engineering is the largest department** — 2,033 of 5,000 employees
- **Age and experience are strongly linked** (correlation 0.97) — as expected
- Salary spread is widest in Engineering (boxplot shows the biggest boxes and outliers)

## 🎓 Explain it yourself

1. When would you pick a line chart instead of a bar chart?
2. What does a boxplot show that a bar chart of averages hides?
3. The scatter plot has a red line — what does it represent, and what does its slope tell you?
4. In the heatmap, what does a value close to 1 (dark red) mean? What about close to 0?
5. How would you add a chart showing average salary by **gender**? Which chart type would you pick and why?
