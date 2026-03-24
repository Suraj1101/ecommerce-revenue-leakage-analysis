## 📊 E-commerce Revenue Leakage Analysis

### 🚀 Overview

End-to-end SQL + Power BI project analyzing revenue leakage, discount inefficiencies, and growth quality in an e-commerce dataset.

Built a structured data model and KPI framework to uncover hidden revenue loss and enable better, data-driven business decisions.

---

### 🎯 Business Problem

* Revenue leakage due to discounts, returns, and cancellations
* Poor visibility into true growth vs discount-driven growth
* Lack of prioritization in identifying high-impact problem areas

---

### 🧠 Approach

* Designed a scalable **star schema** (fact_sales + dimension tables)
* Built core KPIs: **Gross Revenue, Net Revenue, Leakage %, AOV**
* Developed a **Leakage Impact Score (Impact × Frequency)** to prioritize business issues
* Created a prioritization framework to identify high-impact revenue leakage areas

---

### 📊 Dashboard Pages

1. Overview
2. Leakage Analysis
3. Growth Analysis
4. Prioritization

---

### 🔍 Key Insights

* High-revenue categories also contribute significantly to leakage
* Growth is partially driven by heavy discounting, indicating dependency risk
* Returns and cancellations are major contributors to revenue loss
* Certain customer segments and payment methods show higher leakage behavior

---

### 🚀 Recommendations

* Optimize discount strategy to reduce unnecessary revenue erosion
* Focus on high-impact categories identified through prioritization
* Improve return and cancellation control mechanisms
* Monitor growth quality, not just topline revenue

---

### 🛠 Tools Used

SQL Server | Power BI | DAX

---

### 🏗 Data Model

**Star Schema:**
fact_sales + dim_customer, dim_product, dim_category, dim_date, dim_seller

---

### 📸 Dashboard Preview

### 📸 Dashboard Preview

#### 1. Overview
![Overview](link)

#### 2. Leakage Analysis
![Leakage](link)

#### 3. Growth Analysis
![Growth](link)

#### 4. Prioritization
![Prioritization](link)

---

### 🧩 Data Model (Power BI)
![Data Model](link)
