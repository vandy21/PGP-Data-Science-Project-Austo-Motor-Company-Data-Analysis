# 🚗 Auto Motor Company Data Analysis

---

## 📌 Project Overview

This project analyzes customer behavior and automobile purchase patterns for Austo Motor Company, a car manufacturer offering SUVs, Sedans, and Hatchbacks.

The objective is to understand how customer demographics, income levels, financial status, and lifestyle factors influence vehicle purchasing decisions. The insights derived from this analysis help improve customer targeting, pricing strategies, and marketing effectiveness.

---

## 🎯 Objectives

* Identify key factors influencing car purchase decisions
* Analyze customer segmentation based on demographics and income
* Understand vehicle preference across different customer groups
* Provide data-driven recommendations for business growth

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Jupyter Notebook
* Excel

---

## 📂 Dataset Information

* **Total Rows:** 1581
* **Total Columns:** 14

### Key Variables

* Age, Gender, Profession
* Marital Status, Education
* Number of Dependents
* Personal Loan, House Loan
* Partner Working, Partner Salary
* Salary, Total Salary
* Price
* Car Type (SUV / Sedan / Hatchback)

---

## 🧹 Data Cleaning & Preprocessing

* Corrected inconsistent values in the Gender column
* Handled missing values by creating a separate category (`Gender_Unknown`)
* Derived missing Partner Salary using:
  **Partner Salary = Total Salary - Salary**
* Removed outliers using IQR method for:

  * Number of Dependents
  * Total Salary

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Age distribution
* Salary and Total Salary distribution
* Price distribution
* Customer demographics and categorical features

### 🔹 Bivariate Analysis

* Car Type vs Price
* Gender vs Car Preference
* Profession vs Car Type
* Salary vs Total Salary
* Correlation Heatmap

### 🔹 Multivariate Analysis

* Combined impact of marital status, dependents, and car preference

---

## 📊 Key Insights

* Sedan is the most preferred car category among customers
* SUVs are less preferred overall due to higher pricing
* Higher income customers show strong preference for SUVs
* Female customers tend to prefer SUVs more than male customers
* Male customers prefer Sedans and Hatchbacks
* Married customers have higher purchase rates compared to single customers
* Customers with more dependents prefer spacious vehicles like SUVs and Sedans
* Personal loan holders show higher inclination toward Sedans

---

## 📈 Business Impact

* Enables targeted marketing based on income and demographics
* Improves product positioning across customer segments
* Supports pricing strategy optimization
* Helps identify high-value customer groups
* Enhances decision-making using data-driven insights

---

## ❓ Business Questions Addressed

* Do men prefer SUVs more than women?
* What is the likelihood of a salaried individual purchasing a Sedan?
* Is a salaried male an ideal target for SUV sales?
* How does gender impact automobile spending?
* How does partner income influence high-value purchases?

---

## 🚀 Recommendations

* Implement income-based premium targeting strategies
* Design gender-focused marketing campaigns
* Promote financing options for loan-based customers
* Target families with SUVs and Sedans based on dependents
* Use education and profession data for premium product positioning

---

## 🏁 Conclusion

This project demonstrates how data analysis can uncover meaningful insights into customer behavior and purchasing patterns. The findings help Austo Motor Company enhance marketing strategies, improve customer segmentation, and drive better business decisions.

---

## 👩‍💻 Author

**Vandana Kumari**
Data Analyst | SQL | Python | Statistics

---
