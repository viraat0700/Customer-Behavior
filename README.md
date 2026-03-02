# 📊 Customer Shopping Behavior Analysis

## 🔎 Overview

This end-to-end Data Analytics project analyzes customer shopping behavior using transactional purchase data.

The goal of this project was to:

* Understand customer spending patterns
* Identify product preferences
* Segment customers based on behavior
* Analyze subscription trends
* Generate business insights for better decision-making

The project follows a complete analytics lifecycle:

➡️ Data Loading → Cleaning → EDA → SQL Analysis → Visualization → Reporting → Business Insights

---

## 📁 Dataset

The dataset contains **3,900 customer purchase records** across multiple product categories 

### Key Information:

* Customer demographics (Age, Gender, Location)
* Purchase behavior
* Product details
* Subscription status
* Discount usage
* Shipping preferences
* Review ratings

Missing values were present in the **Review Rating column (37 values)** and were handled during data cleaning 

---

## 🛠️ Tools & Technologies Used

| Tool                            | Purpose                 |
| ------------------------------- | ----------------------- |
| Python (Pandas, NumPy)          | Data Loading & Cleaning |
| Jupyter Notebook                | EDA                     |
| PostgreSQL / MySQL / SQL Server | Business Analysis       |
| Power BI                        | Dashboard               |
| Gamma                           | Presentation            |
| GitHub                          | Project Hosting         |

---

## ⚙️ Project Workflow

### 1. Data Loading (Python)

* Loaded CSV dataset using Pandas
* Checked structure using `.info()` and `.describe()` 

### 2. Data Cleaning

* Handled missing values
* Standardized column names
* Removed redundant fields
* Created new features:

  * `age_group`
  * `purchase_frequency_days` 

### 3. Exploratory Data Analysis (EDA)

* Customer demographics analysis
* Purchase behavior trends
* Discount impact study
* Subscription comparison

### 4. SQL Business Analysis

Data was pushed into SQL database for deeper insights.

Key questions answered:

* Revenue by gender
* Top-rated products
* Discount usage patterns
* Shipping impact on spending
* Subscriber vs non-subscriber behavior
* Customer segmentation (New / Returning / Loyal) 

Example Insight:

➡️ Loyal customers formed the largest segment (shown in segmentation table on page 5) 

---

## 📊 Dashboard (Power BI)

An interactive dashboard was built to visualize insights such as:

* Revenue by category
* Sales by age group
* Subscription distribution
* Customer count
* Average purchase amount

The dashboard provides a quick business view of:

* Customer value
* Product performance
* Revenue drivers 

---

## 📈 Key Insights

* Female vs Male revenue contribution differed significantly (page 3 comparison) 
* Express shipping users spent more on average than standard users (page 4) 
* Loyal customers dominated the customer base (page 5) 
* Young adults contributed the highest revenue (page 7) 

---

## 📄 Deliverables

* Python EDA Notebook
* Cleaned Dataset
* SQL Analysis
* Power BI Dashboard
* Business Report
* Gamma PPT Presentation

---

## ▶️ How to Run

### Step 1: Clone Repository

```bash
git clone <your-repo-link>
```

### Step 2: Run Python Notebook

Open:

```
PythonProject.ipynb
```

Run all cells to:

* Load data
* Clean data
* Perform EDA

### Step 3: Load Data into SQL

Use PostgreSQL / MySQL / SQL Server

Run SQL queries to generate insights.

### Step 4: Open Power BI Dashboard

Open:

```
customer_behavior_dashboard.pbix
```

### Step 5: View Final Report

Refer:

```
Customer Shopping Behavior Analysis.pdf
```

---

## 🚀 Business Impact

This project demonstrates how raw customer data can be transformed into:

✔️ Actionable insights
✔️ Customer segmentation
✔️ Revenue optimization strategies
✔️ Marketing decision support
