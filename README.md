# Customer_Behavior_Analysis
Data Analytics project showcasing customer behavior analysis using python, sql and power BI
Alright Leo, here’s a clean, recruiter-friendly **professional README** for your data analytics project — polished enough for GitHub, but still giving that sharp, modern vibe. I’ve blended your workflow + insights from the PPT you shared.

---

# 📊 Customer Shopping Behavior Analysis

*A complete end-to-end data analytics workflow — from raw CSV to business insights.*

## 🧠 Overview

This project digs into **3,900 customer purchase records** to understand buying patterns, customer segments, revenue drivers, and product performance.
The workflow covers everything from **Python-based EDA**, **data cleaning**, **SQL analytics**, **Power BI dashboards**, and a **final presentation built using Gamma**.

If you’re a recruiter skimming this: this project shows my ability to handle real datasets, run analytics across multiple tools, build dashboards, and deliver insights that matter.

---

## 📂 Dataset

* **Transactions:** 3,900
* **Features:** 18
* **Locations Covered:** 50
* **Products:** 25

Key fields include:
`age`, `gender`, `category`, `quantity`, `price`, `rating`, `location`, `shipping_type`, `payment_method`, `discount_applied`, `subscription_status`, etc.

---

## 🛠️ Tools & Technologies

* **Python:** pandas, numpy, matplotlib/seaborn
* **SQL Databases:** PostgreSQL / MySQL / SQL Server
* **Power BI:** Dashboard & KPI visualization
* **Gamma App:** Presentation creation
* **Jupyter Notebook:** Analysis environment

---

## 🔍 Project Steps

### 1️⃣ Data Loading & Initial Exploration

* Loaded CSV using **pandas**
* Explored structure using `df.info()`, `df.describe()`, missing value checks
* Analyzed categorical & numerical patterns

### 2️⃣ Data Cleaning

* Handled missing values (e.g., 37 missing ratings)
* Fixed inconsistent columns & converted to **snake_case**
* Removed outliers using IQR method
* Standardized datatypes

### 3️⃣ Feature Engineering

Created new attributes for deeper insights:

* **age_group** (teen / young adult / middle-aged / senior)
* **purchase_frequency_days**
* **is_high_value_customer**
* **discount_user_category**

### 4️⃣ SQL Analytics

Loaded cleaned dataset into a database to run SQL queries like:

* Revenue by gender, age group, and product
* Customer segmentation (new, returning, loyal)
* Subscription vs non-subscription patterns
* High-value discount user analysis
* Shipping method impact on revenue

### 5️⃣ Power BI Dashboard

The dashboard includes:

* **Revenue by Gender**
* **Top-Rated Products**
* **Customer Segmentation** (New, Returning, Loyal)
* **Age Group Revenue Distribution**
* **Discount Usage Behavior**

Key insights visualized:

* Male customers generate **68%** of revenue
* Subscribers vs non-subscribers show **similar average spending**
* Loyal customers make up **80%** of all users
* Express shipping users spend **3.5% more per transaction**

### 6️⃣ Final Deliverables

* **Detailed Analysis Report**
* **Gamma Presentation:** clean, modern slide deck summarizing insights
* **Power BI Interactive Dashboard**

---

## 📈 Key Results

Some high-impact findings from this project:

### 💡 Revenue Insights

* Male customers: **$157,890**
* Female customers: **$75,191**

### ⭐ Product Performance

Top-rated items:

* Gloves (3.86)
* Sandals (3.84)
* Boots (3.82)

### 🔥 Customer Segmentation

* Loyal: **3,116**
* Returning: **701**
* New: **83**

### 🧾 Subscription Analysis

* Subscribers: **27%**
* Non-subscribers: **73%**
* Avg spend is almost identical for both

### 📦 Shipping Behavior

* Express: $60.48 average
* Standard: $58.46

---

## 🚀 How to Run This Project

### **1. Clone the repo**

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### **2. Install Python dependencies**

```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebook**

```bash
jupyter notebook
```

### **4. Load data into SQL (optional step)**

Use the included SQL schema or simply import CSV via pgAdmin / MySQL Workbench.

### **5. Open Power BI Dashboard**

File: `shopping_dashboard.pbix`

### **6. View the Final Gamma Presentation**

File: `Customer-Shopping-Behavior-Analysis.pptx`


---

