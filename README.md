# Diwali Sales Analysis 🛍️

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Diwali sales data to understand customer behavior and improve business decision-making.

The analysis focuses on identifying:

* Key customer segments
* Purchasing patterns
* High-performing product categories

---

## Objective

The main goal is to:

* Identify **target customers**
* Understand **buying behavior during Diwali**
* Help businesses **increase sales and improve customer experience**

---

## Tools & Libraries Used

* Python
* Pandas (Data cleaning & manipulation)
* NumPy (Numerical operations)
* Matplotlib & Seaborn (Data visualization)

---

## 📂 Dataset

The dataset contains **Diwali sales transaction data** with customer demographics and purchasing details.

---

## Data Cleaning Steps

The dataset initially had **11,251 rows and 15 columns**.

### ✔ Cleaning Performed:

* Removed unnecessary columns: `Status`, `unnamed1`
* Handled missing values:

  * Dropped **12 null values** from `Amount` column
* Converted data types:

  * `Amount` from float → integer

### ✔ Final Dataset:

* **11,239 rows**
* **13 columns**

---

## Exploratory Data Analysis (EDA)

### Gender Analysis

* Majority of buyers are **female**
* Females contribute **higher purchasing power**

---

### Age Group Analysis

* Highest buyers belong to **26–35 age group**
* **Females in this group** are top contributors

---

### State-wise Analysis

Top 3 states with highest sales:

* Uttar Pradesh
* Maharashtra
* Karnataka

---

### Marital Status

* Most buyers are **unmarried**
* This group shows **higher spending behavior**

---

### Occupation Analysis

Top contributing sectors:

* Healthcare
* IT
* Banking

---

### Product Category Analysis

Most purchased categories:

* Food
* Footwear
* Electronics

---

### Top Products

* Identified **Top 10 selling products** using `Product_ID`

---

## Key Insights

* Women are the **primary buyers during Diwali**
* Age group **26–35 dominates purchasing**
* Certain states consistently generate **high revenue**
* Specific occupations show **strong purchasing patterns**
* Product demand is concentrated in **essential and lifestyle categories**

---

## Conclusion

👉 The ideal target customers are:

* **Unmarried women**
* Age group: **26–35 years**
* Location: **Uttar Pradesh, Maharashtra, Karnataka**
* Occupation: **IT, Healthcare, Banking**

👉 These customers are most likely to purchase:

* Food
* Clothing
* Electronics

---

## 📈 Project Outcome

This analysis helps businesses:

* Improve marketing strategies
* Target the right audience
* Increase sales during festive seasons
