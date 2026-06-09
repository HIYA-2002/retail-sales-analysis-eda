# 📊 Retail Sales Analysis & Customer Segmentation

## 🚀 Project Overview

This project presents an end-to-end Exploratory Data Analysis (EDA) of a retail sales dataset using Python. The goal is to uncover actionable business insights related to customer purchasing behavior, product performance, sales trends, and customer segmentation.

The analysis includes data cleaning, feature engineering, visualization, and RFM (Recency, Frequency, Monetary) analysis to identify valuable customer groups and support data-driven business decisions.

---

## 🎯 Objectives

* Analyze sales performance across product categories.
* Understand customer demographics and purchasing patterns.
* Identify top-performing products and customer segments.
* Discover trends in sales and revenue generation.
* Perform customer segmentation using RFM Analysis.

---

## 📂 Dataset Information

The dataset contains retail transaction records with the following attributes:

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| Customer ID      | Unique customer identifier    |
| Gender           | Customer gender               |
| Age              | Customer age                  |
| Product Category | Category of purchased product |
| Quantity         | Number of units purchased     |
| Price Per Unit   | Price of each product         |
| Total Amount     | Total transaction value       |
| Date             | Date of purchase              |

---

## 🛠️ Project Workflow

### 1️⃣ Data Loading & Inspection

* Imported dataset using Pandas
* Explored data structure
* Checked data types and summary statistics

### 2️⃣ Data Cleaning

* Missing value analysis
* Duplicate record checks
* Data formatting and validation

### 3️⃣ Feature Engineering

* Date conversion and extraction
* Revenue calculations
* Additional analytical features

### 4️⃣ Exploratory Data Analysis (EDA)

#### Univariate Analysis

* Age Distribution
* Product Category Distribution
* Revenue Distribution

#### Bivariate Analysis

* Revenue by Product Category
* Revenue by Gender
* Customer Purchase Behavior

#### Multivariate Analysis

* Relationship between key variables
* Sales performance trends

### 5️⃣ Customer Segmentation

* Customer grouping based on purchase behavior
* Identification of high-value customers

### 6️⃣ RFM Analysis

RFM analysis was performed using:

* **Recency** → How recently a customer purchased
* **Frequency** → How often a customer purchases
* **Monetary** → How much a customer spends

This helps identify:

* Loyal Customers
* High-Value Customers
* Potential Customers
* At-Risk Customers

---

## 📈 Key Insights

* Certain product categories contribute significantly more revenue than others.
* Customer demographics influence purchasing behavior.
* A small percentage of customers generate a large portion of overall revenue.
* RFM segmentation effectively identifies valuable customer groups.
* Sales trends reveal opportunities for targeted marketing and customer retention strategies.

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 💡 Business Impact

This analysis can help retail businesses:

* Improve customer retention
* Optimize marketing campaigns
* Increase revenue generation
* Better understand customer behavior
* Support strategic decision-making

---

## 📁 Repository Structure

```text
retail-sales-analysis-eda/
│
├── README.md
├── retail_sales_eda.ipynb
├── dataset/
│   └── retail_sales_dataset.csv
│
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/retail-sales-analysis-eda.git
```

2. Navigate to the project folder

```bash
cd retail-sales-analysis-eda
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open and run:

```text
retail_sales_eda.ipynb
```

---

## 📊 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis
* Data Visualization
* Customer Segmentation
* RFM Analysis
* Business Analytics
* Python Programming

---

## 👩‍💻 Author

**Hiya Maiti**

Aspiring Data Analyst | Data Science Enthusiast

If you found this project useful, feel free to ⭐ the repository.
