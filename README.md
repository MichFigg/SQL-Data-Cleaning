#  SQL Data Cleaning Project

This project demonstrates a complete SQL-based data cleaning process using a dataset of global company layoffs.

---

##  Dataset

- Source: [Kaggle - Layoffs 2022](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
- Contains company layoff data including location, industry, date, and funding

---

##  Cleaning Workflow

1. Create a staging table to preserve the original dataset
2. Identify and remove duplicate rows using `ROW_NUMBER()`
3. Standardize inconsistent text data (e.g. trimming whitespace, correcting industry names)
4. Fill in missing values based on repeated company data
5. Convert string dates into SQL `DATE` format using `STR_TO_DATE()`
6. Remove records with nulls in key analytical columns
7. Create a final `VIEW` of the cleaned data for further analysis

---

##  Files

| File Name               | Description                          |
|------------------------|--------------------------------------|
| `data_cleaning_script.sql` | Full SQL workflow for cleaning and preparing the data |
| `layoffs_cleaned` (view)   | Final cleaned version of the dataset as an SQL view |

---


##  Author
Michał Figwer 
