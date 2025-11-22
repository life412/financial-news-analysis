# Task 1: Git, GitHub, and Exploratory Data Analysis (EDA)

## Overview
Task 1 focused on setting up the Python development environment, using Git for version control, and performing initial analysis on financial news data. The goal was to demonstrate proficiency in Git/GitHub and basic EDA.

---

## Folder Structure
ml_projects/
├── notebooks/
│ └── 01_EDA.ipynb # removed later after Task 2 completion
├── .gitignore
├── requirements.txt
├── README.md


---

## Steps Completed

### 1. Git & GitHub Setup
- Created GitHub repository for the project.
- Initialized `task-1` branch for Task 1 development.
- Committed work multiple times with descriptive messages.
- Merged `task-1` branch into `main` after completion.

### 2. Exploratory Data Analysis (EDA)
Performed analysis on financial news CSV data:

#### Descriptive Statistics
- Analyzed textual lengths of headlines.
- Counted number of articles per publisher.
- Examined publication dates for trends.

#### Text Analysis
- Identified common keywords and phrases in headlines.
- Highlighted topics or significant events (e.g., "FDA approval", "price target").

#### Time Series Analysis
- Explored publication frequency over time.
- Observed spikes related to specific events.

#### Publisher Analysis
- Determined which publishers contribute most to the news feed.
- Checked for unique domains if email addresses were used as publisher names.

---

## Libraries Used
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `nltk`, `re` – Text processing (optional for advanced EDA)

---
