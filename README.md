# Austo Motor Company Analysis

## Project Overview

This project focuses on analyzing customer behavior and automobile purchase patterns for Austo Motor Company, a car manufacturer specializing in SUV, Sedan, and Hatchback models.

The main objective of this project is to understand how customer demographics, income, family status, loans, and other personal factors influence automobile purchasing decisions and vehicle preferences.

This analysis helps the business improve customer targeting, sales strategy, and marketing campaigns.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

---

## Dataset Information

- Total Rows: 1581
- Total Columns: 14

### Key Variables

- Age
- Gender
- Profession
- Marital Status
- Education
- Number of Dependents
- Personal Loan
- House Loan
- Partner Working
- Salary
- Partner Salary
- Total Salary
- Price
- Make (SUV / Sedan / Hatchback)

---

## Data Cleaning Performed

- Corrected misspelled values in Gender column
- Treated missing values in Gender using a separate category: Gender_Unknown
- Calculated missing Partner Salary using:

Partner Salary = Total Salary - Salary

- Removed outliers using IQR method for:
  - No_of_Dependents
  - Total_Salary

---

## Exploratory Data Analysis (EDA)

### Univariate Analysis

Performed analysis on:

- Age
- Salary
- Total Salary
- Price
- Gender
- Profession
- Marital Status
- Education
- Loans
- Partner Working
- Make of Car

### Bivariate Analysis

Studied relationships between:

- Make vs Price
- Gender vs Car Type
- Profession vs Car Type
- Salary vs Total Salary
- Correlation Heatmap

### Multivariate Analysis

Analyzed combined effects of:

- Marital Status
- Number of Dependents
- Make Preference

---

## Key Business Insights

- Sedan is the most preferred car type
- SUV is least preferred due to higher pricing
- Female customers show stronger preference for SUVs
- Male customers prefer Sedan and Hatchback more
- Married customers buy more cars than single customers
- Higher income customers show stronger preference for SUVs
- Customers with more dependents prefer spacious vehicles like SUVs and Sedans
- Personal loan holders prefer Sedan more frequently

---

## Business Questions Answered

### Example Questions Solved

- Do men prefer SUVs more than women?
- What is the likelihood of a salaried person buying a Sedan?
- Is salaried male an easier target for SUV sales?
- How does gender impact automobile spending?
- How does a working partner affect high-value car purchases?

---

## Recommendations

### Marketing Strategy Suggestions

- Age-based advertising campaigns
- Gender-focused promotions
- Salary-based premium targeting
- Loan-based financing campaigns
- Family-size focused SUV/Sedan targeting
- Education-based premium product positioning

These recommendations help improve conversion rates and customer segmentation.

---

## Project Outcome

This project provides strong business insights for customer targeting and helps Austo Motor Company improve marketing efficiency, product positioning, and sales strategy using data-driven decision making.

---

## Author

Vandana Kumari  
Data Analyst