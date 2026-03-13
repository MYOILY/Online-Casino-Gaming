# 🎰 Online Casino Gaming Data Analysis

## Project Overview

The online gambling industry generates significant revenue through digital casino platforms. Understanding how wagers, player winnings, and promotional deductions influence total gaming revenue is important for both regulators and operators.

This project performs **Exploratory Data Analysis (EDA)** on online casino gaming data to investigate financial trends and operational patterns within the industry.

Using Python-based data science tools, the analysis explores relationships between **player wagering behavior, casino payouts, and gross gaming revenue**.

---

## Research Questions

This project focuses on answering several key questions:

1. How do **total wagers relate to gross gaming revenue**?
2. What patterns exist between **player winnings and casino profit**?
3. How much impact do **promotional deductions** have on reported revenue?
4. Are there noticeable **trends over time** in online casino activity?
5. How does gaming performance vary across **different licensees (operators)**?

---

## Dataset Description

The dataset contains financial records from online casino operations, including wagering activity, payouts, and revenue calculations.

### Main Variables

| Variable                        | Description                    |
| ------------------------------- | ------------------------------ |
| Fiscal Year                     | Fiscal reporting year          |
| Month Ending                    | Month the data was reported    |
| Licensee                        | Casino operator                |
| Wagers                          | Total money wagered by players |
| Patron Winnings                 | Total winnings paid to players |
| Cancelled Wagers                | Wagers that were cancelled     |
| Online Casino Gaming Win/(Loss) | Net gaming result              |
| Promotional Deduction           | Promotional credits deducted   |
| Total Gross Gaming Revenue      | Revenue before deductions      |
| Payment                         | Payment derived from revenue   |

---

## Tools and Technologies

The project was implemented using the following data science stack:

* **Python**
* **Pandas** – data cleaning and manipulation
* **NumPy** – numerical computation
* **Matplotlib** – visualization
* **Seaborn** – statistical graphics
* **SciPy** – statistical analysis
* **Scikit-learn** – data preprocessing

---

## Project Workflow

The analysis followed a standard data science workflow:

### 1️⃣ Data Loading

Import dataset and inspect structure.

### 2️⃣ Data Cleaning

* Handling missing values
* Checking data types
* Validating dataset consistency

### 3️⃣ Exploratory Data Analysis

* Summary statistics
* Distribution analysis
* Correlation exploration

### 4️⃣ Visualization

Graphs were used to explore relationships such as:

* Wagers vs Patron Winnings
* Wagers vs Gross Gaming Revenue
* Revenue trends over time
* Operator-level comparisons

### 5️⃣ Interpretation

Identify patterns and extract insights from the data.

---

## Key Insights

Some important observations from the analysis include:

* **Wagers strongly influence total gross gaming revenue**, showing the direct relationship between player activity and casino income.
* **Patron winnings scale with wagers**, indicating consistent payout ratios across operators.
* **Promotional deductions reduce reported revenue**, demonstrating how marketing incentives impact financial reporting.
* Revenue levels fluctuate across **months and operators**, suggesting operational and market variability.

---

## Project Structure

```
Online-Casino-Gaming
│
├── Casino_Gaming_Data.csv
├── EDA.ipynb
├── Presentation.pdf
└── README.md
```

**Files**

`Casino_Gaming_Data new.csv`
Raw dataset used for analysis.

`EDA.ipynb`
Jupyter Notebook containing all data cleaning, analysis, and visualizations.

`Presentation.pdf`
Slides summarizing the project findings.

---

## How to Run the Project

### Clone the repository

```bash
git clone https://github.com/MYOILY/Online-Casino-Gaming.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

### Run the analysis

Open the notebook:

```
EDA.ipynb
```

Run all cells to reproduce the analysis.

---

## Future Work

Possible improvements include:

* Building **predictive models for gaming revenue**
* Applying **time-series forecasting**
* Creating an **interactive dashboard**
* Expanding analysis with **larger datasets**
* Investigating **player behavior patterns**

---

## Author
Lok Yiu
GitHub: [https://github.com/MYOILY](https://github.com/MYOILY)
