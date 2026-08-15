# Lift-Sales-Business-Performance-Analytics
Interactive Power BI Business Analytics dashboard for Lift Sales, Payments, Installation, Customer &amp; Builder Performance, with SQL-based analysis and DAX KPIs.

## 📊 Project Overview

**Lift Sales & Business Performance Analytics** is an interactive Power BI dashboard developed to analyze the end-to-end performance of a lift/elevator business.

The dashboard provides insights into:

* 📈 Sales performance
* 💳 Payment and collection status
* 🏗️ Lift installation progress
* 👥 Customer and builder performance
* 🌍 City-wise business performance
* 🛗 Lift-type analysis
* 🏆 Sales-person performance

### Business Flow

**Order Booking → Sales → Payment → Installation → Customer / Builder**

The main objective is to convert business data into meaningful KPIs, trends and actionable insights** for management decision-making.

---

## 🎯 Business Objectives

* Track overall sales and lift performance
* Analyze year-wise sales and order trends
* Compare city-wise sales performance
* Identify high-performing lift types
* Monitor advance received and outstanding balance
* Analyze payment status and payment modes
* Identify top sales performers
* Track installation progress
* Analyze customer and builder contribution
* Identify top and repeat customers

---

## 🛠️ Tools & Technologies

## Tools & Technologies

- Power BI – Dashboard & visualization
- Power Query – Data cleaning & transformation
- DAX – KPI calculations
- Microsoft Excel – Data source
- Data Modeling – Relationships & analysis

---

## 📂 Dashboard Pages

### 1️⃣ Overview Dashboard

Provides an executive summary of the business.

**Key KPIs:**

* Total Sales
* Total Lifts
* Total Buildings
* Total Builders

**Analysis includes:**

* Year-wise Sales Trend
* Order Booking Trend
* Sales by City
* Lift Type Analysis
* Building Type Analysis
* Top Customers

---

### 2️⃣ Sales Analysis

Focuses on revenue and payment performance.

**Key KPIs:**

* Total Sales
* Total Discount
* Advance Received
* Balance Amount

**Analysis includes:**

* Sales by Lift Type
* Payment Mode
* Payment Status
* Top Sales Person
* Customer-wise Sales & Discount
* City-wise Lift & Sales Performance

---

### 3️⃣ Installation & Lift Status

Tracks operational and installation performance.

**Key KPIs:**

* Total Lifts
* Total Installations
* In-Process Installations
* Total Cities

**Analysis includes:**

* Machine Type
* Installation Trend
* Installation Status
* Door Type
* City-wise Installation

---

### 4️⃣ Customer Details

Provides customer and builder-level analysis.

**Analysis includes:**

* Builder Name
* Total Lifts
* Total Sales
* Discount
* Balance Amount
* Total Buildings
* Top & Repeat Customers

---

## 🧮 DAX Measures

Example measures used in the dashboard:

```DAX
Total Sales =
SUM(Sales[Sales Amount])

Total Discount =
SUM(Sales[Discount])

Advance Received =
SUM(Sales[Advance Amount])

Balance Amount =
[Total Sales] - [Advance Received]

Total Lifts =
DISTINCTCOUNT(Sales[Lift ID])

Total Buildings =
DISTINCTCOUNT(Sales[Building ID])

Total Builders =
DISTINCTCOUNT(Sales[Builder Name])
```

---

## 🧹 Data Cleaning & Transformation

Data preparation was performed using **Power Query**.

Key transformations included:

* Removing duplicate records
* Handling missing values
* Correcting data types
* Standardizing text values
* Cleaning date fields
* Removing unnecessary columns/records
* Preparing analysis-ready data

---

## 🔍 Key Business Insights

* Recent years show a **slight decline in sales**, indicating a need for stronger sales strategies.
* Sales contribution varies significantly across cities.
* Payment status analysis highlights **paid, partial and pending collections**.
* Installation tracking provides visibility into completed and in-process projects.
* Top-customer analysis helps identify valuable customer relationships.
* Lift-type analysis helps identify high-demand product categories.
* Sales-person analysis helps management compare individual performance.

---

## 💡 Business Recommendations

### Sales

* Investigate the recent decline in sales.
* Improve lead generation and conversion.
* Focus on low-performing cities.
* Strengthen customer retention.

### Payments

* Prioritize pending payments.
* Follow up with partially paid customers.
* Monitor outstanding balances regularly.

### Installation

* Reduce installation delays.
* Improve installation planning and scheduling.
* Closely monitor in-process installations.

### Customers & Products

* Focus on high-value customers and builders.
* Encourage repeat orders.
* Analyze lift-type demand by city.
* Identify new market opportunities.


## 🚀 Project Outcome

This Power BI solution provides a centralized view of **sales, payments, installations, customers and business performance**, helping management identify trends, monitor operational progress and make data-driven decisions.

---

## 👨‍💻 Skills Demonstrated

**Power BI • DAX • Power Query • Data Cleaning • Data Modeling • KPI Development • Data Visualization • Business Analytics**
