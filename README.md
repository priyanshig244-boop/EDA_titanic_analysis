# EDA_titanic_analysis
# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The main objective is to explore passenger information, identify patterns, handle missing data, and understand the factors associated with passenger survival.

## 🎯 Objectives
- Understand and explore the Titanic dataset.
- Identify and handle missing values.
- Check duplicate records and data types.
- Analyze survival rates based on gender, passenger class, and age groups.
- Perform grouping, aggregation, and correlation analysis.
- Create meaningful data visualizations.

## 🛠️ Technologies & Tools Used
- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook (Anaconda)** – Development environment

## 📂 Project Files
- `Titanic_Exploratory_Data_Analysis.ipynb` – Jupyter Notebook containing the complete analysis and code.
- `Titanic_Exploratory_Data_Analysis.html` – HTML version of the project for easy viewing.

## 📊 Dataset Information
The project uses the Titanic dataset available through Seaborn.

- **Total Records:** 891 passengers
- **Original Columns:** 15
- **Dataset Type:** Structured passenger data

The dataset contains information such as passenger age, gender, ticket class, fare, family details, and survival status.

## 🔍 Key Analysis Performed

### 1. Data Exploration
- Displayed dataset dimensions.
- Inspected column names and data types.
- Used `head()`, `info()`, and `describe()`.

### 2. Data Cleaning
- Identified missing values.
- Filled missing age values using median age grouped by passenger class and gender.
- Filled missing embarkation information using the mode.
- Removed the deck column due to excessive missing values.
- Checked duplicate records.

### 3. Survival Analysis
- Survival rate based on gender.
- Survival rate based on passenger class.
- Survival rate based on age groups.

### 4. Data Visualization
- Bar charts for survival comparisons.
- Correlation heatmap.
- Combined visualization dashboard.

## 📈 Key Insights
The analysis investigates:
- Differences in survival rates between male and female passengers.
- The relationship between passenger class and survival.
- Survival patterns across different age groups.
- Relationships between numerical variables.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Anaconda Navigator.
4. Launch Jupyter Notebook.
5. Open `Titanic_Exploratory_Data_Analysis.ipynb`.
6. Run all cells in sequence.

**Note:** The Titanic dataset is loaded using Seaborn's built-in dataset function and may require an internet connection on first use.

## 🎓 Learning Outcomes
Through this project, I gained practical experience in:
- Data exploration and preprocessing.
- Handling missing values.
- Working with Pandas DataFrames.
- Grouping and aggregation.
- Statistical analysis and visualization.
- Extracting meaningful insights from real-world datasets.

## 👩‍💻 Author
**BCA (AI & DS) Student**

This project was completed as part of the **InternCircle Data Science & AI Project Series**.

---
⭐ If you find this project useful, feel free to explore the repository!
