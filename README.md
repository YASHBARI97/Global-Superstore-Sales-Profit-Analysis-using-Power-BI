# Global-Superstore-Sales-Profit-Analysis-using-Power-BI

# 📊 Global Superstore Power BI Dashboard

## 🧠 Project Overview
This Power BI project analyzes the **Global Superstore dataset** to uncover insights on **sales performance, profit trends, customer segments, product categories, and regional contributions**.  
It leverages DAX measures, time intelligence, and interactive visuals to help businesses make data-driven decisions and optimize profitability.

---

## ⚙️ Data Model Overview
The report follows a **Star Schema** data model with clearly defined fact and dimension tables.

- **Fact Tables:**
  - Orders
  - Sales

- **Dimension Tables:**
  - Customers
  - Products
  - Location
  - Date

Relationships are built through key fields such as `Customer ID`, `Product ID`, and `Order ID`, ensuring a structured and optimized data flow.

---

## 🧮 DAX Measures Created

| Measure | Description |
|----------|--------------|
| **Total Sales** | SUM of sales transactions |
| **Total Profit** | SUM of profit earned |
| **Total Orders** | DISTINCTCOUNT of Order IDs |
| **Total Quantity** | SUM of quantity sold |
| **% of Discount on Total Sales** | (Total Discount ÷ Total Sales) × 100 |
| **Sales PY** | Sales from the same period last year |
| **Profit PY** | Profit from the same period last year |
| **Orders PY** | Orders count from the same period last year |
| **Quantity PY** | Quantity from the same period last year |

These measures enable **comparative, time-series, and profitability analysis** across all business dimensions.

---

## 📈 Dashboard Pages & Visuals

### 🟣 1. **Overview Dashboard**
**Purpose:** Provide a quick summary of sales, profit, and quantity across customer segments and regions.  
**Key Visuals:**
- KPI Cards (Sales, Profit, Orders, Quantity, Shipping Cost)
- Bar Chart (Profit by Region)
- Donut Chart (Quantity & Sales by Category)
- Monthly Profit Trend
- Segment-wise Distribution  

**Insights:**
- Total Sales: ₹32.33M  
- Total Profit: ₹3.63M  
- Central region leads in profitability.  
- Technology contributes the largest share of total sales.

---

### 🟢 2. **Performance Comparison Dashboard**
**Purpose:** Evaluate current year vs previous year performance (YoY).  
**Visuals:**
- KPI Cards for Sales PY, Profit PY, Orders PY, Quantity PY  
- Date, Region, and Category Slicers  
- Tree Map for Sales by Category & Region  

**Insights:**
- Sales and profit are consistent across years.  
- Corporate and Consumer segments dominate sales volume.  
- Technology continues to show the highest YoY growth.

---

### 🟠 3. **Regional & Category Analysis Dashboard**
**Purpose:** Visualize the geographic distribution of sales and profits.  
**Visuals:**
- Map showing Profit by Country & Category  
- Tree Map showing Category and Sub-Category contribution  

**Insights:**
- Highest profits from USA, India, and Australia.  
- Phones and Copiers drive most of the profit growth.  
- Furniture has high sales but lower profitability due to discounts.

---

### 🔵 4. **Segment Analysis Dashboard**
**Purpose:** Analyze performance by customer segment.  
**Visuals:**
- Donut Chart for Total Sales by Segment  
- Bar Chart for Segment-wise Sales Comparison  

**Insights:**
- Consumer segment contributes about one-third of total sales.  
- Corporate customers are more profitable per order.  
- Home Office segment shows consistent growth.

---

### 🟣 5. **Time & KPI Trend Dashboard**
**Purpose:** Evaluate yearly sales and profit performance trends.  
**Visuals:**
- Column Chart (Profit & Sales by Year)
- Line Chart (Sales PY vs Total Sales)
- KPI Cards for Profit Growth and Quantity Metrics  

**Insights:**
- Annual Sales average ₹12.6M from 2011–2014.  
- Steady profit margins maintained despite discount variations.  
- Consistent YoY sales performance with growth in Technology category.

---

## 💹 Additional Advanced Visuals

| Visual Type | Purpose |
|--------------|----------|
| **Waterfall Chart** | Profit breakdown by region/category |
| **Funnel Chart** | Sales-to-profit or order fulfillment process |
| **Map Visualization** | Profit distribution across countries |
| **Tree Map** | Category & Sub-category performance |
| **Line Chart** | Time-based trend analysis |
| **KPI Cards** | Key performance indicators with YoY comparison |

---

## 💡 Key Insights Summary

- 💰 **Total Sales:** ₹32.33M  
- 📈 **Total Profit:** ₹3.63M  
- 🛒 **Total Orders:** 25K  
- 🕒 **YoY Sales Growth:** Stable, positive profit trend  
- 🌍 **Top Regions:** Central, East, and North America  
- 🧍 **Top Segment:** Consumer (≈33% of total sales)  
- 🧩 **Top Categories:** Technology (Phones & Copiers)  
- ⚠️ **Optimization Area:** Furniture – high sales, low profit margin  

---

## 🧠 Business Impact
This dashboard empowers business leaders to:
- Identify top-performing regions and categories  
- Monitor profit trends across time  
- Optimize discounts and shipping costs  
- Understand customer segmentation and loyalty trends  
- Drive strategic, data-informed decision making  

---

## 🧰 Tech Stack

| Component | Tool / Language |
|------------|----------------|
| BI Tool | Microsoft Power BI |
| Data Model | Star Schema |
| Language | DAX (Data Analysis Expressions) |
| Dataset | Global Superstore Dataset |
| Visualization | Power BI Desktop |




