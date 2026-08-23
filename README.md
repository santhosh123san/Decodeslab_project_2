# 📊 Excel Data Analytics & Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an e-commerce dataset using **Python, Pandas, Matplotlib, Plotly, and Excel**.

The objective is to transform raw transactional data into meaningful analytical insights by examining sales performance, customer behavior, order patterns, payment methods, referral sources, and data distributions.

The project also includes **outlier detection, correlation analysis, interactive visualizations, and an Excel-based analytics dashboard**.

---

## 🎯 Project Objectives

* Understand the structure and quality of the dataset
* Perform descriptive statistical analysis
* Analyze product-wise sales performance
* Identify monthly and yearly sales trends
* Analyze order status distribution
* Analyze payment method usage
* Analyze referral sources
* Examine coupon usage
* Detect statistical outliers using the IQR method
* Identify relationships between numerical variables
* Create interactive visualizations
* Build an Excel analytics dashboard
* Generate an analysis-ready Excel report

---

## 🛠️ Technologies & Tools

| Tool                | Purpose                          |
| ------------------- | -------------------------------- |
| **Python**          | Data analysis and processing     |
| **Pandas**          | Data manipulation and EDA        |
| **NumPy**           | Numerical operations             |
| **Matplotlib**      | Static visualizations            |
| **Plotly**          | Interactive visualizations       |
| **Google Colab**    | Cloud-based analysis environment |
| **Microsoft Excel** | Reporting and dashboard          |
| **OpenPyXL**        | Excel report generation          |

---

## 📂 Dataset

The dataset contains **1,200 e-commerce transaction records** with information related to orders, products, customers, pricing, payment methods, and order status.

### Important Columns

* `OrderID`
* `CustomerID`
* `Product`
* `Quantity`
* `UnitPrice`
* `ItemsInCart`
* `PaymentMethod`
* `OrderStatus`
* `ReferralSource`
* `CouponCode`
* `TotalPrice`
* `Date`

---

# 🔍 Exploratory Data Analysis

The analysis was performed in several stages.

## 1. Data Preparation

* Loaded the Excel dataset using Pandas
* Converted date fields into proper datetime format
* Created Year and Month columns
* Checked numerical variables
* Prepared the dataset for analysis

---

## 2. Descriptive Statistics

Statistical measures were calculated for:

* Quantity
* Unit Price
* Items in Cart
* Total Price

The analysis includes:

* Count
* Mean
* Median
* Minimum
* Maximum
* Standard Deviation

---

## 3. Product Analysis

Product-level performance was analyzed using:

* Total Sales
* Number of Orders
* Quantity Sold

This helps identify the products contributing the most to overall sales.

---

## 4. Sales Trend Analysis

Sales trends were analyzed at two levels:

### Monthly Analysis

Examines changes in sales and order volume across months.

### Yearly Analysis

Provides a high-level view of annual sales performance.

---

## 5. Order Status Analysis

Orders were analyzed based on their status to understand the distribution of different order outcomes.

---

## 6. Payment Method Analysis

The project analyzes the number of orders associated with different payment methods.

This helps understand customer payment preferences.

---

## 7. Referral Source Analysis

Referral sources were analyzed to identify which channels generate the highest number of orders.

---

## 8. Coupon Usage Analysis

Coupon codes were analyzed to understand their usage across orders.

---

# 🚨 Outlier Analysis

Outliers were detected using the **Interquartile Range (IQR)** method.

### Formula

```text
IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR
```

Outlier analysis was performed on:

* `TotalPrice`
* `Quantity`

### Result

* **TotalPrice Outliers:** 8
* **Quantity Outliers:** 0

Outlier records are stored separately in the Excel report for further investigation.

---

# 🔗 Correlation Analysis

Correlation analysis was performed on the numerical variables:

* Quantity
* UnitPrice
* ItemsInCart
* TotalPrice

A correlation matrix was generated to understand relationships between the numerical variables.

---

# 📊 Key Performance Indicators

The dashboard includes the following KPIs:

| KPI                     | Description                     |
| ----------------------- | ------------------------------- |
| **Total Orders**        | Total number of transactions    |
| **Total Sales**         | Overall transaction value       |
| **Average Order Value** | Average value per order         |
| **Total Quantity**      | Total number of items purchased |
| **Average Unit Price**  | Average product price           |
| **Unique Customers**    | Number of unique customers      |
| **Unique Products**     | Number of unique products       |

### Dataset Results

* **Total Orders:** 1,200
* **Total Sales:** 1,264,761.96
* **Average Order Value:** 1,053.97
* **TotalPrice Outliers:** 8
* **Quantity Outliers:** 0

---

# 📈 Dashboard & Visualizations

The project generates an interactive dashboard in Google Colab using **Plotly**.

### Visualizations include:

* 📊 Sales by Product
* 📈 Monthly Sales Trend
* 📊 Yearly Sales Trend
* 🥧 Order Status Distribution
* 🥧 Payment Method Distribution
* 📊 Orders by Referral Source
* 📊 Coupon Usage
* 📉 Total Price Distribution
* 📉 Quantity Distribution
* 🔗 Correlation Matrix

The analysis can be executed from a **single Google Colab code cell**.

---

# 📗 Excel Analytics Report

An automated Excel report is generated using Python and OpenPyXL.

### Excel Workbook Structure

```text
Excel_EDA_Analytics_Report.xlsx
│
├── Dashboard
├── Analyzed Dataset
├── Descriptive Statistics
├── Product Analysis
├── Monthly Trend
├── Yearly Trend
├── Order Status
├── Payment Method
├── Referral Source
├── Coupon Usage
├── Outlier Summary
├── TotalPrice Outliers
├── Quantity Outliers
├── Correlation
└── Charts
```

The Excel workbook contains both analytical tables and embedded visualizations.


---

# 🚀 How to Run the Project

## Option 1 — Google Colab

1. Open Google Colab
2. Create a new notebook
3. Upload the Excel dataset
4. Copy the project code into the notebook
5. Run the cell
6. Upload your dataset when prompted
7. The EDA dashboard will be generated
8. The Excel analytics report will be automatically created

---

## Option 2 — Local Python Environment

Install the required libraries:

```bash
pip install pandas numpy matplotlib plotly openpyxl
```

Then run the Python notebook or script.

---

# 💡 Business Questions Answered

This project can help answer questions such as:

* Which products generate the highest sales?
* How are sales changing over time?
* Which payment methods are most commonly used?
* Which referral sources generate the most orders?
* How frequently are coupons used?
* What is the average order value?
* Are there unusual or extreme transaction values?
* Which numerical variables have strong relationships?
* How is the overall sales performance distributed?

---

# 📌 Key Insights

The analysis provides a foundation for identifying:

* High-performing products
* Sales trends
* Customer purchasing patterns
* Payment preferences
* Marketing/referral performance
* Unusual transaction values
* Relationships between transaction variables

These insights can support **business reporting and data-driven decision making**.

---

# 🎓 Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis
* Data Cleaning
* Data Preparation
* Descriptive Statistics
* Outlier Detection
* Correlation Analysis
* KPI Analysis
* Business Insight Generation

### Technical Skills

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* Excel
* OpenPyXL
* Google Colab

### Visualization

* Bar Charts
* Line Charts
* Pie Charts
* Histograms
* Correlation Heatmaps
* Interactive Charts
* KPI Dashboards

---

# 📌 Project Outcome

The project demonstrates an end-to-end **Data Analyst workflow**, starting from a raw Excel dataset and progressing through data preparation, exploratory analysis, statistical analysis, visualization, dashboard creation, and automated reporting.

The final output provides both an **interactive Google Colab dashboard** and a structured **Excel analytics report** suitable for business analysis and portfolio presentation.

---

## 👨‍💻 Author

**Santhosh T.**

**B.Tech Information Technology**
Mahendra Institute of Technology

### Career Interests

* Data Analytics
* Business Intelligence
* Data Visualization
* Excel
* Power BI
* SQL
* Python

---

⭐ If you found this project useful, consider giving the repository a star.
