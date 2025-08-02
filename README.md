# E-commerce-Dashboard-by-Power_BI-and-Python
## 🚀 Project Overview
This project demonstrates how to build and analyze an E-Commerce sales dataset using two powerful tools:

- 📊 **Power BI** for business intelligence and drag-and-drop visual dashboards

- 🐍 **Python** (Matplotlib & Pandas) for programmatic analysis and visualization

It highlights how the same dataset can be analyzed using both no-code and code-first approaches — ideal for hybrid data roles.

### 🔧Tools & Libraries Used
|Tools      |Purpose                           |
|-----------|----------------------------------|
|Power BI   | Business dashboard and DAX KPIs  |
|Python     | Data analysis and static charts  |
|Pandas     | Data wrangling                   |
|Matplotlib | Visualization (bar, line, funnel)|

### 📊KPIs Tracked
- ✅ **Total Orders**
- 💸 **Total Revenue**
- 📦 **Average Order Value**
- 🌍 **Orders by Country**
- 🛒 **Revenue by Sales Channel**
- 📉 **Sales Funnel Conversion:**

## 📈 Power BI Dashboard

> Found in `ecommerce-powerbi`

### 📌 Features:
- Interactive filters (Channel, Country, Date)
- Funnel chart showing conversion drop-offs
- Visuals: Donut chart, clustered bar chart, time-series line chart, KPI cards

📷 *Example screenshot:*

![Power BI Dashboard](ecommerce-powerbi/E-commerce%20Powerbi%20ss.png)

---

## 🐍 Python Dashboard

> Found in `ecommerce-python`

### 📌 Features:
- KPI calculations using Pandas (`.sum()`, `.mean()`)
- Bar chart for revenue by channel
- Simulated funnel chart using horizontal bar plot
- Monthly revenue trend using line plot

---

## 📂 Dataset

A sample e-commerce dataset was used containing the following fields:
- `SessionDate`
- `Country`
- `Channel`
- `AddedToCart`
- `CheckoutStarted`
- `PurchaseCompleted`
- `Revenue`

*(Dataset file included in `Ecommerce_Funnel_Dataset.xlsx`)*

---

## 📚 Learning Outcomes

- 📊 Build interactive dashboards in Power BI using DAX and visuals
- 🐍 Perform the same analysis in Python using code and charts
- 🧠 Interpret KPIs like revenue trends, conversion rates, and category performance
- 🔀 Gain versatility in using both business-friendly and technical tools

---

## 📎 How to Use

1. Clone or download the repo
2. Open the `.pbix` file in Power BI Desktop
3. Open the `.ipynb` file in Jupyter Notebook
4. Run the cells and explore the dashboard visuals
