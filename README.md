# Personal Data Cleaning & Exploratory Data Analysis Project

## Overview

This project focuses on cleaning and analyzing a raw dataset using Python and popular data analysis libraries. The objective was to practice real-world data cleaning, data exploration, and visualization techniques commonly used in data analysis and data science projects.

The project is divided into two main parts:

1. **Data Cleaning** – Handling duplicates, formatting inconsistencies, missing values, and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)** – Understanding the dataset through statistical summaries, correlations, and visualizations.

---

## Project Files

* `personal data cleaning.ipynb` → Data cleaning process
* `EDA personal.ipynb` → Exploratory data analysis and visualization
* `personal_data_cleaning.csv` → Cleaned dataset used for analysis

---

## Tools & Technologies

### Programming Language

* Python

### Libraries Used

* `pandas` – Data manipulation and cleaning
* `numpy` – Numerical operations
* `matplotlib` – Data visualization
* `seaborn` – Statistical visualization

---

## Data Cleaning Process

The cleaning notebook includes several important preprocessing steps:

* Inspecting dataset structure with `.info()`
* Checking data types
* Detecting and removing duplicates
* Cleaning text columns using regular expressions
* Standardizing values
* Preparing data for analysis

Example operations:

```python
# Remove duplicates
 df1 = df1.drop_duplicates()

# Clean ticket column
 df1['Ticket'] = df1['Ticket'].str.replace(r'[^a-zA-Z0-9]', '', regex=True)
```

---

## Exploratory Data Analysis (EDA)

The EDA notebook explores the cleaned dataset using:

* Dataset summaries
* Statistical analysis
* Correlation analysis
* Heatmaps and visualizations
* Distribution analysis

Example visualization:

```python
sns.heatmap(df.corr(numeric_only=True), annot=True)
plt.rcParams['figure.figsize'] = (20,7)
plt.show()
```

---

## Key Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization
* Handling structured datasets
* Working with Pandas DataFrames
* Statistical analysis
* Python programming for data analysis

---

## Project Goal

The goal of this project was to strengthen practical data analysis skills and build a portfolio project demonstrating the ability to:

* Transform raw data into usable datasets
* Identify patterns and relationships in data
* Create meaningful visual insights
* Apply Python libraries in real-world analysis workflows

---

## Future Improvements

Possible future enhancements for this project include:

* Adding more advanced visualizations
* Creating dashboards with Power BI or Tableau
* Applying machine learning models
* Automating data cleaning pipelines
* Improving documentation and reporting

---

## Author

**Dolaimin Yaya KONE**

Aspiring Data Analyst and Supply Chain Professional passionate about data analysis, logistics, and business intelligence.

* LinkedIn: Add your LinkedIn profile here
* GitHub: Add your GitHub profile here

---

## How to Run the Project

1. Clone the repository

```bash
git clone <your-repository-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebooks

```bash
jupyter notebook
```

4. Run the notebooks step by step.

---

## Conclusion

This project demonstrates the complete workflow of preparing and analyzing data using Python. It highlights practical skills in data cleaning, exploration, and visualization that are essential for data analyst and data science roles.
