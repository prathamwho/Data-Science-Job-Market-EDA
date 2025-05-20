# Data Science Job Market - Exploratory Data Analysis

This repository presents an Exploratory Data Analysis (EDA) of the current **Data Science job market**, with a focus on uncovering trends in roles, salaries, locations, skills, and employment types.

---

## Project Overview

This project analyzes job listings for data-related roles such as:
- Data Scientists
- Data Analysts
- Machine Learning Engineers
- Business Analysts

We aim to extract meaningful insights regarding:
- Job titles and demand
- Company distribution
- Location preferences
- Salary trends
- In-demand skills

---

## Repository Structure

```bash
Project Structure:

  Data-Science-Job-Market-EDA/
  │
  ├── EDA.ipynb # Main notebook with full exploratory data analysis
  ├── datasets/ # Source dataset(s) used for analysis
  │ └── data_jobs.csv
  ├── README.md # Project documentation (you are here)
  └── requirements.txt # Required Python packages
```

## Key Insights
Top Roles: Data Scientist and Analyst roles dominate the job listings.

Salaries: Highest salaries are offered in San Francisco, New York, and remote roles.

Skills in Demand: Python, SQL, AWS, and Machine Learning top the skills chart.

## Getting Started
Prerequisites
Python 3.10+

Recommended: Jupyter Notebook or JupyterLab

Installation

Clone this repository:

```bash
git clone https://github.com/prathamwho/Data-Science-Job-Market-EDA.git
cd Data-Science-Job-Market-EDA
```

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```
Launch Jupyter:

```bash
jupyter notebook
```
Open EDA.ipynb and explore!

## Tools & Libraries
Pandas: Data manipulation
Matplotlib & Seaborn: Visualizations
Plotly: Interactive charts
NumPy: Numerical operations
WordCloud: Visualizing text data (skills)
Seaborn: plotting and styling the graphs

## 📌 Dataset
The dataset is publicly available and included in the /datasets folder. It contains scraped job postings with attributes like job title, company, salary range, location, and required skills.

## Future Work
NLP on job descriptions for better skill extraction
Predictive modeling for salary estimation
Dashboard using Streamlit or Power BI
