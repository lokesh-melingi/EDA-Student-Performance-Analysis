# Exploratory Data Analysis — Student Performance

A college-level EDA project that explores patterns and insights in a Student Performance dataset using Python and an interactive React dashboard.

![Tech](https://img.shields.io/badge/Python-3.11-blue) ![Pandas](https://img.shields.io/badge/Pandas-2.x-150458) ![React](https://img.shields.io/badge/React-19-61DAFB) ![Tailwind](https://img.shields.io/badge/Tailwind-4-38BDF8)

## Project Title
**Exploratory Data Analysis for Discovering Patterns and Insights**

## Objective
Identify the strongest drivers of student final exam scores using statistical and visual analysis.

## Problem Statement
Educators lack a clear, data-driven view of which student habits (study time, attendance, sleep, internet usage) most influence academic outcomes.

## Tech Stack
- **Analysis:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
- **Dashboard:** React, TanStack Router, Tailwind CSS, Recharts

## Folder Structure
```
EDA_Project/
├── Dataset/
│   └── student_performance.csv      # 120 rows × 8 columns
├── Notebook/
│   └── EDA_Project.ipynb            # Reproducible analysis
├── Report/
│   └── EDA_Report.pdf               # Written report
├── frontend/                        # React dashboard
├── backend/                         # (placeholder)
└── README.md
```

## Dataset
| Column | Type | Description |
| --- | --- | --- |
| Student_ID | string | Unique identifier |
| Gender | categorical | Male / Female |
| Study_Hours | numeric | Avg hours studied per day |
| Attendance | numeric (%) | Class attendance |
| Previous_Scores | numeric | Prior assessment average |
| Sleep_Hours | numeric | Avg sleep per night |
| Internet_Usage | numeric | Recreational internet (hrs/day) |
| **Final_Score** | numeric | **Target** — final exam score |

## How to Run

### Notebook
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Notebook/EDA_Project.ipynb
```

### Dashboard
```bash
cd frontend
npm install
npm run dev
```

## Modules
1. **Project Overview** — definition, objective, problem, outcomes
2. **Dataset** — preview, schema, target variable
3. **Analysis** — types, missing values, duplicates, statistical summary
4. **Visualization** — histogram, bar, scatter, box plot, correlation heatmap
5. **Insights** — automatic patterns and recommendations
6. **Report** — downloadable PDF, CSV, notebook, README

## Key Findings
- **Study Hours** is the strongest positive predictor of Final Score.
- **Attendance** reinforces the effect of study time.
- **Internet Usage** beyond 4 hrs/day shows a mild negative effect.
- **Previous Scores** remain a reliable baseline predictor.

## License
MIT — free for academic and personal use.

## Author
Built as a college Data Science portfolio project.
