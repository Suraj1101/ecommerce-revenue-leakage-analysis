# 📊 E-commerce Revenue Leakage Analysis (SQL + Power BI)

## 🚀 Overview

This project builds an end-to-end analytics solution to identify revenue leakage, discount inefficiencies, and growth quality in an e-commerce dataset.

The goal is to transform raw transactional data into a structured analytical model and generate actionable business insights.

---

## 🧠 Business Problem

E-commerce businesses often struggle with:

* High discount dependency
* Revenue loss due to cancellations and returns
* Lack of clarity on category performance
* Misleading growth driven by discounts

This project addresses these challenges using data modeling and analytics.

---

## 🏗️ Data Architecture

```
Raw CSV → SQL Server → Clean View → Star Schema → Power BI Dashboard
```

### Tables Created:

* **Fact Table:** `fact_sales`
* **Dimensions:**

  * `dim_customer`
  * `dim_product`
  * `dim_category`
  * `dim_date`
  * `dim_seller`

---

## 🔧 Data Modeling

* Designed a **star schema** for scalable analysis
* Handled duplicates and ensured **1-to-many relationships**
* Separated category into its own dimension to avoid many-to-many issues
* Created a proper date table for time intelligence analysis

---

## 📊 Key Metrics

* Gross Revenue
* Net Revenue
* Discount Amount
* Average Order Value (AOV)
* Discount Erosion %
* Leakage %
* Cancellation Rate
* Return Rate
* Growth Metrics (MoM / YoY)

---

## 🔍 Key Insights

* Some categories generate high revenue but also contribute significantly to leakage
* Growth is partially driven by discounts, indicating dependency risk
* Returns and cancellations are major contributors to revenue loss
* Certain payment methods show higher leakage behavior

---

## 📈 Dashboard Features

* Revenue vs Net Revenue comparison
* Category-level performance analysis
* Discount impact and dependency tracking
* Leakage analysis (returns + cancellations)
* Growth trend analysis
* Priority-based decision framework

---

## 🛠️ Tools Used

* SQL Server (Data modeling & transformation)
* Power BI (DAX & visualization)
* CSV (Raw dataset)

---

## 📸 Dashboard Preview

(Add screenshots here)

---

## 📌 Author

**Suraj Bhandari**

