# Exploratory Data Analysis Projects

This repository contains exploratory data analysis projects built with Python, Jupyter Notebook, pandas, NumPy, Matplotlib, and related data visualization tools. Each folder focuses on a different dataset and uses cleaning, aggregation, visualization, and interpretation to find patterns in the data.

## Projects

### 2024 Olympics

Explores athlete, medal, event, schedule, team, venue, and historical Olympics datasets. The notebook looks at athlete demographics, country participation, medal distribution, and performance patterns across recent and past Olympic data.

Main notebook:

```text
2024 Olympics/2024_olympics_eda.ipynb
```

Main datasets:

```text
2024 Olympics/2024 Olympics/
2024 Olympics/Past Olympics/
```

### Color Game Statistics

Simulates betting outcomes for the Filipino e-casino color game. The analysis compares strategies such as Martingale, reverse Martingale, and constant betting across different round counts, bet sizes, and number of selected colors.

Main files:

```text
Color Game Statistics/color_game.ipynb
Color Game Statistics/color_game.html
Color Game Statistics/color_game.md
```

### Food Intake

Analyzes food intake logs starting from April 2026. The notebook cleans meal categories, dates, dish names, and rice intake values, then studies meal frequency, daily and weekly rice consumption, category patterns, and approximate food themes such as pork, fish/seafood, fruit, vegetables, fried/fast food, sweet drinks, and coffee/caffeine.

Main files:

```text
Food/foods.csv
Food/foods_eda.ipynb
```

### Personal Expenses

Explores personal spending data across 2024 and 2025. The notebooks summarize expenses, identify category-level spending patterns, analyze time-series behavior, and highlight expense categories that may be useful for budgeting decisions.

Main files:

```text
Personal Expenses/2024_expenses/eda_expenses.ipynb
Personal Expenses/2025_expenses/expenses_EDA.ipynb
```

## Repository Structure

```text
eda/
├── 2024 Olympics/
├── Color Game Statistics/
├── Food/
├── Personal Expenses/
├── .gitignore
└── README.md
```

## Tools Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn

Some notebooks may also use project-specific libraries depending on the analysis.

## How To Run

Clone the repository:

```bash
git clone https://github.com/onazor/eda.git
cd eda
```

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install common analysis packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl xlsxwriter
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open any `.ipynb` file from the project folders.

## Notes

- CSV files are included where they are needed for the notebooks.
- Some notebooks contain saved outputs and rendered charts, so file sizes may be larger than plain source notebooks.
- Food theme tagging is approximate because it is based on keywords in dish names, not complete ingredient or nutrition information.
- Analysis results may change when the underlying CSV files are updated.
