# 🪔 Diwali Sales Data Analytics

A data analytics project to explore and visualize **Diwali sales data** using Python.  
This project focuses on identifying customer purchasing patterns across different **genders**, **age groups**, **states**, and **order amounts**, providing business insights to boost future sales strategies.

---

## 📌 Project Overview

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on a Diwali Sales dataset to uncover trends and actionable insights, such as:
- Which **gender** contributes most to sales?
- Which **age groups** are the most active buyers?
- Which **states** generate the highest number of orders and revenue?
- How different customer segments behave during Diwali sales.

---

## 🧰 Tech Stack

- **Python**
- **Pandas** – Data cleaning & manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical plots & styling  
- **Jupyter Notebook**

---

## 📂 Dataset

- **File Name:** `Diwali Sales Data.csv`  
- **Description:** Contains customer details, product information, order details, and transaction amounts.  
- **Encoding Used:** `unicode_escape` (to handle special characters)

---

## 📝 Analysis Steps

1. **Import libraries** and load dataset  
2. **Data cleaning**  
   - Dropped unnecessary columns (`Status`, `unnamed1`)  
   - Checked for null values  
3. **Exploratory Data Analysis (EDA)**  
   - Gender-wise sales analysis  
   - Age group distribution with gender comparison  
   - Sales by age group  
   - Top 10 states by orders and total amount  
4. **Data Visualization** using Matplotlib & Seaborn for insights.

---

## 📈 Key Insights

- **Female customers** contributed the highest sales amount during Diwali.  
- Customers aged **26–35 years** are the most active buyers.  
- Top contributing states include **Uttar Pradesh, Maharashtra, and Karnataka**.  
- Targeting female customers in the 26–35 age group could increase sales further.

---

## 🖼️ Sample Visualization

> Add an image named `dashboard-preview.png` inside an `images/` folder, then use:

```markdown
![Sales Dashboard](images/dashboard-preview.png)
