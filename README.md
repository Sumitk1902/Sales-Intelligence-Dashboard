# 📊 Sales Intelligence Dashboard

An interactive **Power BI Sales Intelligence Dashboard** built to analyze sales, profitability, customers, products, regional performance, and target achievement.

The dashboard transforms raw sales data into an interactive business reporting solution with KPI tracking, visual analysis, filters, and page navigation.

---

## 📸 Dashboard Preview

### Executive Dashboard

The executive page provides a high-level overview of overall sales and business performance.

![Executive Dashboard](D1.jpeg)

---

### Product Analysis

Analyzes sales and profitability across categories and sub-categories.

![Products Dashboard](D2.jpeg)

---

### Customer Analysis

Provides insights into customer performance and geographical sales distribution.

![Customers Dashboard](D3.jpeg)

---

### Target Performance

Tracks actual sales against targets and highlights target achievement and sales variance.

![Targets Dashboard](D4.jpeg)

---

## 🎯 Project Objective

The objective of this project is to create an interactive sales analytics dashboard that helps users:

- Monitor overall business performance
- Track sales and profitability
- Compare actual sales with targets
- Analyze product and category performance
- Identify top customers
- Compare regional sales performance
- Understand sales trends over time
- Evaluate target achievement

---

## 📊 Key KPIs

The dashboard tracks:

- **Total Sales**
- **Total Profit**
- **Profit Margin %**
- **Sales Target**
- **Sales Variance**
- **Target Achievement %**
- **Total Customers**
- **Total Orders**
- **Total Quantity**
- **Average Order Value**

---

## 📑 Dashboard Pages

### 1. Executive

Provides a management-level overview of the business.

**Includes:**
- Total Sales
- Sales Variance
- Target Achievement
- Total Profit
- Profit Margin
- Sales by Category
- Sales by State
- Sales vs Target by Month

### 2. Products

Focuses on product and category performance.

**Includes:**
- Sales by Category
- Profit by Category
- Sales by Sub-Category
- Category comparison
- Sub-category analysis

### 3. Customers

Focuses on customer and geographical performance.

**Includes:**
- Total Customers
- Top 10 Customers by Sales
- Sales by State
- Sales by City
- State-level filtering

### 4. Targets

Focuses on target monitoring and performance.

**Includes:**
- Total Sales
- Sales Target
- Sales Variance
- Target Achievement %
- Monthly Sales vs Target
- Target Achievement Gauge

---

## 🔍 Interactive Features

- Page navigation
- Month/Year filtering
- Category filtering
- State filtering
- Cross-filtering between visuals
- KPI cards
- Interactive charts
- Target performance analysis
- Drill-through functionality

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data transformation |
| **DAX** | KPI and business calculations |
| **Data Modeling** | Relationships between datasets |
| **Power BI Visuals** | Interactive data analysis |

---

## 🧮 Data Model

The dashboard uses multiple related tables for sales and target analysis, including:

- Calendar
- List of Orders
- Order Details
- Category
- Sales Target

The data model enables analysis across:

**Time → Products → Categories → Customers → Geography → Targets**

---

## 💡 Business Questions

The dashboard helps answer questions such as:

- What are the current total sales and profit?
- Are actual sales meeting the target?
- What is the current target achievement percentage?
- Which category generates the highest sales?
- Which category generates the highest profit?
- Which sub-categories perform best?
- Who are the top customers by sales?
- Which states generate the highest sales?
- Which cities contribute the most revenue?
- How does sales performance change over time?
- What is the gap between actual sales and the target?

---

## 📁 Repository Structure

```text
Sales-Intelligence-Dashboard/
│
├── Dashboard SS/
│   ├── D1.jpeg
│   ├── D2.jpeg
│   ├── D3.jpeg
│   └── D4.jpeg
│
├── Data Files/
│   └── Source Data
│
├── Sales Intelligence Dashboard.pbix
│
└── README.md
